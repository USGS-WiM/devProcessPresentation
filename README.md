![WiM](wim.png)

  
  

# WIM Development Process Presentation

  

This is a [Reveal.js]([https://revealjs.com/#/](https://revealjs.com/#/)) presentation for describing WIM's model for collaborative development. 

  

### Prerequisites

  

This project requires Node.js v9.0.0+

 

### Full setup

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1.  Install  [Node.js](https://nodejs.org/)  (9.0.0 or later)
    
2.  Clone the  repository
    
    $ git clone [https://github.com/USGS-WiM/devProcessPresentation](https://github.com/USGS-WiM/devProcessPresentation)
    
3.  Navigate to the
    
    $ cd devProcessPresentation
    
4.  Install dependencies
    
    $ npm install
    
5.  Serve the presentation and monitor source files for changes
    
    $ npm start
    
6.  Open  [http://localhost:8000](http://localhost:8000/)  to view your presentation
    
    You can change the port by using  `npm start -- --port=8001`.
    

### [](https://github.com/hakimel/reveal.js#folder-structure)Folder Structure

-   **css/**  Core styles without which the project does not function
-   **js/**  Like above but for JavaScript
-   **plugin/**  Components that have been developed as extensions to reveal.js
-   **lib/**  All other third party assets (JavaScript, CSS, fonts)
  



  

## Contributing

  

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on the process for submitting pull requests to us. Please read [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for details on adhering by the [USGS Code of Scientific Conduct](https://www2.usgs.gov/fsp/fsp_code_of_scientific_conduct.asp).

  

## Versioning

  

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](../../tags).

  

Advance the version when adding features, fixing bugs or making minor enhancement. Follow semver principles. To add tag in git, type git tag v{major}.{minor}.{patch}. Example: git tag v2.0.5

  

To push tags to remote origin: `git push origin --tags`

  

*Note that your alias for the remote origin may differ.

  

## Authors

  
*  **[Blake Draper](https://github.com/BlakeDraper)** - *Lead Developer* - [USGS Web Informatics & Mapping](https://wim.usgs.gov/)
  

See also the list of [contributors](../../graphs/contributors) who participated in this project.

  

## License

  

This project is licensed under the Creative Commons CC0 1.0 Universal License - see the [LICENSE.md](LICENSE.md) file for details

  

## Suggested Citation

In the spirit of open source, please cite any re-use of the source code stored in this repository. Below is the suggested citation:

  

`This project contains code produced by the Web Informatics and Mapping (WIM) team at the United States Geological Survey (USGS). As a work of the United States Government, this project is in the public domain within the United States. https://wim.usgs.gov`

  
  

## Acknowledgments

  

WIM Developers Lauren Privette and Nick Estes who helped in developing and honing this process.

  

## About WIM

* This project authored by the [USGS WIM team](https://wim.usgs.gov)

* WIM is a team of developers and technologists who build and manage tools, software, web services, and databases to support USGS science and other federal government cooperators.

* WIM is a part of the [Upper Midwest Water Science Center](https://www.usgs.gov/centers/wisconsin-water-science-center).
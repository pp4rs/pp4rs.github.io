<!-- markdownlint-disable MD033 -->
<!-- see https://github.com/DavidAnson/markdownlint for code to enable or disable rules -->

# Module:  Installation Guide for Programming Practices for Research Students

[![GitHub Pages](https://github.com/pp4rs/2024-uzh-installation-guide/actions/workflows/deploy.yaml/badge.svg)](https://github.com/pp4rs/2024-uzh-installation-guide//actions/workflows/deploy.yaml)
[![lifecycle](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing)
[![lifecycle](https://img.shields.io/badge/version-2024.0-red.svg)]()


## Meta-Information

* Module Maintainer: Julius Schäper (`@jfschaeper`)
* Course: [Programming Practices for Research in Economics](https://pp4rs.github.io)
* Institute: Dept of Economics, Uni Zurich
* Current Version: [Fall 2024 edition](https://pp4rs.github.io/2024-uzh-installation-guide)

## Building the Site

The site is rendered using [MkDocs](https://www.mkdocs.org/) and build using GitHub actions.

If you want to build the site locally on your machine:

* Change your working directory to this one, and then create an environment with the necessary packages:

```{.bash}
conda env create -f environment.yml -n <env_name>
```

* Look at a copy of the site served locally on your machine:

```{.bash}
mkdocs serve
```

* The website will be served at http://127.0.0.1:8000/python/.

If you want to host the website on GitHub pages:

* Change your working directory to this one and run:
```{.bash}
mkdocs gh-deploy
```

* Behind the scenes, MkDocs will build your docs and use the ghp-import tool to commit them to the gh-pages branch and push the gh-pages branch to GitHub.

* Now navigate to 'Settings' in the GitHub repository and make sure 'Build and Deployment' has its source set to 'Deploy from a branch' and choose the 'gh-pages' branch with 'root' as the folder origin.

* After a short period of time the website should be available.

## Want to Contribute

* See the contributing guide [here](CONTRIBUTING.md).
* By contributing you agree to abide by the [Code of Conduct](CONDUCT.md)

## License

All materials are licensed under a Creative Commons CC-SA license. The license allows you to copy, remix and redistribute any of our publicly available materials, under the condition that you attribute the work (details in the license). More information is available [here](http://creativecommons.org/licenses/by-sa/4.0/)

## Suggested Citation

The suggested citation for the course materials is:

``` bash
Julius Schäper, 2024, Installation Guide, Programming Practices for Research in Economics, University of Zurich
```

If you find the installation guide useful - please drop us a line and say so - pp4rs@econ.uzh.ch

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />

This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

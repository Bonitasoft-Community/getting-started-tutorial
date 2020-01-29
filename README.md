# Getting started: workspace and .bos file

## Overview
This repository provides the solution for [Bonita getting started](https://documentation.bonitasoft.com/bonita//_getting-started-tutorial).

## Compatibility
This example has been built with Bonita 7.10.0 Community Edition.

It is compatible with all Bonita editions (Community and Enterprise).
It should remain compatible with any future releases.

## Artifacts provided
You can get the .bos file from the [release section on GitHub](https://github.com/Bonitasoft-Community/getting-started-tutorial/releases/latest). This .bos file includes:
* The process diagram with the process definition
* The Business Data Model (BDM)
* Instantiation and step forms
* Application page

## Importing the solution in Studio
To import the solution in Bonita Studio:
* Go to **File > Import > BOS archive...** Studio menu
* Click on **Browse...** button and select _claims-management.bos_ file
* Click on **Import** button

WARNING: When you import _claims-management.bos_ in your Studio, if some artifacts (BDM, diagrams...) with identical names already exsit, Studio will ask you if you want to override them. On Community Edition you might want to do that in a separated installation of Bonita Studio. With Enterprise Edition you probably want to import the bos file content to a new project.

Note: alternatively you can clone this repository in Enterprise Edition using Git integration.

## Deployment
Click on **File > Deploy** Bonita Studio menu to deploy all artifacts and open the application or the Portal homepage. For more details refer to [Bonita getting started](https://documentation.bonitasoft.com/bonita//_getting-started-tutorial).

## Issues tracker
Use [GitHub issue tracker](https://github.com/Bonitasoft-Community/getting-started-turorial/issues) to report issues.

## Content of the Git repository
If you follow the [Bonita getting started](https://documentation.bonitasoft.com/bonita//_getting-started-tutorial) you should end up with a workspace just like the content of this Git repository.


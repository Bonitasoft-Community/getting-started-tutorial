# Getting started: workspace and .bos file

## Overview
This repository provides the solution for [Bonita getting started](https://documentation.bonitasoft.com/bonita/latest/getting-started/getting-started-index).

## Compatibility
This example has been built with Bonita 2021.2 Community Edition.

It is compatible with all Bonita editions (Community and Enterprise).
It should remain compatible with any future releases.

## Artifacts provided
You can get the .bos file from the [release section on GitHub](https://github.com/Bonitasoft-Community/getting-started-tutorial/releases/latest). This .bos file includes:
* The process diagram with the process definition
* The Business Data Model (BDM)
* Instantiation and step forms
* Application page
* An Application descriptor
* A Timeline custom widget

## Importing the solution in Studio
To import the solution in Bonita Studio:
* Go to **File > Import > BOS archive...** Studio menu
* Click on **Browse...** button and select _claims-management.bos_ file
* Click on **Import** button

WARNING: When you import _claims-management.bos_ in your Studio, if some artifacts (BDM, diagrams...) with identical names already exsit, Studio will ask you if you want to override them. To avoid that, you probably want to import the bos file content to a new project.
{: .note}

**NOTE**: alternatively you can clone this repository using Git integration.
{: .note}

## Deployment
Click on **File > Deploy** Bonita Studio menu to deploy all artifacts and open the Claims management application or the Bonita user home page. For more details refer to [Bonita getting started](https://documentation.bonitasoft.com/bonita/latest/getting-started/getting-started-index).

## Releasing a new version

:warning: There is a known limitation that prevent the usage of a Github action to perform the release automatically.

Maintainer of the project can use the `maven-release-plugin` to publish a new release for this project.

* Java 11 and Maven 3.8.x is required to publish a release
* Checkout the `master` branch and run:

```
 mvn --batch-mode release:prepare -D releaseVersion=x.y.z -D developmentVersion=a.b.c-SNAPSHOT 
```

As a result a new tag should be pushed. You must now create a Github release from this tag and attached the generated .bos in the `target` folder. 

## Issues tracker
Use [GitHub issue tracker](https://github.com/Bonitasoft-Community/getting-started-turorial/issues) to report issues.

## Content of the Git repository
If you follow the [Bonita getting started](https://documentation.bonitasoft.com/bonita/latest/getting-started/getting-started-index) you should end up with a workspace just like the content of this Git repository.


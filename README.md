# ESS-DIVE API Tutorials

Jupyter+R: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ess-dive/essdive-tutorials/main)

RStudio: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ess-dive/essdive-tutorials/main?urlpath=rstudio)

Google Colab: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ess-dive/essdive-tutorials)

## DataSubmission: Getting started with ESS-DIVE Package Service 1.2.0
The ESS-DIVE Package Service is a service that enables projects to programmatically store data packages with ESS-DIVE. This is an alternative to using the ESS-DIVE web portal form for data uploads. This service encodes metadata using the JSON-LD specification. JSON-LD is a schema to encode linked Data using JSON, and in the future will be used by Google to index metadata for searches. The use of the standardized JSON-LD schema will dramatically increase the visibility of data packages, and also enable projects to create one-time code that can be reused for periodic uploads of data packages to ESS-DIVE.

The ESS-DIVE Package service allows you to submit JSON-LD data package metadata to ESS-DIVE’s sandbox instance, to test whether metadata curated by projects are mapped correctly onto ESS-DIVE’s data package metadata schema. Data package metadata refers to the top level metadata that enables a data package to be “discoverable” in search results. Examples of top-level metadata include the title, abstract, authors, variables and keywords. Other file-level metadata, such as those that describe the the data file structure or variables are not included in this service. The beta version also does not include submission of data files to ESS-DIVE.

Provide feedback on the package service to ess-dive-support@lbl.gov.

### Tutorial Material
There are two data submission tutorials available: Jupyter Notebook and RStudio. If you are not familiar with the API, we recommend starting with these tutorials, which walk through creating your JSON-LD metadata object and provide additional guidance for data submission. If you are familiar with the API and do not need step-by-step instructions, you can visit our [package service examples](https://github.com/ess-dive/essdive-package-service-examples/tree/4bcfe8fa2cd77c3f8bcf1895173a32a64f2196b5) for more streamlined notebooks and example code. 

## Search Data: Using Data with the Dataset and Deep Dive API (Python)
The ESS-DIVE Dataset API enables programmatic search of dataset metadata and access to their contents. The ESS-DIVE Deep Dive API enables direct search within data files across datasets that are following certain standards.
This Jupyter Notebook tutorial illustrates a data discovery workflow and approaches to searching for and exploring inside datasets using both the Dataset API and Deep Dive API. The example provided plots two data files in different datasets that have matching search terms and download both the files and dataset citations.

## FindingAccessingData: Approaches to Inspecting Datasets via the ESS-DIVE Dataset API
The ESS-DIVE Dataset API enables programmatic search of dataset metadata and access to their contents.

This Jupyter Notebook tutorial illustrates a general dataset search and approaches for inspecting dataset contents with and without FLMD and Data Dictionary files (ESS-DIVE Community File-level Metadata Reporting Format). It also illustrates inspection of datasets employing the ESS-DIVE Community Sample ID and Metadata Reporting Format.

Code to import csv files to Pandas dataframes and download data files to local storage are also included.

## Share Data: Lookup and Change Dataset Permissions
The ESS-DIVE Dataset API enables data contributors to programmatically review who currently has access to view, edit, or
manage their dataset, as well as, add or remove individuals from their dataset permissions. 

This Jupyter Notebook tutorial provides a basic example of how to execute the API's sharing operations for one dataset.
The example code could readily be expanded to manage dataset permissions in bulk.

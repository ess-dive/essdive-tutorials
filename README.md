# ESS-DIVE API Tutorials

Jupyter+R: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ess-dive/essdive-tutorials/HEAD)

RStudio: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ess-dive/essdive-tutorials/HEAD?urlpath=rstudio)

## Getting started with ESS-DIVE Package Service 1.2.0
The ESS-DIVE Package Service is a service that enables projects to programmatically store data packages with ESS-DIVE. This is an alternative to using the ESS-DIVE web portal form for data uploads. This service encodes metadata using the JSON-LD specification. JSON-LD is a schema to encode linked Data using JSON, and in the future will be used by Google to index metadata for searches. The use of the standardized JSON-LD schema will dramatically increase the visibility of data packages, and also enable projects to create one-time code that can be reused for periodic uploads of data packages to ESS-DIVE.

The ESS-DIVE Package service allows you to submit JSON-LD data package metadata to ESS-DIVE’s sandbox instance, to test whether metadata curated by projects are mapped correctly onto ESS-DIVE’s data package metadata schema. Data package metadata refers to the top level metadata that enables a data package to be “discoverable” in search results. Examples of top-level metadata include the title, abstract, authors, variables and keywords. Other file-level metadata, such as those that describe the the data file structure or variables are not included in this service. The beta version also does not include submission of data files to ESS-DIVE.

Provide feedback on the package service to ess-dive-support@lbl.gov.

## Tutorial Material
There are two data submission tutorials available. If you are not familiar with the API, we recommend starting with these tutorials, which walk through creating your JSON-LD metadata object and provide additional guidance for data submission. If you are familiar with the API and do not need step-by-step instructions, you can visit our [package service examples](https://github.com/ess-dive/essdive-package-service-examples/tree/4bcfe8fa2cd77c3f8bcf1895173a32a64f2196b5) for more streamlined notebooks and example code. 

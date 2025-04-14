# Submit Data: Getting started with ESS-DIVE Dataset API 1.13.0
The ESS-DIVE Dataset API is a service that enables projects to programmatically store datasets with ESS-DIVE. This is an alternative to using the ESS-DIVE web portal form for data uploads. This service encodes metadata using the JSON-LD specification. JSON-LD is a schema to encode linked Data using JSON, and is used by Google to index metadata for searches. The use of the standardized JSON-LD schema will dramatically increase the visibility of datasets, and also enable projects to create one-time code that can be reused for periodic uploads of datasets to ESS-DIVE.

The ESS-DIVE Dataset API allows you to submit JSON-LD dataset metadata to ESS-DIVE’s **sandbox instance** (https://data-sandbox.ess-dive.lbl.gov/), to test whether metadata curated by projects are mapped correctly onto ESS-DIVE’s dataset metadata schema. Dataset metadata refers to the top level metadata that enables a dataset to be “discoverable” in search results. Examples of top-level metadata include the title, abstract, authors, variables and keywords. Other file-level metadata, such as those that describe the the data file structure or variables are not included in this service.

Provide feedback on the Dataset API to ess-dive-support@lbl.gov.
### Tutorial Material
If you are not familiar with the Dataset API, we recommend starting with these tutorials, which walk through creating your JSON-LD metadata object and provide additional guidance for data submission. If you are familiar with the API and do not need step-by-step instructions, you can visit our [package service examples](https://github.com/ess-dive/essdive-package-service-examples/tree/4bcfe8fa2cd77c3f8bcf1895173a32a64f2196b5) for more streamlined notebooks and example code. 
- Tutorial_DataSubmission_R.Rmd (_Can be run on Binder using RStudio or Jupyter Notebook_)
- Tutorial_DataSubmission.ipynb

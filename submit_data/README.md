# Submit Data: Getting started with ESS-DIVE Dataset API 1.13.0
The ESS-DIVE Dataset API is a service that enables projects to programmatically store datasets with ESS-DIVE. This is an alternative to using the ESS-DIVE web portal form for data uploads that enables projects to create one-time code that can be reused for periodic uploads of datasets to ESS-DIVE. 

This service encodes metadata using the JSON-LD specification which is a schema to encode linked Data using JSON. 
The provided tutorials walk through creating your JSON-LD metadata object and provide additional guidance for data submission.

## Tutorial_DataSubmission (R + Python)
The data submission tutorial is available in both R and Python. These tutorials demonstrate the same capabilities. 
  
- Tutorial_DataSubmission_R.Rmd (_Can be run on Binder using RStudio or Jupyter Notebook_)
- Tutorial_DataSubmission.ipynb

The tutorials are designed to submit JSON-LD dataset metadata to ESS-DIVE’s **sandbox instance** (https://data-sandbox.ess-dive.lbl.gov/), to test whether metadata curated by projects are mapped correctly onto ESS-DIVE’s dataset metadata schema.

### Learn More
If you are familiar with the API and do not need step-by-step instructions, you can visit our [package service examples](https://github.com/ess-dive/essdive-package-service-examples) for more streamlined example code.

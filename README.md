# Magnetic resonance imaging datasets with anatomical fiducials for quality control and registration
<img width="757" alt="image (21)" src="https://user-images.githubusercontent.com/46094728/200840201-90d2e6ef-b066-4de9-8bae-79cb51bd2354.png">

[![DOI](.svg)](link)

## In this GitHub repo, you can find: 

1) data: Markups Comma-separated values file (i.e., *.fcsv extension) files for both templates and datasets. 
2) notebooks: Jupyter notebooks involved in creation of the JavaScript Object Notation (i.e., *.json) which is an adaptation from BIDS Appendix VIII on Coordinate systems.  
3) other: Information about rater experience, afids protocol, and interactive glass brain

## Compressed NIfTI-1 format (i.e., .nii.gz extension) for datasets involved in this study are available for download: 
1) 100 Unrelated Humman Connectome Project (AFIDs-HCP dataset; n = 30): 
2) Open Access Series of Imaging Studies (AFIDs-OASIS dataset; n = 30):  
3) London Health Sciences Center Parkinson's Disease Dataset (LHSCPD ; n = 40): 
4) Stereotactic Neurosurgery 7-Tesla Control Dataset (SNSX; n = 32): 

*Please review and agree to the Data Usage Terms, outlined in links to each dataset, before downloading imaging data.


## Downloading imaging data:

For users that have already accepted DUAs, they can download imaging data we make availible here by following directions provided below. We may ask for project assigned username or user input to confirm acceptance of the DUAs. 

Step #1: Install datalad 

https://www.datalad.org/#install

Step #2: clone our superdataset on your machine (afids-data)

`datalad install <link to this repository>` <-- run this where you want the data to live

Step #3: fill in cloned dataset content*

`datalad get .`  <-- run this from the parent afids-data directory to install all the data we release here

*users will be asked to input username credentials or indicate they have accepted the DUA before this stage runs.


## An important note on data imaging data license: 

We release our anatomical landmark annotaitons under the Attribution 4.0 International (CC BY 4.0) license, available in `AFIDS_LICENSE.txt` at the dataset level. However, the HCP and OASIS-1 imaging data are protected by a data usage agreement (DUA). If users wish to access this imaging data, they must accept DUAs which we make availible in the `IMAGING_DATA_USE_AGREEMENT.txt`, at dataset level. Specific instructions for accepting DUA is at the level of each dataset. 


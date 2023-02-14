# Magnetic resonance imaging datasets with anatomical fiducials for quality control and registration
<img width="757" alt="image (21)" src="https://user-images.githubusercontent.com/46094728/200840201-90d2e6ef-b066-4de9-8bae-79cb51bd2354.png">

<a href="https://doi.org/10.5281/zenodo.7640692"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.7640692.svg" alt="DOI"></a>


## In this GitHub repo, you can find: 

1) data: Markups Comma-separated values file (i.e., *.fcsv extension) files for both templates and datasets. 
2) notebooks: Jupyter notebooks involved in creation of the JavaScript Object Notation (i.e., *.json) which is an adaptation from BIDS Appendix VIII on Coordinate systems.  
3) other: Information about rater experience, afids protocol, and interactive glass brain

## Compressed NIfTI-1 images for datasets involved in this data release are available for download: 
1) 100 Unrelated Humman Connectome Project (AFIDs-HCP dataset; n = 30): https://github.com/afids/AFIDs-HCP
2) Open Access Series of Imaging Studies (AFIDs-OASIS dataset; n = 30): https://github.com/afids/AFIDs-OASIS
3) London Health Sciences Center Parkinson's Disease Dataset (LHSCPD ; n = 40): https://openneuro.org/datasets/ds004471
4) Stereotactic Neurosurgery 7-Tesla Control Dataset (SNSX; n = 32): https://openneuro.org/datasets/ds004470

*Please review and agree to the Data Usage Terms, outlined in links to the HCP and OASIS datasets, before downloading imaging data.

## Accepting Data Usage Agreements (DUA):
For information about specific dataset DUA, please consult the individual directories linked above. To download HCP and OASIS data, the user must accept their specific DUAs. As for our local datasets (i.e., LHSCPD and SNSX), they are released under Attribution 4.0 International (CC BY 4.0) license and no further user intervention is needed before following instructions for download below. Users can either download those datasets directly from links above, or by cloning the super dataset here via instructions below. 

## Downloading the afids-data super dataset:

1) Install datalad
https://www.datalad.org/#install
    

2) Clone our superdataset (afids-data) on your machine 
`datalad install -r https://github.com/afids/afids-data.git` run this where you want the data to live
    

3) fill in cloned dataset content
`datalad get -r .` run this from the parent afids-data directory to install all the data we release here

**Users will be asked to input username credentials or indicate they have accepted the DUA before this stage runs.



## An important note on data imaging data license: 

We release our anatomical landmark annotaitons under the Attribution 4.0 International (CC BY 4.0) license, available in `DERIVATIVE_DATA_USE_AGREEMENT.txt` at the dataset level. However, the HCP and OASIS-1 imaging data are protected by a data usage agreement (DUA). If users wish to access this imaging data, they must accept DUAs which we make availible in the `IMAGING_DATA_USE_AGREEMENT.md`, at dataset level. Specific instructions for accepting DUA is at the level of each dataset. 


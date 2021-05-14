# vest-wi-2018

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2018-wisconsin-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

## Raw from source: 

- VEST Wisconsin, 2018
    - Accessed, 11/10/2020
    - Source: VEST on the Harvard Dataverse
    - Direct link: https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/UBKYRU/OYQQMS&version=33.0 
    - Link to VEST 2018 Datasets:  https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/UBKYRU 
    
- US Census 2020 Redistricting Data Program Phase 2
    - Accessed: 03/09/2021
    - Source: US Census
    - Direct link to VTDs for Wisconsin: https://www.census.gov/geo/partnerships/pvs/partnership19v2/st55_wi.html 
    - Link to 2020 Redistricting Data Program Partnership Files (VTDs for state available from the second drop down menu): https://www.census.gov/geographies/mapping-files/time-series/geo/partnership.2020.html 
    - Note: One can download five county VTD shapefiles at a time. Each county’s data is a zip file with a number of other files, in addition to the VTDs. The VTD filename follow this format: PVS_19_v2_vtd_55[FIPS].All of the counties that required supplemental data from the Phase 2 release, per VEST documentation, are available.
    
    
## Inaccessible files: 
- Election Results and Wards Shapefile from the Wisconsin State Legislature Open Data Portal
- This is the primary file used in the VEST processing. On the Wisconsin LTSB Open Data Portal (https://data-ltsb.opendata.arcgis.com/) , ward boundaries with election results are only available at 2020 and 2011 boundaries (with multiple election years), as of the time of this report. VEST confirmed that they used a 2018 ward boundary file (personal communication, not in documentation), which is not currently available on the website. We were able to retrieve what we believe to be a similar file from the University of Wisconsin: https://geodata.wisc.edu/catalog/B41117FE-B7E9-423A-91C8-E0DF28ACA065 (retireved on 03/08/2021). The University of Wisconsin notes that they retrieved this file from the Wisconsin LTSB and is intended to represent 2018 wards.

## File processing: 

- `vest-wi-2018` - processing and documentation in markdown cells and comments

# vest-vt-2018

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2020-vermont-precinct-boundary-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

## **Raw from source:**
- VEST VT 2020 Data File  
  - Accessed: 07/20/21
  - Source: [VEST on the Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/K7760H)
 
- VEST VT 2020 Documentation
  - Accessed: 07/20/21
  - Source: [VEST on the Harvard Dataverse](https://dataverse.harvard.edu/file.xhtml?fileId=4938251&version=15.0)

- VT Precinct-Level Election Results
  - Accessed: 07/20/21
  - Source: [VT Secretary of State Election Archive](https://electionarchive.vermont.gov/elections/search/year_from:2020/year_to:2020/stage:General)
  - Note: For each needed election, click under Candidates -> See Details for Election -> Download this Election -> Precinct Results.

- VT State House Districts 2012 Shapefile
  - Accessed: 05/19/21
  - Source: [VT Open Geodata Portal](https://geodata.vermont.gov/datasets/vt-data-vermont-house-districts-2012?geometry=-80.269%2C42.477%2C-64.614%2C45.249)

- U.S. Census Bureau's 2020 Redistricting Data Program
  - Accessed: 08/04/21
  - Source: [US Census](https://www.census.gov/geo/partnerships/pvs/partnership19v2/st50_vt.html)
  - Note: Shapefiles can only be downloaded for up to 5 counties at a time, so we did some minor processing in combining the various county files into one folder.

- VT 2019 ACS Survey for Areas w/ Allocated Votes
  - Accessed: 07/20/21, Source: [U.S. Census](https://data.census.gov/cedsci/table?q=Buels%20gore&g=0600000US5000327962,5000363550,5000734600,5000902125,5000908725,5000911800,5000925975&tid=ACSST5Y2019.S0101&hidePreview=true)
  - Note: This table provides 2019 ACS population data for the areas where VEST allocated votes. 


## File processing

- `vest-vt-2020-validation.ipynb` - documentation in markdown cells and comments

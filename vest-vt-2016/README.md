# vest-vt-2016

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2016-vermont-precinct-and-election-results/). Still in progress as of 5/19/21.  

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

## **Raw from source:**
- File: VEST VT 16 data file
  - Online: [Harvard Dataverse Link](https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/NH5S2I/HWHE2M&version=56.0)
  - AWS: `vt_2016.zip` (available upon request)
  - Accessed: 05/19/21
  - Note:

- File: VEST VT 16 documentation file
  - Online: [Harvard Dataverse Link](https://dataverse.harvard.edu/file.xhtml?fileId=4499004&version=56.0)
  - AWS: `documentation.txt` (available upon request)
  - Accessed: 05/19/21
  - Note:

- File: VT Precinct-Level Election Results
  - Online: [VT Secretary of State Election Archive](https://electionarchive.vermont.gov/elections/search/year_from:2016/year_to:2016/stage:General)
  - AWS: `Election_Results` (available upon request)
  - Accessed: 05/19/21
  - Note: For each needed election, click under Candidates -> See Details for Election -> Download this Election -> Precinct Results. 

- File: VT Municipal-Level Election Results
  - Online: [VT Secretary of State Election Archive](https://electionarchive.vermont.gov/elections/view/82048/)
  - AWS: `Diff_Explanation` (available upon request)
  - Accessed: 05/19/21
  - Note: For each needed election, click under Candidates -> See Details for Election -> Download this Election -> Municipality Results. This file was downloaded to explain a slight difference in the election results.

- File: VT State House Districts 2012 Shapefile
  - Online: [VT Open Geodata Portal](https://geodata.vermont.gov/datasets/vt-data-vermont-house-districts-2012?geometry=-80.269%2C42.477%2C-64.614%2C45.249)
  - AWS: `VT_Data_-_Vermont_House_Districts_2012` (available upon request)
  - Accessed: 05/19/21
  - Note:

- File: VT 2010 Census County Subdivision Boundaries and Statistics
  - Online: [VT Open Geodata Portal](https://geodata.vermont.gov/datasets/01539ba1dec8418b867ec580424405aa_12/data?geometry=-80.269%2C42.477%2C-64.614%2C45.249&orderBy=NAMELSAD10)
  - AWS: `VT_2010_Census_County_Subdivision_Boundaries_and_Statistics` (available upon request)
  - Accessed: 05/19/21
  - Note:

- File: VT 2016 ACS Survey
  - Online: [US Census](https://data.census.gov/cedsci/table?q=Buels%20gore&g=0600000US5000327962,5000363550,5000734600,5000902125,5000902162,5000908725,5000911800,5000925975&tid=ACSST5Y2016.S0101&hidePreview=true)
  - AWS: `ACS` (available upon request)
  - Accessed: 05/19/21
  - Note: This table was constructed to include data for the following places: Averill town
Avery's gore
Canaan town
Buels gore
Huntington town
Brighton town
Ferdinand town
Glastenbury town
Shaftsbury town


## File processing

- `vest-vt-2016-validation.ipynb` - documentation in markdown cells and comments

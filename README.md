Information on vegetation and crop types near flux towers is a critical supplement for the interpretation of surface flux measurements. This repository presents vegetation data created from records collected by site-operations staff as part of Preventive Maintenance (PM) reports. These data are then used to supplement surface flux measurements collected by the ARM Eddy Correlation Flux Measurement System (ECOR) at the Southern Great Plains (SGP) extended and supplemental facilities. 

Vegetation information is collected within ARM PM reports and associated with flux data from three data streams (30ECOR/QCECOR and ECORSF) at 30-min resolution. PM reports observations were made user-friendly, especially for long-term measurements and multiple sites. Python scripts (Jupyter notebooks) were developed for users to analyze surface fluxes as a function of the vegetation types to support land-atmosphere interactions research.

Jupyter notebooks
-	SGP_30ECOR_Surface_Conditions.ipynb
-	SGP_30QCECOR_Surface_Conditions.ipynb
-	SGP_ECORSF_Surface_Conditions.ipynb
-	SGP_30QCECOR_Surface_Conditions_cropwise.ipynb

The first three notebooks provide python scripts to correlate the three different ECOR data streams with surface and vegetation conditions in the PM reports. These scripts help classify the data into observations from individual SGP facility locations. These scripts have the functionality to plot the seasonal trends in surface flux measurements (averaged at various temporal resolutions) whenever a specific crop was reported at a facility (Fig. 2). The final script provides similar analyses, but the data are classified as a function of a specific crop reported across all facilities to analyze the same data sets from a crop wise perspective (Fig. 3). Each notebook has extensive comments to describe the components. Questions regarding the use of these notebooks can be directed to the corresponding author.

Input data
-	Old SGP PM report observations (1999 – 2019) uploaded as an excel spreadsheet named SGP_Surface_Conditions.xlsx. 
This file contains the variables listed in Table 1. The table contains descriptions of the variables along with the most reported technician responses. 
-	New SGP PM report observations (2019 – present) uploaded as a .csv file named “sgp_sfccond_reports_YYYYMMDD.csv” where YYYYMMDD is the date of last update. 
New PM reports are uploaded biweekly. This file will be updated every 6 months to keep it updated with the latest PM report responses. The variables included in these data files are listed in Table 2. An example of a PM report is provided in the Github repository as “PM_Report_Example.pdf” with the response choices for each variable. 
-	ARM ECOR datastreams – please see the linked ARM instrument/VAP webpages.

Updated (4/22/2026): A new PM report dataset that includes new reports from September 2025 to April 2026 has been added. This increases the number of reports from 1796 to 1914.

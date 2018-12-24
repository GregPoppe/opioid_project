# Opioid Trends
**Trends in Opioid Use and Addiction by Geographical Regions**

**Team Members: Greg, Deep, Vannia, Mark**

For project details and presentation, please see **Opioid_Crisis.pptxbb**

#### The folowing modules are required to generate some project charts
   * **seaborn** : version 0.9.0 or later
   * **folium** : https://pypi.org/project/folium/

## Repository structure
* Top Level : Data aquisition and processing notebooks
* Data sub-folder : csv files from data acquisition step
* Charts sub-folder : Plot images from data processing step

### Top Level Folder Files
#### Project Information
   * **Opioid_Crisis.ppt** : Project presentation deck
#### Data Acquisition
   * **ProPublicaData_API_Calls.ipynb** : Data acquisition for opioid related legislation
      * Note that this notebook takes hours to run.
   * **censusData.ipynb** : Data acquisition for socio-economic and demographic information
   * **opioid_data_clean.ipynb** : Data clean for AMFAR county level data, ultimately not used
#### Data Processing 
   * **povertyAndOpioids.ipynb** : Processing and plots with demographic census data
   * **charts.ipynb** : Processing and plots with ethnic census data
   * **geojsonmap.ipynb** : Opiod death overlay on US map
   * **charts.ipynb** :
   * **ProPublicaData** : 
   * **ProPublicaDataCharts.ipynb** :
### Data Folder Files
   * **districtdata.csv** : AMFAR opioid stats by congressional district
   * **statedata.csv** : AMFAR opioid stats by state
   * **countydata.csv** : AMFAR opiod stats by county
   * **censusdata.csv** : ACS demographic population stats by congressional district
   * **censusData20181217** : ACS demographic population stats by congressional district
      * Included in **censusdata.csv** but still used by some notebooks, to be cleaned up
   * **censusbyrace.csv** : ACS ethnic population stats by congressional district
      * Included in **censusdata.csv** but still used by some notebooks, to be cleaned up
   * **votedataall.csv** : 2016 congressional bill/vote stats from ProPublica
   * **reps_short_list.csv** : 2016 members of congress ID from ProPublica 
   * **FIPs.CSV** : Map of state/district FIPS ID to state names
### Charts Folder Files
   * Plot images used in presentation

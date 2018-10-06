# Project 1

## Steps of the project:

* Mapping zipcodes boundaries : Done

* PV and SP from Zillow :
  - Data OK
  - Processing OK for current data --> need to go over time
  - Expected plots:
    - Heat map of current mean of PV (Zillow Estimate) by zipcodes  (august 2018)
    - Heat map of current mean of SP by zipcodes  (august 2018)
    - Heat maps for avg SP for each year
    - Line plots of interesting market (major changes) : 2 largest increases / 2 largest decreases

* Income : 
  - Data to process
  - Expected plots:
    - Heat map of current income (--> to compare with property value)
    - Heat map of income normalized by PV (to see where people spend the most of their income on housing)
    - Line plots of intersting zipcodes to identify sign of gentrification (or the opposite) and compare them to PV evolution

* Twitter sentiment analysis
  - Focus on the cities / zipcodes that exhibited the most changes or the most intersting trends
  - Analyse sentiment for each city name and compare with 
  - Number of tweets


* Further analysis/steps:
  - get data SP and PV from another source than Zillow



## Jupyter notebook description


### cleaning_zipcode_geojsonData.ipynb
Load the json resource file (az_arizona_zip_codes_geo.min.json) containing the geographic properties of all AZ zipcodes and select only the data of the Phoenix metropolitan area.
Create a new json file : phoenix_zip_codes_geo.json

### map_zipcode.ipynb
Making heatmap with zipcodes of the Phoenix metropolitan area

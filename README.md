# Project 1: The “Best” Place to Live in Phoenix

## Team
* Dana Martell
* Marie Parent
* Arthur Osakwe

## File description and organization
We all worked on the same branch so we divided the steps in different jupyter notebooks.

### Jupyter notebooks
* Data cleaning:
  - Crime_data_df
  - Income_DF
  - Sales_PV_DF
* Data mapping:
  - mapping_clean: TEMPLATE
  - maping_PVbyZipcode
  - mapping_crime
  - mapping_population
  - mapping_income
* Scatter plots
  - scatter_plots: crime vs income and property value
  - income_DF
* Tweeter sentiment analysis:
  - Phoenix_Sentiment_Analysis 

### Resources
* Zipcodes and Boundaries
  - zipcodes.cvs --> https://www.bestplaces.net/find/zip.aspx?st=az&msa=38060
  - az_arizona_zip_codes_geo.min.json (https://github.com/OpenDataDE/State-zip-code-GeoJSON)
  - az_arizona_zip_codes_geo_ms_simplified.json (same file but uploaded into https://mapshaper.org/ and simplified)
  - phoenix_zip_codes_geo_from_us_az_simplified.json : data from previous file filtered on Phoenix metropolitan area with "cleaning_zipcode_geojsonData.ipynb"
  - phoenix_zip_codes_geo_from_us_az_simplified_ms.json : same than before but uploaded and downloaded in https://mapshaper.org/ --> better organized text file
* INCOME data:
  - 16zp03az.xls --> https://www.irs.gov/statistics/soi-tax-stats-individual-income-tax-statistics-2015-zip-code-data-soi
  - clean_income_file.csv
* Real Estate:
  - Median_Sale_Prices_Time_Zip.csv --> https://www.zillow.com/research/data/
  - Current_Median_Property_Value_Zip.csv --> https://www.zillow.com/research/data/
* Crime data:
  - crime-data_crime-data_crimestat.csv: https://phoenixopendata.com/dataset/crime-data/resource/0ce3411a-2fc6-4302-a33f-167f68608a20
  - clean_crime_data_with_rates.csv
  - clean_crime_data.csv

### Plots
* Maps:
  - crime_number.html / crime_by_taxpayer.html
  - income_zip_2018.html
  - population_density.html
  - real estate: zillow_pv_2018.html, zillow_sp2018-01.html
* Scatter plot:
  - scatter_crime_vs_income.png, scatter_crime_vs_pv.png
  - property value and income: PV_AI.png
* Tweeter sentiment analysis
  - Overall_Media_Sentiment_based_on_Twitter_barchart.png





# HousingPricesProject
Housing Prices Trends using Zillow &amp; Census Data

## Resources

**Raw Data Source:**
Zip_zhvi_uc_sfrcondo.csv
Download from zillow.com/data - contains home value from 1996 to 2021 at the zipcode level for the entire US

census_data.csv
This file is copied from class activity resource

SP500_his_monthly.csv
This data is copied from Yahoo finance website
https://finance.yahoo.com/quote/%5EGSPC/history?period1=822528000&period2=1619308800&interval=1mo&filter=history&frequency=1mo&includeAdjustedClose=true

## Scripts
**DataCleaning.ipynb**
Data is cleaned in this python script. 4 output csv files are generated.
Transformation include reorder the columns, drop columns that are not useful for this analysis, merge data set, sort data set.
1. zillow_census_metro.csv - contain merged zillow zhvi data and census data for metro area for 2021/03/31
2. zillow_census_suburb.csv - contain merged zillow zhvi data and census data for suburb area for 2021/03/31
3. zillow_his_metro.csv - contain zillow zhvi data from 1996/01 to 2021/03 for metro area
4. zillow_his_suburb.csv - contain zillow zhvi data from 1996/01 to 2021/03 suburb area

**HousingPriceAnalysis.ipynb**
1.	Does income level increase as housing prices increase?<br/>
  a.	Scatter plot with regression for entire US<br/>
  b.  Scatter plot with regression for entire US for metropolitan areas<br/>
2.	Is median age correlated to housing prices?<br/>
  a.  Present age in buckets for categorical<br/>
  b.  Bar chart showing age categories vs median housing price<br/>
3.	How are housing prices correlated to population density?<br/>
  a.  Scatter plot with regression for entire US<br/>
  b.  Scatter plot with regression for entire US for metropolitan areas<br/>

**historical_trends.ipynb**
4.	Pricing trends from 1996 to 2021<br/>
  a. Line graph showing entire US and metropolitan areas<br/>
  b. Show entire US pricing trend vs stock market index <br/>
  c. Show entire US pricing trend vs lumber prices<br/>


 



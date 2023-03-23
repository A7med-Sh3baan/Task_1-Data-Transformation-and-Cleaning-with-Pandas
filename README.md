# Task_1-Data-Transformation-and-Cleaning-with-Pandas-1-
Python code that extract data from Excel file, clean and transform it, then load it into a Pandas DataFrame
# Transorm and Clean Data with Python


## Problem Description:

### Step 1:

Load the energy data from the excel file ```Energy Indicators.xls```, which is a list of indicators of [energy supply and renewable electricity production](Energy%20Indicators.xls) from the [United Nations](http://unstats.un.org/unsd/environment/excel_file_tables/2013/Energy%20Indicators.xls) for the year 2013, and load it into a Pandas DataFrame.


The output dataframe has the columns: `['Country', 'Energy Supply', 'Energy Supply per Capita', '% Renewable']`

### Step 2:

Load the GDP data from the file `world_bank.csv`, which is a csv containing countries' GDP from 1960 to 2015 from [World Bank](http://data.worldbank.org/indicator/NY.GDP.MKTP.CD) into a Pandas DataFrame

### Step 3:

Finally, load the [Sciamgo Journal and Country Rank data for Energy Engineering and Power Technology](http://www.scimagojr.com/countryrank.php?category=2102) from the file `scimagojr-3.xlsx`, which ranks countries based on their journal contributions in the aforementioned area into a Pandas DataFrame.

### Step 4:
Join the three DataFrames: GDP, Energy, and ScimEn into a new DataFrame using the intersection of country names. 
Only the last 10 years (2006-2015) of GDP data and the top 15 countries by Scimagojr 'Rank' (Rank 1 through 15) will be used.

### Step 5:

Find the average GDP over the last 10 years for each country.
Find the mean `Energy Supply per Capita`.
Find the country that has the maximum % Renewable and its percentage.
Find the country that has the highest ratio.
Find countries that are above and below the median.

## Tools and Technologies:
- Python 
- Pandas
- NumPy
- Jupyter Notebook

ETL Project, United States GDP and Personal Spending Data by State
Team 10: Aaron Bossard & Jin Lee

OVERVIEW:
We were interested in comparing gross domestic product data and personal savings data by state in the United States for 2018. 

EXTRACT:
Data Source 1: Bureau of Economic Analysis, Table 1. Percent Change in Real Gross Domestic Product (GDP) by State and Region, 2017:Q1-2018:Q4: https://www.bea.gov/data/gdp/gdp-state XLSX file with file converted to CSV file: qgdpstate0519_3.csv

Data Source 2: Bureau of Economic Analysis, Table 1. Personal Income, by State and Region, 2017:Q4-2019:Q1:  https://www.bea.gov/news/2019/state-personal-income-first-quarter-2019 XLSX file converted to CSV file: spi0619.csv

TRANSFORM:
Imported Personal Income, by State and Region as well as Percent Change in Real Gross Domestic Product (GDP) by State and Region
Selected certain columns
Renamed certain columns to make the data easier to read and to make indexing easer
Dropped rows with NaN values
Query to join tables

LOAD:
Created SQL database using Postgres and TablePlus

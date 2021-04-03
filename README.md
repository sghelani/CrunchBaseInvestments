# CrunchBaseInvestments
Ran the whole ETL workflow on data related to startup funding stored in a CSV file for further analysis.

## Description

* The data related to startup funding was loaded from a CSV file into a Pandas dataframe in a memory-efficient way.
* The data from the data frame was subsequently loaded into an SQLite database after applying appropriate transformations.
* SQL queries were run on the database to answer specific queries related to startup investments.

## Artifacts

* CrunchBase.ipynb:
This jupyter notebook contains all the code for the above functionality.

* Data/crunchbase-investments.csv:
The CSV file that contains all the data related to startup funding

* Data/crunchbase.db:
The database into which the data was finally loaded for analysis using SQL queries.

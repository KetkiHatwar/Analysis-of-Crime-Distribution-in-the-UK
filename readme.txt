

ANALYSIS OF CRIME DISTRIBUTION AND HOTSPOT PERSISTENCE IN HARINGEY

Install the required libraries
1. pandas: For data manipulation and analysis.
2. numpy: For numerical operations.
3. matplotlib: For plotting and visualization.
4. statsmodels: For statistical modeling, including time series decomposition and SARIMAX models.
5. pmdarima: For time series analysis and ARIMA model fitting.
6. math: For mathematical functions.
7. geopandas: For working with geospatial data.
8. seaborn: For statistical data visualization.
9. sklearn: For machine learning metrics.

Setup
1) Extract the zip file
2) Open CODE.ipynb file from the extracted folder.


Data
1)	The data is directly taken from the site https://data.police.uk/. 
2)	Data cleaning has been performed and all the CleanedData is saved in Cleaned_Dataset folder

Running the project:
Run all the files in CODE.ipynb. The following folders will be created along with visualizations and models:
All_boroughs: 33 London's bourough csv files created from filtering the Cleaned_Dataset.
Haringey: Haringey's data files
Camden: Camden's persistent data file 
Southwark: Southwark's persistent data file
Newham: Newham's persistent data file
Lambeth: Lambeth's persistent data file
Westminster: Westminster's persistent data file


Output
The script will generate various visualizations, models and results according to the problem statements.

Information for remaining files:
GeoJSON: contains the LSOA information for Map outlining
Cleaned_Dataset: Contains csv files of all London boroughs for each month from January 2021 to April 2024.
data_cleaning_code: The data cleaning code has been done using the code in this file for each raw file.
highest_crime_types: Highest crime type for each borough
number_of_cases_over_time_LONDON: Cases count for each month for overall London boroughs.
statement: Signed statement
Ketki Sanjay Hatwar_23025697_Grigoros Laukides_FinalReport_2023-24: Report source file












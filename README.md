# WildfireDataAnalysis

This is the code repository for the Wildfire Data Preprocessing and Analysis. The goal of this project is to analyze wildfire data from 2004-2024 primarily based on cause. 

The directory structure is: 

Code: 
Data_Analysis.ipynb - Analyzing the data for the number of wildfires per year, number of wildfires per cause, avg size of wildfires per cause, and creating figures and tables
Data_Preprocessing.ipynb - Filtering out the wildfire data for desired time frame + state, as well as separation of date information

Data/Input: 
CA_Fire_Perimeter_ALL.csv - original dataset from the California Open Data Portal
Metadata_CA_Fire_Perimeter.pdf - Metadata information for the dataset

Data/Output/Plots:
AverageAreaByCause.png - Bar graph of average fire area by cause
NumberByCause.png - Bar graph of the number of wildfires by cause
OccurenceByYear.png - Line plot of the number of wildfires per year

Data/Output/Tables:
WildfireCauseStats.csv - Statistics of the Cause subsets, including total number of fires, percentage of all fires, and average area
WildfireCountByCause.csv - Table of how many wildfires occurred for each cause subset for every year
WildfireCountByYear.csv - Table of how many wildfires occurred each year

Data/Output/PreprocessedData:
CA_Fire_Perimeter_FILTERED.csv - Filtered dataset after preprocessing

# What-impacts-the-earning-of-the-taxi-drivers

# Overview
This is 2021S2 MAST30034 Project 1 on quantitative analysis. This project aims to explore the factors impacting the earnings of yellow-taxi drivers in New York City. In an environment where the annual median wage for taxi drivers is $25,880, understanding the dynamics of income generation becomes crucial. Unlike many professions, taxi drivers rely not only on standard fares but also on tips, making their earnings unpredictable. The goal is to provide insights and recommendations for drivers, particularly in choosing optimal pick-up regions or targets. Additionally, the project employs a Generalized Linear Model (GLM) regression to predict tip amounts, offering drivers a tool to anticipate their earnings before accepting a trip.

# Datasets
- NYC TLC: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page
- Daily Summaries Station Details for Climate Data: https://www.ncdc.noaa.gov/cdo-web/datasets/GHCND/stations/GHCND:USW00094728/detail
- Hotels Properties Citywide: https://data.cityofnewyork.us/City-Government/Hotels-Properties-Citywide/tjus-cn27

# Directory
- `raw_data`: Contains all the raw data files. You may add this folder to `.gitignore` if your files are too large, but you **must** provide code to automatically download or links so that we may manually download them. 
- `preprocessed_data`: Contains all the preprocessed data files. You may add this folder to `.gitignore` if your files are too large, but your script should automaticaally generate files here given the correct dataset in `raw_data`.
- `plots`: Contains all figures or plots used in the report.
- `code`: Notebooks and scripts for each stage of code.
    - 'Download' Notebook for "Extracting Data".
    - 'Preprocessing' Notebook for "Preprocessing" for each month of raw data.
    - 'What impacts the earning of the taxi drivers' Notebook for the rest including "Feature Engineering", "Add External Data", "Remove Outliers", "Geospatial Visualisation", "Descriptive Statistic" and "Statistical Modelling" which is clearly divided into sections in the notebook.
- `deprecated`: A folder to store "old code" that **is not used anymore**.
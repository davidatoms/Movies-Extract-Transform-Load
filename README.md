# Movies-Extract-Transform-Load

The purpose of this project was to learn and perform the extract, transform, and load method on various datasets to predict films that would become popular for a streaming device. Extract, transform, and load (ETL) are three database functions to systematically make the data more accessible and easy to analyze.

## Overview
1. *Extract* - Before data can be moved, it needs to be extracted from its source. The first step is to know where to get the data, and then extract or mine that data for usage. Raw data is available in many places including existing databases and legacy systems, cloud and on-premises environment, applications, data platforms, and data warehouses.
2. *Transform* - This step includes cleansing, standardizing, deduplicating, verifying, and sorting the data that has been extracted for analysis. Each of these steps is crucial to make the analysis more accurate and more clean.
3. *Loading* - This phase is taking the clean data and making it available for usage by the analyst, team of analysts, or group going to use the data. There are a few types of loading. This final step is the link between the analyst intelligence and the raw data available. 

## The Challenge:
[x] Create a function (extract_transform_load) that runs through various datasets of movies to perform the three tasks listed above.

## The Datasets:
- wikipedia-movies.json
- movies_metadata.csv
- ratings.csv

This data has been pulled from wikipedia.org/movies and multiple Kaggle datasets for usage in the class. The data needed to be extracted, cleaned, and loaded for usage in an SQL data set. 

## The Process:
Using Python, I pulled data from some sites and prepared it for the next phase. Using Alchemy on Python, I connected the data from phase 2 to a database in SQL for phase 3.

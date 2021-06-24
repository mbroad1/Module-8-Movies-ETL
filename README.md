# Module 8 Challenge: Movies ETL

## Purpose:
The purpose of this analysis was to create an ETL pipeline for the two Kaggle datasets, movies_metadata.csv and ratings.csv, and the Wikipedia JSON of movies and their respective information. To do this, I refactored the code created in the module by creating an over-arching function called "extract_transform_load" that extracted the data from all of the given data sets, transformed them by cleaning up the bad data in those data sets, and then finally loading them into a PostgreSQL database. The final results matched the outcomes described in the challenge with the SQL movies table having 6,052 rows and the SQL ratings table having 26,024,289 rows as shown in the images of these queries and their outputs in the Resources folder.

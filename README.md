# DABC-Movies-ETL

The purpose of this exercise is to create a clean database with a list of movies with their ratings through an ETL process. This is performed by extracting a list of movies on Wikipedia in json format, and extracting movie ratings from Kaggle in csv format. With each set of raw data in place, Python and Pandas is used to read each set of raw data as a DataFrame, transform and clean the data into a format that is consistent across all movies. Once cleaned, the Wikipedia movies data and the ratings data from Kaggle are merged into one dataframe, and further cleaning is performed. Cleaned data is then loaded into the SQL database.

## Resource

- Data source: wikipedia-movies.json, movies_metadata.csv, ratings.csv
- Software: Python, Pandas, PostgresSQL

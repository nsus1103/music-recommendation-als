# music-recommendation-als

The accompanying scripts load the Lastfm data which has records of 3 million artists' songs listened to by over 17 million users.
The data is compressed with gzip.

The script recommendation dataset.ipynb Extracts, Transforms and Loads the files into Databricks filestore as Hive table.

The script recommender.ipynb loads the dataset using SparkSQL into dataframe and uses ALS for learning User preferences and Song characterstics to finally make recommendations on the test data.

# Movies-ETL
# Overview of the Analysis: 
This analysis was to help Hackathon to use clean dataset by using raw data from multiple places and then use the strategy of Extract, Transform and Load for a database on Movies. We have used the data from both Wikipedia and Kaggle. The extract of Wikipedia is saved under resources folder as Wikipedia-movies.json. Movies-mega data and ratings has been downloaded from Kaggle and both (movies_metadata.csv and ratings.csv) are saved under resources folder.

Jupyter notebook in Python is used to EXTRACT the Wikipedia and Kaggle data from their files, TRANSFORM the dataset by cleaning them and merging the data together. Later LOAD the clean dataset into SQL database (PostgresSQL). 

There were total of 6052 movies are imported into the SQLdatabase(“movie_data”) and 26,024,289 ratings across all the movies. Queries shows the result of import of database: 
![Movies-ETL]( https://github.com/Zainak94/Movies-ETL/Resources movies_query.png/)
![Movies-ETL]( https://github.com/Zainak94/Movies-ETL/Resources/ratings_query.png)

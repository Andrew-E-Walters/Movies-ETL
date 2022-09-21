# Movies-ETL

## Purpose
The purpose of this challenge was to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. We also need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

## Deliverable #1 
### An ETL is written to read the three data tables


### wiki movies_df
![Wiki_movies](https://github.com/Andrew-E-Walters/Movies-ETL/blob/main/Images/wiki_movies.png)

### keggle_metadata
![keggle_metadata](https://github.com/Andrew-E-Walters/Movies-ETL/blob/main/Images/keggle_metadata.png)

### ratings
![ratings](https://github.com/Andrew-E-Walters/Movies-ETL/blob/main/Images/ratings.png)


## Deliverable #2

### Extract and transform the Wikipedia data so you can merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates, use a try-except block to catch errors.

### wiki_movies_cleaned
![wikimovies](https://github.com/Andrew-E-Walters/Movies-ETL/blob/main/Images/wiki_movies_clean.png)

### wiki_movies coulmns
![wikimovies_columns](https://github.com/Andrew-E-Walters/Movies-ETL/blob/main/Images/wiki_movies_column.png)

## Deliverable #3

### Using your knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Then, you’ll merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, you’ll merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.


### movies_with_rating
![movies_with_rating](https://github.com/Andrew-E-Walters/Movies-ETL/blob/main/Images/movies_with_ratings.png)

### movies_df
![movies_df](https://github.com/Andrew-E-Walters/Movies-ETL/blob/main/Images/movies_df.png)

## Deliverable #4

### Use your knowledge of Python, Pandas, the ETL process, code refactoring, and PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.

REWIND


### upload
![upload](https://github.com/Andrew-E-Walters/Movies-ETL/blob/main/Images/extract_transform_load.png)

### movies query
![movies query](https://github.com/Andrew-E-Walters/Movies-ETL/blob/main/Images/Screenshot%202022-09-15%20203814.png)

### ratings query
![ratingsquery](https://github.com/Andrew-E-Walters/Movies-ETL/blob/main/Resources/ratings_query.png?raw=true)

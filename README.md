# Movies_ETL

Regina Negrycz 
genglist@yahoo.com 
Module 8 Challenge 
Submitted 13 Jun 2021 
Due 20 Jun 2021 
ETL_function_test.ipynb
ETL_clean_wiki_movies.ipynb
ETL_clean_kaggle_data.ipynb
ETL_create_database.ipynb
Resources/wikipedia-movies.json
Resources/movies_metadata.csv
Resources/movies_query.png
Resources/ratings_query.png
README

# Deliverable 1 - Write an ETL Function to Read Three Data Files

Use Python, Pandas, the ETL process, and code refactoring to write a function that reads in the three data files and creates three separate DataFrames.

# Deliverable 2 - Extract and Transform the Wikipedia Data 

Use Python, Pandas, the ETL process, and code refactoring, extract and transform the Wikipedia data to merge it with the Kaggle metadata. Use a try-except block to catch errors when extracting the IMDb IDs using a regular expression string and dropping duplicates.

# Deliverable 3 - Extract and Transform the Kaggle Data

Use Python, Pandas, the ETL process, and code refactoring, extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.

# Deliverable 4 - Create the Movie Database
Use Python, Pandas, the ETL process, code refactoring, and PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.
# Movies-ETL
Extract, Transform, and Load with movie data

#### Purpose
The purpose of this project is to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. So, I am refactoring code that I created during my practice exercises to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database. Four analysis deliverables were developed for this process.

#### Deliverable 1: Write an ETL Function to Read Three Data Files
- Using Python, Pandas, the ETL process, and code refactoring, a function is created to read in three data files and create three separate DataFrames.
- ETL_function_test.ipynb is added to the respository

#### Deliverable 2: Extract and Transform the Wikipedia Data 
- Wikipedia Data is extracted and transformed with the lambda and join functions so it can be merged with the Kaggle metadata.
- IMDb IDs is extracted using a regular expression string and code to drop duplicates while a try-except block is used to catch errors.
- ETL_clean_wiki_movies.ipynb is added to the repository.

#### Deliverable 3: Extract and Transform the Kaggle data
- Kaggle metadata and MovieLens rating data is extracted, transformed, then converted into separate DataFrames.
- Kaggle metadata DataFrame is merged with the Wikipedia movies DataFrame to create the movies_df DataFrame.
- MovieLens rating data DataFrame is merged with the movies_df DataFrame to create movies_with_ratings_df DataFrame.
- ETL_clean_kaggle_data.ipynb is added to the repository.

#### Deliverable 4: Create the Movie Database
- The movies_df DataFrame and MovieLens rating CSV data is added to a SQL database using PostgreSQL.
- The number of rows for each table is checked using SELECT COUNT(*)
- ETL_create_database.ipynb, movies_query.png, and ratings_query.png was added to the repository.

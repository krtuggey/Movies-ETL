# Movies-ETL
Extract, Transform, and Load with movie data

#### Purpose
The purpose of this project is to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. So, I am refactoring code that I created during my practice exercises to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database. Four analysis deliverables were developed for this process.

#### Deliverable 1: Write an ETL Function to Read Three Data Files
- An ETL function is created to read in the three data files
- The function converts all of the files into dataframes.
- ETL_function_test.ipynb is added to respository

#### Deliverable 2: Extract and Transform the Wikipedia Data 
- TV shows are filtered out
- The wiki_movies dataframe is created and IMDb IDs are extracted with a try-except block
- Wikipedia data is extracted and transformed within in the ETL function using the lambda and join functions as well as regular expressions.
- Wikipedia data is added to a Pandas Dataframe
- ETL_clean_wiki_movies.ipynb is added to repository

#### Deliverable 3: Extract and Transform the Kaggle data
#### Deliverable 4: Create the Movie Database

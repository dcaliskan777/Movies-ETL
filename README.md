# Movies-ETL

## Content

### Deliverable 1: Write an ETL Function to Read Three Data Files

The ETL Function is

![ETL_function_test](ETL_function_test.ipynb)

The outputs are

wiki_movies_df

![](Resources/11.wiki_movies_df.png)

kaggle_metadata

![](Resources/12.kaggle_metadata.png)

ratings

![](Resources/ratings.png)

### Deliverable 2: Extract and Transform the Wikipedia Data

The code of the deliverable 2 is

![ETL_clean_wiki_movies](ETL_clean_wiki_movies.ipynb)

The outputs are

wiki_movies_df_head

![](Resources/21.wiki_movies_df_head.png)

wiki_movies_df_colums_list

![](Resources/22.wiki_movies_df_columns_list.png)

Notice that in the output given in the challenge the number columns is 23 but in my project it is 21.
In the challenge Budget and Release date columns were not dropped; so these columns are contained two times in the data frame, as old and new. I dropped old columns.

### Deliverable 3: Extract and Transform the Kaggle Data

The code of the deliverable 3 is

![ETL_clean_kaggle_data](ETL_clean_kaggle_data.ipynb)

The outputs are

movies_with_ratings_df

![](Resources/31.movies_with_ratings_df.png)

movies_df

![](Resources/32.movies_df.png)

### Deliverable 4: Create the Movie Database

The code of the deliverable 4 is

![ETL_create_database](ETL_create_database.ipynb)

The outputs are

movies_query

![](Resources/movies_query.png)

rating_query

![](Resources/rating_query)

elapsed_time

![](Resources/43.elapsed_time.png)

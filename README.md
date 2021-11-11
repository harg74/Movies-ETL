# Movies-ETL

## Project Overview

For its Hackathon, Amazing Prime, required to create an ETL pipeline that helps to automate processing large datasets.

## ETL pipeline process:

<img width="731" alt="Screen Shot 2021-11-03 at 21 33 22" src="https://user-images.githubusercontent.com/78564912/141254412-59f0a37b-144e-4ad4-838b-aef0494f0ada.png">

- ### Extract phase:
  Involved the data retrieval from .json and .csv files from sources: [Wikipedia](https://es.wikipedia.org/wiki/Wikipedia:Portada), [Kaggle](https://www.kaggle.com/) and [IMDB](https://www.imdb.com/).
  
- ### Transform phase:
- 
  Involved cleaning the data and transformining it, also included removing missing values and corrupted data, plus  formatting.
  
  SEE FULL CODE HERE --->
  
  https://github.com/harg74/Movies-ETL/blob/main/ETL_clean_kaggle_data.ipynb
  
  https://github.com/harg74/Movies-ETL/blob/main/ETL_clean_wiki_movies.ipynb

- ### Load phase:

  Finally in this phase, we connected and imported our transformed data into PosgreSQL through pgAdmin.
  
  - **Ratings table:**
  
  ![ratings](https://user-images.githubusercontent.com/78564912/141252533-03a41b86-0fc6-46a2-ad42-c5cd33c8a21a.png)
  
  - **Movies table:**
  
  ![movies](https://user-images.githubusercontent.com/78564912/141252560-c8874826-4598-41d4-8913-0fb31e1ec239.png)
  
## Summary

Leveraging with the ETL methodology we were able to retreive, clean and load into a database our data from different sources, which is now ready to be used by the hackaton members.


# **Building And Deploying A Netflix Recommender System**

Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API. 

We use *web scraping* to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.

## Importing of datasets
To import the csv files, run the following command

import kagglehub

path = kagglehub.dataset_download("tmdb/tmdb-movie-metadata")

print("Path to dataset files:", path)

## Similarity.pkl
inorder to obtain the similarity.pkl, run the notebook to obtain the file as well as other files required

## Running Streamlit Tests

To run a Streamlit deployment tests, run the following command

```bash
  streamlit run main.py
```

## Deployment

### Steps To Deploy The App:

Prepare your dataset:

        1. Data Extraction
        2. Exploratory Data Analysis(EDA)
        3. Feature Engineering
        4. Model Building and Tuning
        5. Building tmdb API
        6. Pushing code to Github
        7. Connecting to your streamlit account 
        8. Deploy App


## 🛠 Skills
- Python  
- Statistics 
- SQL 
- Machine Learning 
- Deep Learning
- Artificial Intelligence
- Data Science

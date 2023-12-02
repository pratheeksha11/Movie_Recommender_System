# Content-Based Movie Recommender System

This project implements a content-based recommender system for movies. It uses data from the TMDb database to recommend movies based on similarities in content.

## Features

- Data integration from `tmdb_5000_movies.csv` and `tmdb_5000_credits.csv`.
- Extraction and transformation of key fields: `movie_id`, `title`, `overview`, `genres`, `keywords`, `cast`, `crew`.
- Data cleaning and preprocessing, including handling missing values and text processing.
- Feature engineering to combine different textual fields into a unified tag.
- Implementation of a cosine similarity metric to measure similarities between movies.
- A function `recommend(movie)` to find and list movies similar to a given movie.

## Technologies Used

- Python
- Pandas for data manipulation.
- NLTK for natural language processing.
- Scikit-learn for text vectorization (CountVectorizer) and cosine similarity computation.

## Setup and Usage

1. Ensure Python is installed along with Pandas, NLTK, and Scikit-learn.
2. Download the datasets `tmdb_5000_movies.csv` and `tmdb_5000_credits.csv`. [Go to think link for dataset]()
3. Run the Jupyter Notebook to process the data and train the model.
4. Use the `recommend(movie)` function to get movie recommendations.

## Data Source

The datasets are from the TMDb database and include movie details along with cast and crew information.

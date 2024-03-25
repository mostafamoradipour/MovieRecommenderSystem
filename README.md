# Movie Recommender System
This project implements a movie recommender system using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization technique. The recommender system suggests movies similar to a selected movie based on textual features such as genres, keywords, and overview.

# Dataset
The recommender system is built using the TMDB (The Movie Database) Movie dataset, which contains information about various movies including genres, keywords, overview, vote average, and vote count.

# Features
TF-IDF Vectorization: Textual features such as genres, keywords, and overview are transformed into numerical vectors using TF-IDF vectorization.
Cosine Similarity: Cosine similarity metric is used to measure the similarity between movies based on their TF-IDF vectors.
Top 5 Recommendations: The system recommends the top 5 most similar movies to a selected movie.
# Usage
To use the recommender system:

Ensure you have Python installed on your system.
Clone this repository.
Download the TMDB Movie dataset (tmdb_5000_movies.csv) and place it in the project directory.
Run the movie_recommender.py script to see the recommendations.
bash
Copy code
python movie_recommender.py
# Dependencies
pandas
scikit-learn
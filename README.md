# Movie-Recommendation-System
This project is a Movie Recommendation System that suggests movies similar to a user’s favorite movie based on various features like genre, keywords, tagline, cast, and director. It uses text-based similarity measures to provide recommendations.
Features
Feature Extraction: Combines multiple movie attributes into a single text feature for each movie.
Text Vectorization: Converts text features into numerical vectors using TF-IDF vectorization.
Similarity Calculation: Computes cosine similarity scores between movies based on their vectorized features.
Movie Recommendation: Provides movie recommendations by finding the most similar movies to a user-provided favorite movie.
Functionalities
Import Libraries and Dataset:
Imports necessary libraries such as pandas, numpy, sklearn, and difflib.
Loads and previews the movie dataset from a CSV file.
Feature Extraction:
Extracts relevant features from the dataset and combines them into a single text field for each movie.
Text Vectorization:
Uses TfidfVectorizer to convert text features into numerical vectors.
Similarity Calculation:
Computes cosine similarity scores between movies to determine how similar they are.
User Input for Movie Name:
Takes user input for a favorite movie name and finds the closest matching movie title from the dataset.
Generate Recommendations:
Retrieves and sorts similar movies based on similarity scores.
Outputs the top 30 (or top 10, based on user preference) recommended movies.

# Movie-Recommendation-System
The Movie Recommendation System is designed to suggest movies similar to a user’s favorite film by analyzing various features from a dataset. This system leverages text-based similarity techniques to provide personalized movie recommendations. The project uses features such as movie genre, keywords, tagline, cast, and director to compute similarity scores and recommend movies that are most similar to the one selected by the user.

"Key Features"

Comprehensive Feature Extraction: Integrates multiple movie attributes including genre, keywords, tagline, cast, and director into a single text feature for each movie.
TF-IDF Vectorization: Converts textual features into numerical vectors using Term Frequency-Inverse Document Frequency (TF-IDF) to capture the importance of words in the context of the dataset.
Cosine Similarity Measurement: Calculates the cosine similarity between movies based on their vectorized features to determine how similar they are to each other.
Personalized Recommendations: Allows users to input their favorite movie and provides a list of recommended movies that are similar to the chosen film.

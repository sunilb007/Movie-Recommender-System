Movie Recommender System

This project develops a Movie Recommender System designed to help users discover new movies based on their preferences and interactions. Leveraging a blend of content-based and collaborative filtering techniques, the system provides personalized recommendations and continuously improves through a user feedback loop.

Features
Personalized Recommendations: Generates movie suggestions tailored to individual user tastes.
Content-Based Filtering: Recommends movies similar to those a user has enjoyed based on genres, keywords, and other metadata.
User Feedback Integration: Incorporates user ratings and interactions (e.g., likes/dislikes) to refine future recommendations.
Dynamic Updates: The system adapts its recommendations as new user data becomes available.

Dataset
The system utilizes movie data fetched and enriched via the TMDB (The Movie Database) API. This includes comprehensive metadata such as genres, keywords, cast, crew, and plot summaries. The dataset is continuously updated to ensure fresh recommendations.

Methodology
The core of this recommender system is built upon a hybrid approach:
Data Acquisition & Preprocessing: Movie metadata is collected from the TMDB API. This data undergoes rigorous cleaning, transformation, and feature engineering to create a structured dataset suitable for analysis.
Content-Based Engine: This component analyzes movie attributes (e.g., genre, director, actors, plot keywords) to identify movies that are similar to a user's past preferences. Techniques like TF-IDF vectorization and cosine similarity are employed.
User Feedback Loop: A critical aspect of this system is its ability to learn from user interactions. When a user rates a movie or provides implicit feedback (e.g., watches a movie, adds to watchlist), this data is captured and used to update their preference profile. This feedback mechanism allows the system to continuously refine its recommendations, moving towards a more collaborative filtering-like behavior over time, even without explicit collaborative filtering algorithms. This dynamic adaptation ensures that recommendations become more accurate and relevant with increased user engagement.

Technologies Used
Python: The primary programming language for data processing, model development, and API interaction.
Pandas: For efficient data manipulation and analysis.
scikit-learn: For various machine learning algorithms, including feature extraction (e.g., TF-IDF) and similarity calculations.
TMDB API: For accessing comprehensive movie data.


Future plans - Mkae a stearmlit app, add sementic meaning, and movie info - Lets see how many can I do

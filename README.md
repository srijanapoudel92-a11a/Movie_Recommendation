Movie Recommendation System 
Project Overview

This project focuses on building a movie recommendation system that suggests movies similar to a user’s selected movie. It uses the MovieLens dataset, which includes movie details, user information, and ratings.

Dataset

The MovieLens dataset contains 3,883 movies, 1,000,209 ratings, and 6,040 users. Movie genres are used as the main information for finding similar movies.

Recommendation Approach

The system uses two text vectorization methods: TF-IDF and CountVectorizer. These methods convert movie genres into numerical features. Cosine similarity then compares the movies and identifies those with similar genres.

System Evaluation

The two approaches are compared using Precision@5 and Recall@5. These measures help show how relevant the recommended movies are in the test data.

GUI Prototype

The system includes a Gradio GUI where users can enter a movie title and receive five similar movie recommendations.

Conclusion

This project demonstrates a simple way to recommend movies based on genre information. It combines text vectorization, cosine similarity, and a user-friendly interface to provide movie suggestions.

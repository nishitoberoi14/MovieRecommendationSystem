# MovieRecommendationSystem
AI4ALL Ignite Project Proposal

Adrian Maldonado, Nishit Oberoi, Kanchan Thapa

Topic: Movie Recommendation System

Research Question: 

How can machine learning algorithms be optimized to provide personalized movie recommendations based on user preferences and behavior, considering factors such as genre, actors, directors, user ratings, and viewing history?

Summary: 

A movie recommendation system is crucial for modern entertainment services like Netflix, Hulu and other streaming sites. By leveraging both content-based and collaborative filtering techniques, this project aims to optimize machine learning algorithms to provide personalized movie recommendations tailored to individual user preferences and behavior. The system considers a variety of factors, including genre, actors, directors, user ratings and overview to guide users from one movie to the next.

This data will help address the research question of how machine learning algorithms can be optimized for personalized movie recommendations. By utilizing both content-based and collaborative filtering methods, the project seeks to develop an intelligent system that learns from user behavior and preferences to suggest movies that users are most likely to enjoy. The goal is to create a more engaging and satisfying entertainment experience for users.

Sources of Bias: 

Selection bias: The Kaggle dataset has majority of films primarily from Hollywood and do not include other international or independent film studios

Rating bias: The people may rate movies predetermined based on the genre, director of the film without having actually taken an objective view of the movie.

Popularity bias: Items that are highly rated or frequently watched may dominate recommendations, leading to a tendency to recommend popular items over more personalized or diverse choices.

Machine Learning Algorithm:

We chose content-based filtering to recommend movies, focusing on attributes like genre, actors, directors, overview, and user ratings. Using 5,000 common words from movie content, the algorithm represents movies as vectors and matches them based on their similarities using cosine similarity. We selected the nearest 5 vectors to recommend movies, generating personalized suggestions aligned with user preferences and content characteristics.

Collaborative filtering is another approach we considered for movie recommendation, analyzing user-item interactions to identify patterns and make predictions about users' preferences. By leveraging the behavior of similar users or items, we used collaborative filtering to provide personalized recommendations.our algorithm identified users with similar preferences to the target user and recommended items they have liked. This approach relied on the assumption that users who have liked similar items in the past will have similar preferences in the future.

Datasets:

We selected datasets from Kaggle's open-sourced dataset website to train and evaluate our machine learning model for content-based recommendations.Additionally, we utilized datasets from GroupLens for collaborative filtering. 

[TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

[MovieLens 25M Dataset](https://grouplens.org/datasets/movielens/25m/)


Sources:

https://www.datacamp.com/blog/clustering-in-machine-learning-5-essential-clustering-algorithms 

OpenAI. (2024, March 9). I want to make a data science/ai/ml project on a movie recommendation system. Give me some research questions for that? [Response to user query]. OpenAI ChatGPT.

https://towardsdatascience.com/unsupervised-learning-and-data-clustering-eeecb78b422a 

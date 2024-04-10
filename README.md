# MovieRecommendationSystem
Topic: Movie Recommendation System

Research Question: How can machine learning algorithms be optimized to provide personalized movie recommendations based on user preferences and behavior, considering factors such as genre, actors, directors, user ratings, and viewing history?

Summary: 
A movie recommendation system is a vital part of modern entertainment services such as Netflix, Hulu, and other streaming sites. Its importance lies in its ability to provide users with a seamless transition from one movie to the next, thus enhancing user engagement and satisfaction with the product in general. A good recommendation system must provide content that is personalized based on what users have liked in the past and relevant to the current movie scene.
The collected data will be used to train and test the model in order to answer the research question. The researchers will utilize features provided in the data based on user interactions like ratings, reviews, and watch history. Other data features such as movie metadata (i.e. runtime, director), can also be used to train the model if deemed appropriate.

Sources of Bias: 
Selection bias: The Kaggle dataset has majority of films primarily from Hollywood and do not include other international or independent film studios
Rating bias: The people may rate movies predetermined based on the genre, director of the film without having actually taken an objective view of the movie.

Machine Learning Algorithm:
	The machine learning algorithm the researchers decided to use is content-based filtering. This approach recommends movies based on the attributes or features of the movies themselves, such as genre, actors, directors, and plot keywords. It creates user profiles based on their historical preferences and matches them with movies sharing similar attributes.
Another idea could be to use matrix factorization techniques with SVD. This technique decomposes the user-item interaction matrix into lower-dimensional matrices to identify latent factors that capture user preferences and item characteristics. It has been widely used in recommendation systems due to its effectiveness in capturing complex patterns.
Finally, the researchers contemplated the k-means clustering algorithm for partitioning a dataset into k clusters. In the context of movie recommendation, features such as genre, actors, directors, and ratings can be used to represent movies in a high-dimensional space. K-means clustering can then be applied to group movies into clusters based on similarity.
Datasets:
The datasets that the researchers chose to use to train and test the machine learning model are largely from the Kaggle open-sourced dataset website. These datasets have features such as movie name, popularity, release date, genre, plot keywords, and more. 
9000+ Movies Dataset
IMDB Movies Dataset
25k IMDb Movie Dataset
Movie Recommender System Dataset | Kaggle

Sources:

https://www.datacamp.com/blog/clustering-in-machine-learning-5-essential-clustering-algorithms 

OpenAI. (2024, March 9). I want to make a data science/ai/ml project on a movie recommendation system. Give me some research questions for that? [Response to user query]. OpenAI ChatGPT.

https://towardsdatascience.com/unsupervised-learning-and-data-clustering-eeecb78b422a 

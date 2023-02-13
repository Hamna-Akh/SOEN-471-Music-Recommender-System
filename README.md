# SOEN 471 - Music Recommender System
## Project Summary 

The project aims to learn how to build recommender systems, which are widely used in today's world. The model design is a recommender system that will use two types of algorithms: a content-based algorithm and a collaborative-based algorithm. The dataset used in the project is “Spotify dataset” from Kaggle. It is 29.65MB and has 19 characteristics, which include song title, acousticness, danceability, energy, liveness, loudness, instrumentalness, tempo, duration, speechiness, and popularity.

The research questions for this project are "Can we accurately recommend songs to users based on their previous listening history using the attributes of the songs such as acousticness, liveness, and speechiness?" and “Can we accurately recommend songs to users based on their relative similarity to other users and their listening history?”. To address these questions, the project will use two classes of models: a vector space model and a matrix factorization. 

The content-based algorithm will make recommendations based on the attributes of songs that a user has previously listened to. This algorithm will calculate the similarity between a given song and all other songs in the dataset, based on their attributes. The most similar songs will be recommended to the user.

The collaborative-based algorithm, on the other hand, will make recommendations based on the listening history of other users who have similar preferences to the target user. The algorithm will use matrix factorization to identify latent features in the user-item interaction matrix, and then use these features to make recommendations.

In the project, both algorithms will be applied to the dataset and compared based on their accuracy and performance. The metrics used for comparison will include precision, recall, and F1 score.

The implementation will be done in Python using the pandas and tensorFlow libraries. The pandas library for python can be used to pre-process, clean, and manipulate the data in a dataset to build a recommender system by providing data structures and functions to handle and analyze the data. TensorFlow is an open-source library for machine learning that can be used to build a recommender system by training deep learning models on a dataset to make personalized recommendations.
## Authors
| Name  | Student ID |
| ----- | ---------- |
| Juan Salas  | 40044058  |
| Nabila Mehreen | 40130897  |
| Pola Farid | 40125357  |
| Hamna Akhter | 40078011  |

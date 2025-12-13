[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=21418979)
## Music Recommendation System Using Spotify Dataset (1921–2020)

Final project repo for INFO 523 - Summer 2025.

Site URL: https://github.com/INFO523-Fall25-101-201/final-project-srikanth



Develop a content-based music recommendation system using audio features and similarity modelling to suggest songs based on user listening history.
Dataset: Spotify Tracks Dataset (169,907 songs) 

The dataset used in this project is derived from Spotify’s music metadata and audio features. It includes thousands of tracks released over nearly a century, providing a rich historical and musical context. Each record represents a song and contains both descriptive and numerical attributes.


## Notebooks are where all work was completed
Music_Recom_System_Using_Spotify_Dataset.ipynb
In this project, we analyzed a Spotify music dataset (1921–2020) to build a basic music recommendation system. We performed data cleaning and preprocessing, explored key audio features such as tempo, energy, danceability, and popularity, and used these features to understand patterns in music listening behavior. Based on the similarity of songs and their characteristics, we developed a recommendation approach that suggests songs similar to a given track. This project demonstrates how data analysis and feature-based similarity techniques can be applied to create a practical music recommendation system using real-world data.



# Key features in the dataset include:

Danceability – measures how suitable a track is for dancing based on rhythm and tempo.

Energy – represents the intensity and activity level of a song.

Tempo – indicates the speed of the track in beats per minute.

Loudness – captures the overall sound level of a song.

Popularity – reflects how frequently the song is played on Spotify.

Release year – provides temporal context for musical trends.

These attributes allow songs to be quantitatively compared and analyzed for similarity.


# Models Implemented:
1️. Content-Based Recommender
KNN + Cosine similarity
Uses 9 audio features
Finds songs closest to user-selected track
Returns similarity score + popularity
2️.  Artist-Filtered Recommender
Prioritises tracks from the same artist
Highly useful for fans of specific musicians
3️. Cluster-Based Recommender
Recommends songs from the same K-Means cluster
Mimics “genre-based” suggestions
4️.  Weighted Feature Recommender
Assigns higher weights to energy, danceability, valence
Produces improved musical similarity
# Outcome:
A complete, multi-method music recommendation system based on user listening history, audio similarity, and clustering — fulfilling the project objective.



#### Disclosure:
Derived from the original data viz course by Mine Çetinkaya-Rundel @ Duke University

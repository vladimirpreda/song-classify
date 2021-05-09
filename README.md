## Title: Song Recommendation System exploration between content based and collaborative filtering. 

## Abstract
In this project we focus on exploring the two different approaches taken to creating recommender systems. More specifically, we will be creating a content-based recommender system and comparing its results with a collaborative based recommender. In order to execute this exploration, the use of two different datasets is necessary, as the content based recommender uses the lyrics of the songs as features, while the collaborative filtering approach uses other users behaviour as the features for deep learning. The second method is mroe widely used in large, popular recommender systems. However, it is important to explore content based filtering as we won't always have a plethora of all users information. 


## Research questions
  How does content-based filtering compare to collaborative filtering for a song recommender system? 

## Dataset
  Content-based recommender system 
    https://www.kaggle.com/imuhammad/audio-features-and-lyrics-of-spotify-songs
    This dataset contains rouhgly 15000 unique songs, in which is record has the name and lyrics of a song, including the author as some audio features that might come in handy. This dataset will allow us to use the lyrics to create Tfdf Vectors and compare similarities of songs and create user profiles. 
   Collaborative filtering recommender system
     There are two files that will be interesting for us.
      The first file gives us information about user ID, song ID and the listen count. We can read it from static.turi.com/datasets/millionsong/10000.txt.
      The second file will contain song ID, the title of that song, and artist name. We can read it fromstatic.turi.com/datasets/millionsong/song_data.csv 
      Although this approach is not analyzing the lyrics in itself of the song, there is still NLP involved in the creation of this model. 
  
## A tentative list of milestones for the project
  - Clean datasets
  - Create baseline model (content-based filtering using Tfidf and sparse matrix) 
  - Create Collaborative filtering model (using playlistscreated by spotify users) 
  - Compare the recommened songs and evaluate the models 

## Documentation

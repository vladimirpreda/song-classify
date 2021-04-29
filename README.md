## Title: Music Exploration

## Abstract
In this project we are aiming at creating our own song recommender system. There already exists a song recommendation system on Spotify, which has been proven to be succesful in increasing user satisfaction and time spent on application. We want to create a model that will take a list of songs as an input and output either a single or a list of songs that the algorithm recommends. Most importantly to note, we will be focusing on the lyrics of the song, as the intent of this project is to get more familiar with the NLP domain of machine learning. Moreover, with this recommender system, we would like to also be able to generate a new song created by the algorithm. This would be done with both the users list of songs and the recommendation songs that are given by the first model. This would prove to be an interesting idea to expand on if the model could actually create readable lyrics. 


## Research questions
  Can one use simple NLP tools to create a valuable song recommender system? 
  Is it easy to distinguish an AI generated lyrics to human written ones? 

## Dataset
List the dataset(s) you want to use, and some ideas on how do you expect to get, manage, process and enrich it/them. Show you've read the docs and are familiar with some examples, and you've a clear idea on what to expect. Discuss data size and format if relevant.

Dataset:
  We will need two different datasets. The first dataset will be a collection of songs with their lyrics (the only feature we will be looking at). The second dataset will have both a list of songs users have listened to previously and the songs spotify has recommended them. The first dataset will be used to train and create a model to recommend songs best on their lyrics. The second dataset will be used to evaluate how accurate our training model is working compared to the spotify recommender system. 
  
Challenges with the dataset:
  The challenges with these two datasets are the following. Firstly, we need to figure out the best approach to training the recommender model. Are we using semantic similarity as a sign of recommending another song? Or is there a different method that oculd yield better results? Secondly, what is the best way to evaluate if what we are recommending is actually something users will like? This is where the second dataset comes into play, however we are still wondering what the best approach is.
  
  
  Maybe we should have a third dataset in order to help out with the generating of a new poem. We are not sure. 
  
## A tentative list of milestones for the project

  - Clean and organize datasets
  - Preprocess the datasets (We will most likely use pre_trained Word Embeddings)
  - Create a nearest KNN similarity model for recomendation 
  - Have a model that generates some output of lyrisc based on the previous songs

## Documentation
none yet 

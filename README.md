## Title: Music Exploration

## Abstract
In this project we aim to explore music searching. How often have you wondered what song snippet belongs to what song or which artist, perhaps even what genre? This is our attempt at a shazam for natural language. We begin by exploring the relationship of lyrics and genres and the ideal x-data format (lyric or lyric-snippet) to do so. If successful, we aim to create models which accurately predict a lyrics artist. Finally, we aim to investigate whether there is a change of language in music over time by exploring relations between the ideal x-data format and year. 

## Research questions
  - How well can a model predict the genre of a song, based only on the lyrics, using supervised learning?
  - Which setup will perform better: training on the whole lyrics of the songs, or only on snippets of the songs (e.g. the hook)?
    Our *intuition* is that the models trained on the snippets should outperform models trained on the entire songs, because the model gets a chance to learn more *characteristics* of a song/genre i.e. common phrases, keywords etc., which might be overlooked by the alternative approach.
  - If genre detection is highly accurate, can we train models to also predict the Author or release date of the song?

## Dataset
List the dataset(s) you want to use, and some ideas on how do you expect to get, manage, process and enrich it/them. Show you've read the docs and are familiar with some examples, and you've a clear idea on what to expect. Discuss data size and format if relevant.

Dataset:
  https://www.kaggle.com/mateibejan/multilingual-lyrics-for-genre-classification?select=test.csv
  Features
    Song(str), Song Year(int), Artist(str), Genre(str), Lyrics(str) 
   Lyrics is the whole song into one datapoint. 
   There are about 250000 datapoints in the dataset, from those about 90% are usable (English lyrics). The format of the dataset is handy, as it is alrady organized as a CSV file type.
Ideas:
  Use the lyrics feature of each datapoint to predict the genre of the song. Also, this dataset can be used to create another dataset of sentences of the lyrics to both increase the size of the dataset while reducing each datapoint size. Basic preprocessing will need to be done for both datasets (the one in the link and the one we make from the links dataset), such as tokenizing, POS tagging, stemming, lemmatizing and so forth. 
  
 Challenges with the dataset:
  There aren't many challenges as the data is pretty clean already. Having to create a new dataset from the already existing one will prove to be the biggest challenge, but should be simple with simple nltk functions or python functions. 
  



## A tentative list of milestones for the project

  - Clean and pre-process the dataset by April 19th (Marc)
  - Base models running by April 29th (Ilai)
  - Create model performance reports using a standardized class by April 29th (Preda)
  - Train the rest of the models (Marc, Ilai, Preda)
  - Prepare the final report (Marc, Ilai, Preda)

## Documentation
This can be added as the project unfolds. You should describe, in particular, what your repo contains and how to reproduce your results.

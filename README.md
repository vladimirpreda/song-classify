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

Multilingual Lyrics for genre classification.

We need to remove non-english lyrics and create a general pipeline for lyrics:
https://www.kaggle.com/mateibejan/multilingual-lyrics-for-genre-classification?select=test.csv

## A tentative list of milestones for the project

  - Clean and pre-process the dataset by April 19th (Marc)
  - Base models running by April 29th (Ilai)
  - Create model performance reports using a standardized class by April 29th (Preda)
  - Train the rest of the models (Marc, Ilai, Preda)
  - Prepare the final report (Marc, Ilai, Preda)

## Documentation
This can be added as the project unfolds. You should describe, in particular, what your repo contains and how to reproduce your results.

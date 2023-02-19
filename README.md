# How do you feel, my dear
Recently, emotion detection in text has received attention in the literature on
sentiment analysis. Detecting emotions is important for studying human communication in different domains, including fictional scripts for TV series and
movies. The project aims at studying fictional scripts of several movies and TV
series under the emotional profile of the main characters. We constructed an
LSTM Recurrent Neural Network for the prediction of the VAD values and used
the results to show the emotional profile of a character, how it changes over time
and how is it affected by the other characters in the movie.

# Important
The main code is in 'Project.ipynb' but before running it is necessary to:
1. Download from this link https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?resourcekey=0-wjGZdNAUop6WykTtMip30g the pre-trained vectors for words by Google Code, unzip the file and upload it into the folder 'dati'.
2. Download from this link https://www.kaggle.com/datasets/rajathmc/cornell-moviedialog-corpus the Cornell Movie Dialogs Corpus (only the file 'movie_characters_metadata.txt', 'movie_conversations.txt', 'movie_lines.txt' and 'movie_titles_metadata.txt' are needed) and upload them in the path 'dati/CornellMDCorpus'.
3. Run the script 'EMOBANK_MongoDB.ipynb' to upload in MongoDB the Emobank corpus.
4. Run the script 'CornellMDCorpus_MongoDB' to upload in MongoDB the Cornell Movie Dialogs Corpus.

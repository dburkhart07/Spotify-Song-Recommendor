# Spotify-Song-Recommendor
Note: This project was done on Google Colab.
This app uses a dataset of some of the most popular songs from each year over the last 20 or so years. The dataset gives each song various scores, such as its danceability, genre, valence, etc. 
The app takes in a song from the dataset of the user's choice, as well as a catagory for the recommendation to be based off of, and recommends a song accordingly.
The recommendation takes place using cosine similarity and vectors, finding the smallest differences in angles between the vectors of the user's song based on the specified factor, as well as every other song in the database.
Some of the catagories can be funky, such as dB (decibals) not working, artist running out of songs by the same artist, and year. Anyone able to fix these please let me know. I think it could also be amazing if the app was able to take into account multiple factors and recommend songs off of that, I had trouble implementing it though.

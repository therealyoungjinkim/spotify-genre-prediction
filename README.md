# spotify-genre-prediction
predicting genres of spotify songs using features from spotify

this project uses a naive assumption that songs could only exist in 1 genre, or at least has a clear influence from 1 major genre.

# pipeline

- get spotify API credentials (https://developer.spotify.com/documentation/web-api/)

- gather songs (334 as of now) and separate them into spotify playlists- a new playlist for each genre that each song is to be classified

- scrape the features used by spotify for the selected songs

- EDA

- models

# conclusions(?)

- splitting genres into smaller sub-genres reduces false positives but also increases false negatives

- probably a better idea to consider 'distance' between genres as a metric of accuracy

- contemporary k-pop probably isn't 'real.' its pop that happens to be sung in korean


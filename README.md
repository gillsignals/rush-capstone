# rush-capstone

This repository contains my analysis of Rush lyrics for the Data Science Specialization capstone project from HarvardX via edX. 

### Scripts

* **`rush-lyrics-import.Rmd`** - imports Rush lyrics from Genius using `geniusR`, converts to tokens, cleans lyrics data, saves lyric tokens as `lyricTokens.Rdata`

* **`rush-spotifyr-import.Rmd`** - imports Rush discography audio features, saves audio features as `audioFeatures.Rdata`

### Data 

* **`lyricTokens.Rdata`** - individual tokens (words) from Rush lyrics corpus, with album and song for each word; output of `rush-lyrics-import.Rmd`

* **`audioFeatures.Rdata`** - audio features for all Rush songs, including track and album metadata; selected features include energy, valence, tempo, danceability, track popularity
## Song Recommender
Can't find any new interesting music? We can help!

## Motivation
In a team, we created a song recommender, using Spotify's library and features, Which will eventually contain an App Interface. 

We wanted to use clustering to recommend different genres of music recommendations which contained similar features to the input song.


**The program:**

- Takes the input song and artist 

- Checks whether the song is in the top200 list. If it is, it will recommend another song from the 200 list

- If it is not, it checks a pre-made dataframe for songs with similar attributes (which are unpacked and scored into clusters)

- It then outputs the recommended song and artist


## Code style
This notebook uses:

- Python
- API Wrapper: Spotipy


## Credits

Data was sourced from Spotify at: 

developer.spotify.com


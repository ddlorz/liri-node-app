How to use liri.js:

Main command line: node liri.js

Command to get tweets: my-tweets
Command to spotify: spotify-this-song <song name>
Command to movie: movie-this <movie name>

Tweets command pulls the last 20 tweets of the predefined account name (BarackObama);
Example terminal command to tweets: node liri.js my-tweets;

Spotify command pulls the song data of the input song;
If user doesn't enter a song name, the song name is assigned to 'the sign';
Example terminal command to spotify: node liri.js spotify-this-song Dear Mama

Movie command pulls the movie data of the input movie;
If user doesn't enter a movie name, the movie name is assigned to 'my_nobody';
Example terminal command to movie: node liri.js movie-this Minority Report

All outputs are logged to log.txt.


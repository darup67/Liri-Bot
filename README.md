# Liri-Bot

LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

# LIRI-BOT (a Language Interpretation and Recognition Interface)
LIRI is a command line node app that takes in parameters and gives you back data based off the following parameters:

concert-this
Spotify-this-song
movie-this
do-what-it-says

# Getting Started:
Download the "screenshots" folder to see results of each command. This will allow you to better see how LIRI works with each given command.

concert-this:
Screen shot







This will search the Bands in Town Artist Events API for an artist and render the following information about each event to the terminal:

Name of the venue
Venue location
Date of the Event (use moment to format this as "MM/DD/YYYY")

Spotify-this-song:

![alt text](https://github.com/darup67/Liri-Bot/blob/master/screenshots/Spotify-this-song.png)




This will show the following information about the song in your terminal/bash window

Artist(s)
The song's name
A preview link of the song from Spotify
The album that the song is from

movie-this:

![alt text](https://github.com/darup67/Liri-Bot/blob/master/screenshots/movie-this.png)









This will output the following information to your terminal/bash window:

Title of the movie.
Year the movie came out.
IMDB Rating of the movie.
Rotten Tomatoes Rating of the movie.
Country where the movie was produced.
Language of the movie.
Plot of the movie.
Actors in the movie.




do-what-it-says:

LIRI will use the text from “random.txt” and call on of LIRI’s commands. It should run Spotify-this-song for “I want it That way”.

![alt text](https://github.com/darup67/Liri-Bot/blob/master/screenshots/do-what-it-says.png)
![alt text](https://github.com/darup67/Liri-Bot/blob/master/screenshots/Mr.%20Nobody%20.png)








Technologies used:
- OMDB API
- Spotify API
- Bands In Town API
- Node.js
- NPM Packages
- Javascript

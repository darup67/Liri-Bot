# Liri-Bot

LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

# Usage / Commands
node liri.js ?

Shows the list of available commands
node liri.js concert-this <artist/band name here>

Searched the Bands in Town Artist Events API ("https://rest.bandsintown.com/artists/" + artist + "/events?app_id=codingbootcamp") for an artist and renders the following information about each event to the terminal:

Name of the venue

Venue location

Date of the Event (use moment to format this as "MM/DD/YYYY")

node liri.js spotify-this-song '<song name here>'

Shows the following information about the song in your terminal/bash window

Artist(s)

The song's name

A preview link of the song from Spotify

The album that the song is from

If no song is provided then it defaults to "The Sign" by Ace of Base.

Utilizes the node-spotify-api package in order to retrieve song information from the Spotify API.

node liri.js movie-this '<movie name here>'

Outputs the following information to your terminal/bash window:

  * Title of the movie.
  * Year the movie came out.
  * IMDB Rating of the movie.
  * Rotten Tomatoes Rating of the movie.
  * Country where the movie was produced.
  * Language of the movie.
  * Plot of the movie.
  * Actors in the movie.
If the user doesn't type a movie in, it outputs data for the movie 'Mr. Nobody.'

I use the axios package to retrieve data from the OMDB API. The OMDB API requires an API key. You may use trilogy.

node liri.js do-what-it-says

Using the fs Node package, LIRI takes the text inside of random.txt and then uses it to call one of LIRI's commands.

It runs spotify-this-song for "I Want it That Way," since that is the text in random.txt.

Edit the text in random.txt to test out this feature for movie-this and concert-this.


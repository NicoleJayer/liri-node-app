# liri-node-app

This project was designed to be a play on the iOS application "Siri." Using user input via text rather than voice, this app allows for access to specific programs hardcoded into its design.

The application coined "Liri," accesses the OMDB api, Twitter, and Spotify. The application was designed to pull the inputed users last 20 tweets (if there are that many), search for information on various songs and artists given a set of keywords, and lastly to find points of information provided from OMDB given a movie title input.

The commands necessary to use the application are as follows:

---  "my-tweets"
---  "spotify-this-song" + 'any song title'
--- "movie-this" + 'any movie title'
--- "do-what-it-says" (creates a random.txt file with a preset Spotify song in it)

In order for this application to work the user must have their own Spotify, OMDB, and Twitter API keys. A '.env' file was created and then with the use of '.gitignore' hidden so that students wouldn't be openly sharing their keys in this assignment.

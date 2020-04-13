# liri-node-app

ABOUT:
The Liri Node App is a _Language_ Interpretation and Recognition Interface, that allows users to search for information on concerts, songs, and movies. It pulls out the main information that users are looking for from the Spotify, Bands In Town, and OMDB, omits any excess information, and gives it to them in one condensed location.

APP OVERVIEW:
The app is organized into 3 main sections:
    1. The top holding constants and variables.
    2. A switch statement that matches each expression to the corresponding case and executes the correct function.
    3. The 4 functions for concert-this, spotify-this-song, movie-this, and do-what-it-says, with parameters, only pulling the main points/information from each API and displaying it via console.log().

HOW TO USE:
1. Open the Terminal or Command Prompt on your computer, and go to the "liri-node-app" file folder.

2. Once in the correct folder, type "node liri.js " and type in one of the following commands:
    1. concert-this
            (to search for the artist's upcoming concert with the venue name and location)
    2. spotify-this-song
            (to search for information about a song)
    3. movie-this
            (to search for information on a movie)
    4. do-what-it-says
            (try this one out to see the preset text that was set in the random.txt file)

3. After typing one of the above in, type in the name of the artist (for concert-this), song title (for spotify-this-song), or movie title (for movie-this), leaving a space between the command and name of what you are looking for.

NOTE: When searching for a movie that has two or more words in the title, type %20 in replace of the space you would put inbetween the words. (This function will be removed and fixed at a later date)

4. Finally, hit enter, and your results will pop up within a second.

SCREENSHOTS:


DEPLOYED LINK:


TECHNOLOGIES USED:
* dotenv
    (If you would like to try this app on your computer, you must supply your own .env file for it to work)
* Moment
* package.json
* Axios
* Node-Spotify API
* OMDB API
* Bands In Town API

DEVELOPER:
Christine Dang, full app developer
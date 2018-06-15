# liri-node-app
LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data. 


### How to install:

* Install Node.js and npm in your laptop.
* In your terminal, run "git clone "git@github.com:Staceyrong/liri-node-app.git" to download application.
* Or Download from https://github.com/Staceyrong/liri-node-app.
* After download, in your terminal, run "npm install" in the LIRI_Bot folder that has package.json.
* Create a file named .env, add the following to it, replacing the values with your API keys (no quotes) once you have them:

```
# Spotify API keys

SPOTIFY_ID=your-spotify-id
SPOTIFY_SECRET=your-spotify-secret

# Twitter API keys

TWITTER_CONSUMER_KEY=your-twitter-consumer-key
TWITTER_CONSUMER_SECRET=your-twitter-consumer-secret
TWITTER_ACCESS_TOKEN_KEY=your-access-token-key
TWITTER_ACCESS_TOKEN_SECRET=your-twitter-access-token-secret
```

### How to use LIRI
* **node liri.js my-tweets**
    * This will show your last 20 tweets and when they were created at in your terminal/bash window.

```
Users\kiki1\Documents\liri node\liri-node-app> node liri.js my-tweets

my-tweets

Hi Hi
```

* **node liri.js spotify-this-song \'\<song name here\>\'**
    * If no song is provided then your program will default to "The Sign" by Ace of Base.
    * This will show the information about the song in your terminal/bash window
```
Users\kiki1\Documents\liri node\liri-node-app>node liri.js spotify-this-song
this is loaded
Artist: Arctic Monkeys
Song: Fluorescent Adolescent
Preview URL: https://p.scdn.co/mp3-preview/15d133bcf82fa91cfb81c8b53a2810add8529da2?cid=e57204b5950e4b76aa9c751cca438cf3
Album: Favourite Worst Nightmare (Standard Version)
-----------------------
Artist: Arctic Monkeys
Song: Fluorescent Adolescent
Preview URL: https://p.scdn.co/mp3-preview/cb8560b45aa0d4028e94a2648686c460641074d0?cid=e57204b5950e4b76aa9c751cca438cf3
Album: Fluorescent Adolescent
-----------------------
Artist: Arctic Monkeys
Song: The Bakery
Preview URL: https://p.scdn.co/mp3-preview/13fad08aa75867f90d459ccebbdae58df8fcc31e?cid=e57204b5950e4b76aa9c751cca438cf3
Album: Fluorescent Adolescent
-----------------------
Artist: Arctic Monkeys
Song: Too Much To Ask
Preview URL: https://p.scdn.co/mp3-preview/4e6cad4d8d93cf4c63c8bef1351cf1f1d6d8b662?cid=e57204b5950e4b76aa9c751cca438cf3
Album: Fluorescent Adolescent
-----------------------
```
* **node liri.js movie-this \'\<movie name here\>\'**
    * If the user doesn't type a movie in, the program will output data for the movie 'Mr. Nobody.'
    * This will output the following information to your terminal/bash window:
```
Users\kiki1\Documents\liri node\liri-node-app>node liri.js movie-this Superman
this is loaded
Title: Superman
Release Year: 1978
IMdB Rating: 7.3
Country: USA, UK, Panama, Switzerland, Canada
Language: English
Plot: An alien orphan is sent from his dying planet to Earth, where he grows up to become his adoptive home's first and greatest superhero.
Actors: Marlon Brando, Gene Hackman, Christopher Reeve, Ned Beatty
Rotten Tomatoes Rating: N/A
Rotten Tomatoes URL: http://www.rottentomatoes.com/m/superman_the_movie/
```


* **node liri.js do-what-it-says**
    * LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands.

```
C:\Users\kiki1\Documents\liri node\liri-node-app>node liri.js do-what-it-says
this is loaded
spotify-this-song
"I Want it That Way"
Artist: Backstreet Boys
Song: I Want It That Way
Preview URL: https://p.scdn.co/mp3-preview/e72a05dc3f69c891e3390c3ceaa77fad02f6b5f6?cid=e57204b5950e4b76aa9c751cca438cf3
Album: The Hits--Chapter One
-----------------------
Artist: Backstreet Boys
Song: I Want It That Way
Preview URL: https://p.scdn.co/mp3-preview/b8c2410a5acb68b462be6ac85f1312430e2b149c?cid=e57204b5950e4b76aa9c751cca438cf3
Album: Millennium
-----------------------

```


### Built With  

* Javascript 
* twitter, node-spotify-api, request, DotEnv and colors packages


### Contributing

Please contact  at Jiahong Rong rongjiahong@gmail.com for details on our code of conduct, and the process for submitting pull requests to us.

### Authors

* **Jiahong Rong** 
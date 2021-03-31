Just my own version of Nitter with a purple theme, using the full Redis server and built using nim 1.4.2 instead of 1.2.0 with archiving abilities and other tools.

For Heroku check the buildpack https://github.com/Varulv1997/nitter_buildpack

You can use this button to deploy it on Heroku: 
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Varulv1997/purplenitter)

$ nimble build -d:release
$ nimble scss

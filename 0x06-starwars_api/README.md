Star Wars API
This project contains interview coding challenges.

More Info
Install Node 10
$ curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
$ sudo apt-get install -y nodejs
Install semi-standard
Documentation

$ sudo npm install semistandard --global
Install request module and use it
Documentation

$ sudo npm install request --global
$ export NODE_PATH=/usr/lib/node_modules

Tasks To Complete
 0. Star Wars Characters
0-starwars_characters.js contains a script that prints all characters of a Star Wars movie with the following requirements:
The first positional argument passed is the Movie ID - example: 3 = “Return of the Jedi”.
Display one character name per line in the same order as the “characters” list in the /films/ endpoint.
You must use the Star wars API.
You must use the request module.
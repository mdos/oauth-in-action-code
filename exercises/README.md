# README notes for running/developing exercises

* Grab `nodemon` via `$ npm i -g nodemon`
* Launch a GNU screen session with 3 windows (one each for AS, RS, and client)
* launch each respective server via `$ nodemon client.js`, `$ nodemon authServer.js`,
  and `$ nodemon resourceServer.js` (or whatever they're called). If you don't
think restart after any code change is necessary, just launch via node.
* Edit the code in VSCode or something more comfortable. Each save will respawn
  the servers started via nodemon.
* Enjoy

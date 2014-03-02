#Fast Times with Mongo
Fast Times with Mongo is a single page application (SPA) built with MongoDB, Node.JS, Breeze and AngularJS

## Prerequisites
* Node.js
* MongoDB

## Install and use

### Extract the database

Extract the application's MongoDB database in *Fast-times-mongo-database.zip* to your MongoDB data directory.

OR

Create an empty database.

>The default location per MongoDB installation instructions is */data/db*. Your location may be different.

You only have to install this database once.

### Install dependent node modules

1. Open a terminal

2. Navigate to the *Fast-Times* directory.

3. Use npm to install the following three modules:
<pre style="margin-left: 2em">
npm install mongodb
npm install express
npm install breeze-mongodb
</pre>

Confirm that all of them ran without error (warnings are ok). You can close this window when you're done.

You only install these modules once.

### Start the servers
*Every time you run the application* you must first launch **two** servers: the MongoDB server and the application's node/express server.

1. Open a new command prompt window.

2.	Start MongoDB by typing **sudo mongod** in a terminal window. (Make sure the directory */data/db/* exists or create it first)

	>Do not close this window. Closing the window will end the MongoDB process.

3.	Open a new command prompt window.

4.	Navigate to the *Fast-Times* directory.

5.	Type **node server** to start the Node.js/Express server.
6.	
	>Do not close this window. Closing the window will end the Express process.

### Run Fast-Times

Open **localhost:3000** in a web browser to run the application.

## Release 0.1
* Initial release.
* Demonstrates fundamental characteristics of a MongoDB app.
* Demonstrates more sophisticated user interaction paradigms than other Breeze samples. (It actually looks like a SPA.)
* Makes better use of Angular than other Breeze + Angular samples.

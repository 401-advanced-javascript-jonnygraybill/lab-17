# LAB - 17

### Authors: Jonny and Adriana
* Worked with, and received help from Brad and Brandyn to help debug code issues.

# Event Driven Messaging Server

### Links and Resources
* [submission PR]() 

* [travis]([![Build Status](https://www.travis-ci.com/401-advanced-javascript-jonnygraybill/lab-11.svg?branch=auth)](https://www.travis-ci.com/401-advanced-javascript-jonnygraybill/lab-11))


### Modules
#### app.js
#### server.js
#### logger.js

### Exported Values and Methods

* fs.read(file) -> string
  * Changes text in file to uppercase

* fs.write(write) -> string
  * Saves file after changes are made

### Setup

* PORT runs on 3001

#### Running the app
* `nodemon` should start server.js
* `node logger.js` should start a server that listens for the event happening in app.js
* `node app.js files/test.txt` should allow the app file to grab the test.txt file as a parameter
  
#### Tests
* npm testing will do the following:
  * Inside the terminal, run the "Running the app" command
  * Expect the result of running the command to be truthy if successful
  * test.txt file content will be saved in uppercase format

### UML
![UML: Lab 17](../assets/lab-17-uml.jpg)

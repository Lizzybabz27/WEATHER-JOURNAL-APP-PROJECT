# WEATHER-JOURNAL-APP-PROJECT
This is a weather Journal App

# PROJECT TITTLE
## UDACITY WEATHER JOURNAL APP PROJECT


## Overview
This Weather Journal App project is an asynchronous web app that uses Web API and user data to dynamically update the UI.

# List of files used in this project are:
* `Html`
* `css`
* `javascript`
* `node.js`
* `app.js`
* `server.js`


## Table of Contents
* Project Title
* Overview
* List of files used in this project
* Landing Page Project 
* Table of contents
* Instructions I Followed
* Releases
* Packages


* [Instructions](#instructions)

## Instructions I Followed

1- SERVER.JS
  * I started by setting up my roject environment which was to download and install Node.js.
  * Then, I installed the Packages Express, Body-Parser and Cors. 
  * Then, I required the node packages and required body-parser to be used as the middle-ware.
  * Next, I added a GET Route to respond with the Javascript when a GET request is made.
  * I also added a POST Route that adds the temp, date and feelings data to the projectData, which is the end point for all datas.
  * Lastly, I concluded by passing the .listen method which listens to my port.

2- APP.JS
  * I started by creating an account on the openweaathermap.org website, where I was able to get my api key.
  * Then, I created my variables which fetched my api key.
  * The other variables to hold my datas which were to be accessed later, were also created.
  * Next, I added an event listener with the I.D gnerate, which was used to 
    listen for a click in the generate button.
  * This then led to me creating the chain of .then promises, which links all my datas together.
  * The first async data (firstPromiseData) was created to make a fetch call to the openweathermap api.
  * The second async data (secondPromiseData) was created inorder to specifically collect or filter the 
    datas we need from the web api.
  * The third async data (thirdPromiseData) was created inorder to interact with the get route created in the server, by 
    transferring the fetched data to it.
  * The fourth async data (fourthPromiseData) acted as a means of retrieving data from the server side.
  * The last async data (clientSideUpdate) was created to update the UI by dynamically collecting all the datas
    accumulated, and then showcasing or posting them on the client side, which is on the app.
  * I accessed them in my Dom Elements using .querySelector.
  * Lastly, I made my app interactive on different devices and styled the background image using 
    unsplash random images.

3. INDEX.HTML
  * I added a few more id's and classes, which i used in my javascript and css files.

4. STYLE.CSS
  * Here, I styled my app and customized it to my taste and satisfaction.


## Releases
No releases published
## Packages
No packages published

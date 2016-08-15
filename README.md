# _Weather Humidity_

#### _Practice using Bower and npm to manage dependencies, work with third-party APIs & AJAX to retrieve and display data in applications and continue using gulp tasks, including a development server with live reloading., 05/26/2016_

#### By _**LaTaevia**_

## Description

_Web page functioning as a weather app with the Open Weather Map API. This app has been refactored from the [Node Ping Pong with Server] (https://github.com/LATAEVIA/Node-Ping-Pong-with-Server) project to isolate the functionality from humidity lookup and to seperate front end JavaScript for back end Javascript. _

## Prerequisites

_You will need the following things properly installed on your computer._

* [Git](http://git-scm.com/)
* [Node.js](http://nodejs.org/) (with NPM)
* [Bower](http://bower.io/)	

_You will need to retrieve the following API keys._
* [Open Weather Map API](http://openweathermap.org/)	

## Installation

* `git clone https://github.com/LATAEVIA/Weather-Humidity.git`
* change into the new directory
* create a `.env` file in the folder's root directory
* Add the Open Weather Map API key in the .env file as follows: `exports.apiKey = "a1b2c3d3e4f5g6h7i8j9k0a1b2c3d3e4";` replacing the alpha-numeric key in quotes with the key generated by the Open Weather Map API.
* `npm install`
* `bower install`
* `gulp build`

## Running / Development

_Implement development server with live reloading:_
* `gulp serve`

## Technologies Used

* _HTML_
* _CSS_
* _Bootstrap_
* _JavaScript_
* _Node.js_
* _Node Package Manager_
* _Bower_

### License

*This software is licensed under the MIT license*

Copyright (c) 2016 **_LaTaevia_**
# Note-Taker
[Live Application Click Here](https://secure-springs-07761.herokuapp.com/)

## Description

This app displays skills learned at The Coding Bootcamp at UT Austin during week 12. The specific skills on display consist of back end server creation and data transmission. The exercise focused heavily on learning how to write and organize api routes to execute the needed funtions. 

## Proided Info
Important to note, the front end of this application was provided for this project. The files included can be found in the /public folder.

## Tech
This app uses the following tech to function:
* Express.js to set up the server
* fs node package to read/write/delete files
* nanoid node package to supply unique ID values for notes
* Heroku to host the server
* JavaScript to write the back end functional code
* HTML/CSS to provide the front end
  
## Installation

This app requires no special installation of programs to run. It will run on any web browser.

## Usage

The application allows the user to input a Note Title and Note Text. Once the input is recognized by the web page a save icon appears at the top right. Clicking on this icon executes a POST api action. This is sent to a Heroku server for keeping. The app uses GET api methods to display and recall past notes on the left side when clicked. The app also features a DELETE api function that is executed when clicking on the red trash can.
  
##Screenshot
![notetaker](https://user-images.githubusercontent.com/92648393/151733989-6211b329-0807-4919-8627-597f0a69cab7.PNG)


#Friend Finder
Project Description:

This is an app to search for a compatile friend based on answers to survey questions.

How does it work? 
The user is presented with a home screen where they can access the api for the site and the aoo's github repository.  From here, they proceed to a survey where they enter their name, a link to a picture file and answer 10 survey questions presented using selects with 1 - 5 as the choices.  Once they submit their answers which are stored in an array, they are compared to the answer arrays of existing users to find the closest match.  A new array is created for the comparison between the current user and each user stored in the api which stores the differences between each answer.  These arrays are then summed.  the existing user with the lowest sum is the match. Once the match is determined, a modal with the name and picture of the match is launched.

Who will use this repo or project?

This project is a homework assignment for Coding Bootcamp for full-stack developers at Georgia Tech. 

What is the goal of this project?

The goal of this project is to continue gaining experience with JavaScript, jQuery, HTML, and CSS skills as well as u Express and Node in particular with setting uop a server ands setting up routes to GET and POST data. 
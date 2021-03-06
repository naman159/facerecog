![Screenshot](10.png)  
![Screenshot](12.png)  

FaceRecog is a web application that detects faces in pictures using the Clarifai API.  
The web client is built using JavaScript with React on the front-end and Node.js & Express.js on the back-end (API). PostgreSQL is used for the database. 
The structure of the web application is such that the front-end fetches the required data from the back-end API which manages the pipeline for user registering, login and also makes the API calls to Clarifai.

This is a nice project to work on when first learning website development with MERN stack (this project uses PostgreSQL instead of MongoDB).

Note: 
The libraries and dependencies used in the project are not the latest. At the time it was built, some of the newer dependencies were causing errors thus they were deprecated.

Inspiration:
“The Complete Web Developer in 2020: Zero to Mastery.” Udemy, Andrei Neagoie, 27 Feb. 2020, www.udemy.com/course/the-complete-web-developer-zero-to-mastery/.

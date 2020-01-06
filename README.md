# FLIXTER WEB APPLICATION

This is a web application that uses Postgres. The application is a two-sided, video-streaming marketplace platform that features credit card payment capabilities, user role management, complex user interfaces(advanced UI and UX), and advanced database relationships.

![Flixter main page](/app/assets/images/flixtermainpagescreenshot.png)


## Tools used during the Application Development include

Ruby on Rails. Ruby version 2.5.3 and rails version 5.2.3

HTML and CSS for styling pages

Git 

GitHub

Heroku

Amazon Web Services-Amazon S3

ImageMagick

payment processor (Stripe) 


## Creating and Running the application

Set up the initial project structure by creating a new rails web application that uses Postgresql and creating an initial, empty database by running rake db:create to have a place to store information. Start the server.

Set up the web development pipeline: git, github and heroku. This will save and run the application code locally and in production. 

Add user authentication by setting up the devise gem and adding login links to the navbar. This grants users ability to sign up, sign in and sign out of the application. 

Set up models and database, build the infrastructure which includes controller, routes table and view files. Set up the pipeline for uploading image or video content to our web application using Amazon S3 as the Uploader that stores videos and images. Use the ImageMagick program to adjust the image's resolution to crop it to a smaller size if the user uploads a very large image. These features will allow logged in instructors to create courses, sections, and lessons or students to enroll and access courses, sections, and lessons.

Integrate the application with Stripe, a secure payment processor that facilitate credit card transactions made by students during enrollment.  


## Try it yourself, link provided below

[FLIXTER](https://flixter-dessy-owiti.herokuapp.com/)




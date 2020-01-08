# FLIXTER WEB APPLICATION

This is a web application that can be used for teaching or learning purposes. Signed up instructors can create courses, sections, and lessons that include text, videos and images. Students have the ability to enroll and pay to access the content of the courses. The application is a two-sided, video-streaming marketplace platform that features credit card payment capabilities, user role management, complex user interfaces(advanced UI and UX), and advanced database relationships. 

![Flixter main page](/app/assets/images/flixtermainpagescreenshot.png)


## Tools used during the Application Development include

Ruby on Rails. Ruby version 2.5.3 and rails version 5.2.3

jQuery

HTML and CSS

Git 

GitHub

Heroku

Amazon Web Services-Amazon S3

ImageMagick

payment processor (Stripe) 


## Creating and Running the application

Set up the initial project structure by creating a new rails web application that uses Postgresql and create an initial, empty database by running rake db:create to have a place to store information. Start the server.Construct the web development pipeline: git, github and heroku. This will save and run the application code locally and in production. 

Add user authentication by setting up the devise gem and adding login links to the navbar. This grants users ability to sign up, sign in and sign out of the application. 

Set up models and database, build the infrastructure which includes controllers, routes tables and view files. Set up the pipeline for uploading image or video content to the web application using Amazon S3 as the Uploader that stores videos and images. Use the ImageMagick program to adjust the image's resolution to crop it to a smaller size if the user uploads a very large image. These features will allow logged in instructors to create courses, sections, and lessons or students to enroll and access content of the courses.

Integrate the application with Stripe, a secure payment processor that facilitates credit card transactions made by students during enrollment.  

Apply jQuery, JavaScript code, to enable the repositioning of sections and lessons by the user(instructor), the user would be able to reposition the lessons by dragging and dropping them. 

Style the pages using HTML and CSS.

When finished save the code by pushing it to GitHub and showcase the application in production by pushing it Heroku.


## View the application in the link provided below

[FLIXTER](https://flixter-dessy-owiti.herokuapp.com/)




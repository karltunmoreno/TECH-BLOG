# technology-blog

![Ss](https://karltunmoreno.github.io/My-Portfolio/assets/images/TechBlog.jpg)
_________________________________________________________________________________________________________________________________________________________________

## Usauge Story

AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions

___________________________________________________________________________________________________________________________________________________________________
## Description

GIVEN a CMS-style blog site
WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
WHEN I click on the homepage option
THEN I am taken to the homepage
WHEN I click on any other links in the navigation
THEN I am prompted to either sign up or sign in
WHEN I choose to sign up
THEN I am prompted to create a username and password
WHEN I click on the sign-up button
THEN my user credentials are saved and I am logged into the site
WHEN I revisit the site at a later time and choose to sign in
THEN I am prompted to enter my username and password
WHEN I am signed in to the site
THEN I see navigation links for the homepage, the dashboard, and the option to log out
WHEN I click on the homepage option in the navigation
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
WHEN I click on an existing blog post
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
WHEN I click on the dashboard option in the navigation
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
WHEN I click on the button to add a new blog post
THEN I am prompted to enter both a title and contents for my blog post
WHEN I click on the button to create a new blog post
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
WHEN I click on one of my existing posts in the dashboard
THEN I am able to delete or update my post and taken back to an updated dashboard
WHEN I click on the logout option in the navigation
THEN I am signed out of the site
WHEN I am idle on the site for more than a set time
THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments

___________________________________________________________________________________________________________________________________________________________________

## Utilizes Node.js and Express.js to create and manage a server for a blog post sharing webiste.

### NPM Packages:

- **express**: High performance framework for server-side applications
- **express-session** and **express-session-sequelize**: For session creation and to connect/sync the sequelize database to the session.
- **mysql2 and sequelize**: To connect the application to a MySQL database and to query that database within JavaScript rather than the MySQL command-line shell.
- **dotenv**: For setting environment variables.
- **bcrypt**: For password hashing.
- **express-handlebars**: For serving dynamic HTML based on database queries.


LINK TO APP SITE ON HEROKU
https://arcane-beach-63003.herokuapp.com/home
___________________________________________________________________________________________________________________________________________________________________

TECH USED:

![JavaScript](https://img.shields.io/badge/-JavaScript-%23F7DF1C?style=flat-square&logo=javascript&logoColor=000000&color=d1b01f)

#### Back-end:
 ![Node.js ](https://img.shields.io/badge/node.js-6DA55F?logo=node.js&logoColor=white&style=for-the-badge)
![Heroku](https://img.shields.io/badge/-Heroku-430098?style=flat-square&logo=heroku&logoColor=ffffff)
  ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?logo=mysql&logoColor=white&style=for-the-badge)

__________________________________________________________________________________________________________________________________________________________________

## Installation Instructions

    npm install

### After this repository is cloned, open your command-line in this repository's root directory to install the required dependencies denoted in the package.JSON file.

    npm start

### This will start the server on port 3001 for individual testing purposes. Navigate to localhost:3001/home to test the application out.

    ctrl+C

### Use this command to kill the server at any time.

## Usage Comments

Used  HTML routes to render using handlebars. Built a CMS-style Tech Blog with the required stack! On the same note, using MVC as your architectural structure! The way you went about initializing your app as well as loading and navigating through your routes was very clean and readable! You were able to configure your entire back-end optimally and demonstrated all the required routing and DB functionality in the browser on the client-side when navigating through your elements! Deployed application to Heroku, the url is fully functional!  

### This application and website is used for creating and sharing blog posts centered around technology. Allows users to view, edit and delete their posts and view and comment on the posts of others



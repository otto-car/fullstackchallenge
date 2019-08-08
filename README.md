Full Stack Challenge
====================

This code challenge allows you to demonstrate your ability to build a simple web application, but gives us a chance to see how you code and how you use version control.

We deal with lots and lots of cars on a day-to-day basis, so naturally this will be related to automotives. 

Your challenge consists of two parts: the front-end and the back-end.

### Front End

The front-end must contain two views.

The first view (Cars) contains a form and a table, where a user can add and view cars.

The second view (Statistics) contains a table with statistics, described below.

### Back End 

The back-end must include a web server with two endpoints: `/cars` (for cars) and `/stats` (for statistics on cars and HTTP requests).

The first endpoint, `/cars`, must accept HTTP requests sent using CRUD methods (`GET`, `POST`, `PUT`, `DELETE`) and respond back with JSON describing the status of the request (success, failed, etc).

This is the information we store about each car:
- Make (e.g. Tesla)
- Model (e.g. Model 3)
- Year (e.g. 2019)
- Active (i.e. true/false)

The second endpoint, `/stats`, must respond with the following real time statistics:

  * Total number of cars added 
  * Total number of active cars and inactive cars
  * Active number of HTTP requests sent to the server, classified by HTTP method (eg: 3 GET requests, 4 POST requests, 5 PUT requests)

Before you get started, make sure to read through all the levels below.

#### Base Requirements For All Levels
-------
- A clean, simple front-end to view statistics
- Clean, readable, maintainable codebase
- Source code on Github

#### Levels of Awesome

Choose one of the following routes for your journey. 

-------
### Novice

*"Hey! Look! Listen!"*

**TASKS**
* All of the base requirements
+ Create and implement (using HTML, CSS and JS) a basic design 
+ Use a CSS Framework (Bootstrap, Foundation, Pure, etc.…)

-------
### Intermediate

*"I know Kung Fu."*

**TASKS**
* All of the base, and novice requirements
+ Use a JavaScript framework (Angular, React, Backbone, etc...)
+ Use SASS or LESS for custom CSS
+ Make use of CSS animations
+ Provide instructions on running the web application locally

-------
### Expert

*"Watch and learn Grasshopper."*

**TASKS**
* All of the base, novice, and intermediate requirements
+ Allow users to filter/search through the table of cars
* All of the base, novice, intermediate and expert requirements
+ Host the application online and use a server framework (we enjoy hosting services like AWS, Azure, Heroku and DigitalOcean but you're welcome to use a different hosting provider)
+ Show us your work through your commit history

-------
### Bonus Round

*"All is fair in love and bonus rounds"*

**TASKS**
+ Surprise us! Add a feature that you think would work well here; for instance, advanced search, integration with other API, a "Favorite" functionality

# Allen-Steward_Erica_Vacation_Capstone

[Frontend Repo](https://github.com/mrsemas10/capstone325-frontend.git) <br/>
[Backend Repo](https://github.com/mrsemas10/capstone325-backend.git)


# Introduction
## I love to travel so I wanted to have a place where I could save all my favorite destinations and also know what the weather is during a certain time of year. 

## Process

## Build
1. API
I used a weather API from RapidAPI.com

2. User Authentication
There are 2 routes: Login and Register

3. Frontend
<ol>Entry point for front end: src/App.jsx</ol>
<ol>Components</ol>
<li>Navigation.jsx: for the nav bar</li>
<li>SearchResult.jsx: includes city and weather details</li>
<li>WeatherDetailCards.jsx: includes information about the weather</li>

<ol>Pages</ol>
<li>FavoritePage.jsx: for accessing and manipulating the favorites </li>
<li>HomePage.jsx: links to login, register and instruction on how to use the page</li>
<li>LoginPage.jsx: enter email and password for use of the site</li>
<li>RegisterPage.jsx: enter email and password and confirm password to be able to login</li>
<li>SearchPage.jsx: search cities to add to the favorite list</li>

4. Backend
<ol>Entry point for backend: index.js</ol>
<ol>Server set up with MongoDB</ol>

<ol>Controllers</ol>
<li>auth.controllers.js: for login and register</li>
<li>favorite.controllers.js: add, view, delete favorites</li>

<ol>Models</ol>
<li>favorite.model.js: favorite schema </li>
<li>user.mode.js: user schema</li>

<ol>Routers</ol>
<li>auth.routers: for login and register</li>
<li>favorite.routers: for favorites</li>


## Technology Used
<li>MongoDB</li>
<li>Express</li>
<li>React</li>
<li>NodeJs</li>
<li>JavaScript</li>
<li>Axios</li>
<li>RapidAPI</li>
<li>VS code</li>
<li>Netlify</li>


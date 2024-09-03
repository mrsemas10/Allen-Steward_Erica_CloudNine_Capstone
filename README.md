# CloudNine

## Introduction
#### I love to travel so I wanted to have a place where I could save all my favorite destinations and also know what the current weather is for the location. 


[Live Site](https://cloudnineweather.netlify.app/) <br/>
[Frontend Repo](https://github.com/mrsemas10/capstone325-frontend.git) <br/>
[Backend Repo](https://github.com/mrsemas10/capstone325-backend.git)


## Process

### Build
#### 1. API
I used a weather API from RapidAPI.com

#### 2. User Authentication
There are 2 routes: Login and Register

#### 3. Frontend
* Entry point for frontend: src/App.jsx

* Components
  * Navigation.jsx: for the nav bar
  * SearchResult.jsx: includes city and weather details
  * WeatherDetailCards.jsx: includes information about the weather

* Pages
    * FavoritePage.jsx: for accessing and manipulating the favorites
    * HomePage.jsx: links to login, register and instruction on how to use the page
    * LoginPage.jsx: enter email and password for use of the site
    * RegisterPage.jsx: enter email and password and confirm password to be able to login
    * SearchPage.jsx: search cities to add to the favorite list


#### 4. Backend
<ol>Entry point for backend: index.js</ol>
<ol>Server set up with MongoDB</ol>

* Controllers
  * auth.controllers.js: for login and register
  * favorite.controllers.js: add, view, delete favorites

* Models
  * favorite.model.js: favorite schema
  * user.mode.js: user schema

* Routers
  * auth.routers: for login and registe
  * favorite.routers: for favorites
  * 

## Technology Used
<li>MongoDB</li>
<li>Express</li>
<li>React</li>
<li>NodeJs</li>
<li>JavaScript</li>
<li>Axios</li>
<li>RapidAPI</li>
<li>Google Fonts</li>
<li>RapidAPI</li>
<li>VS code</li>
<li>Netlify(for frontend)</li>
<li>Render(for backend)</li>


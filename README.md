# Seedling School

## 01 - Frontend Project

For your first project, you will build a frontend website with HTML, CSS and JavaScript. The website will communicate and integrate with a 3rd party Web API.

## Goals

These are the required goals for the project. Every project should _at least_ meet these goals.

* General
  * Demonstrate your ability to build basic multi page frontend websites
  * Demonstrate your ability to deploy a website to the web so anyone can access it
  * Demonstrate your ability to debug code with the chrome / firefox dev tools
  * Demonstrate your ability to manage a project with a tool like trello or github projects
  * Demonstrate your ability to create wireframes and implement those wireframes
  * Demonstrate your ability to complete a project to MVP (Minimum Viable Product) within 1.5 weeks
  * Demonstrate your ability to use a REST API tool to test requests to a 3rd party API
* HTML
  * Demonstrate your ability to create html pages that link to each other
  * Demonstrate your ability to use semantic HTML tags
  * Demonstrate your ability to use accessible alt tags
* JavaScript
  * Demonstrate your ability to take in user input
  * Demonstrate your ability to make API requests with front-end JavaScript
  * Demonstrate your ablity to handle CORS requests / errors
  * Demonstrate your ability to use and manipulate data from a 3rd party web API
  * Demonstrate your ability to handle errors gracefully
  * Demonstrate your ability to traverse and manipulate the DOM (Document Object Model) with Vanilla JS (No frameworks like Vue or libraries like jQuery)
    * Demonstrate your ability to select elements in the DOM
    * Demonstrate your ability to modify elements in the DOM
    * Demonstrate your ability to add elements to the DOM
* CSS
  * Demonstrate your ability to use a CSS Framework (see a list of CSS Frameworks [here](./CSS_FRAMEWORKS.md)) to create responsive and adaptive layouts

## What you will build

Your website should have 2 HTML pages.

* 1st Page - Landing Page
  * Title of the project
  * Description of the project
    * What it is
    * Why you built it
    * How people can use it
  * Link to your github / portfolio site
  * Link to the 2nd page (Application page)
* 2nd Page - Application Page
  * Will take in user input
    * For example
      * Search form
      * Settings check boxes
  * Use user input to contact a 3rd party API for data
  * Add the data from the 3rd party API to the page
* Your website will be deployed to a service like netlify, surge, heroku, github pages or now.sh so that others can access / use it

## Example Project Ideas

* Allow user to enter stock names and view a realtime chart of stock price
  * Same idea, but with crypto
* Use a Nutrition API too allow a user to enter the contents of their pantry to get nutritional information
* Use a Movie API to allow a user to search for Movie descriptions / posters
* Use an Image API to allow a user to search and favorite images (favorites stored in local storage)
* Use a News API to search for news articles
* Use a places / restaurant API to list restaurants near a user
* Use the ISS API to show the current location of the ISS on a map
* Use a Rocket Launch History API to allow the user to see if a rocket was launched on a specific day
* A trip planner
  * Use ride share API to calculate ride cost
  * Use a places search API to find hotels in a given place
  * Use a places search API to find things to do in a given place
  * Allow the user to save a list of things to do in the browser (localstorage or indexdb) 
* Use a game stats API to allow the user to search for top gamers of a given game

## How to Participate

1. Copy the Project Description Template into your own git repo
  * Copy the description from [here](https://raw.githubusercontent.com/CodingGarden/seedling-school-01-frontend-project/master/PROJECT_DESCRIPTION_TEMPLATE.md)
  * Do not fork or clone this repo.
  * Create your own repo on github named after your application
2. Fill out Project Description Template in your own git repo and push to github
3. [Open an issue on this repo](https://github.com/CodingGarden/seedling-school-01-frontend-project/issues/new) with a link to your project description
  * Link to the description file
  * Paste your 2 - 3 sentence description
  * Link to the API you plan to use
4. Leave a comment on the issue as to the current state of your project
  * Submitted / Description under review
  * Project Started
  * Need a lesson on a topic
  * Need Help with a Bug
  * Project Deployed
  * Waiting for Code Review
  * Waiting for Feedback

> See the [Code Review Checklist](./CODE_REVIEW_CHECKLIST.md) and [UI Review Checklist](./UI_REVIEW.md) to know what I'll be looking for.

## Example 3rd party web APIs to use

> NOTE: you will want to find an API that does not require OAuth / authentication, and is completely open or only requires an API key.

* Weather API
* News / Articles API 
* Movie API
* Picture API
* Wikipedia API
* Nutrition API
* Recipe API
* Nasa API
* Trading API
* Crypto Currency API
* Hotel API
* Watson API
* Pokemon API
* Game Stats API

* See a full list of many different Free / Open Web APIs you can use:
  * https://github.com/public-apis/public-apis
  * https://apilist.fun/collection/free-apis
  * https://duckduckgo.com/?q=free+web+apis&ia=software
  * https://www.google.com/search?hl=en&q=free%20web%20apis
  * https://www.programmableweb.com/apis/directory

## In Scope

You can use 3rd party javascript libraries for:

* Data Visualization
* Maps
* pdf renderer

## Out of Scope

You should not have any of these things in your project, (To help with consistent project feedback / project feasiblity):

* User Login
* Custom Backend API (Like express / django etc.)
* Custom Backend Database (Mongo, MySQL)
* Firestore / firebase

## FAQ

* What is deadline for submissions?
  * No deadline, but try to complete your project with 1.5 weeks from the time you start.
  * The community will be checking for new issues / comments on a regular basis, so you can start this project at anytime.

## Stretch Goals

Not required, but if you want to go above and beyond:

* Use a web browser API like geolocation, battery / device, gamepad etc.
* Use a linter (eslint)
* Mobile first approach
* SEO friendly tags
* UI Animations
* Docker
* Build process with babel / webpack / gulp / scss / less etc.
  * Use PostCSS for cross browser compatibility
* Use plain CSS with Flexbox / grid instead of a CSS Framework
* Settings persistence in the browser with Local Storage or IndexDB
  * Hard coded username / password checked against local storage
* Structure your javascript code in an MV* pattern (No 3rd party libraries)
* Use a state management pattern in your JavaScript code (No 3rd party libraries)
* Multiple pages with DOM manipulation (SPA) instead of multiple html files.
* Document JavaScript with JSDoc
* E2E testing
* PWA
* Any constraint you want to put on yourself to get better at a particular technology
  * Only ES5 (No ES6+ features)
  * Functional Programming
  * IE9 compatibility
  * etc.
* 100% lighthouse score
* Use a CI / CD pipeline

> If you think of more stretch goals, feel free to open a pull request to update this list.

## TODO: (For CJ on stream)

* [ ] Create an Overall Project Rubric to use for consistent reviews and self guidance

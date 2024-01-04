# Meal App

<p align="justify">
  Developed the React app to search, add to favourites, view more details using a meal API https://www.themealdb.com/api.php
Implemented a responsive search functionality on the home page that dynamically fetches and updates meal suggestions from the API as the user in search.
</p>

## Deployed On
**GitHub**
<br>
<img src="https://github.com/AdityaLambat/skill-icons/blob/main/icons/Github-Dark.svg" width="50">

## Hosted Link
https://adityalambat.github.io/MealApp/

## Features
````
1. The app features a robust recipe search with real-time suggestions as users type, streamlining the process of discovering a diverse range of recipes.
2. Users can easily manage and curate a list of favorite meals by utilizing the interactive 'Favorite' button associated with each search result.
3. Clicking on a specific recipe opens a dedicated Meal Detail Page, providing detailed information such as the meal's name, a visually appealing photo, step-by-step instructions, and additional relevant details for a more immersive cooking experience.
````
## Technologies Used

The IssueTracker is build using the following technologies:

<p>
  <img src="https://github.com/AdityaLambat/skill-icons/blob/main/icons/HTML.svg" width="50">
  <img src="https://github.com/tandpfun/skill-icons/raw/main/icons/CSS.svg" alt="CSS Icon" width="50">
  <img src="https://github.com/AdityaLambat/skill-icons/raw/main/icons/JavaScript.svg" width="50">
  <img src="https://github.com/AdityaLambat/skill-icons/blob/main/icons/Bootstrap.svg" width="50">
  <img style="border-radius: 20px;" src="https://github.com/AdityaLambat/MealApp/blob/main/api.png" width="50">
</p>

## Getting Started

To set up the API on your local machine, follow these steps:
````
1. Clone the repository.
2. Install the packages using npm

````

## After reaching the project directory you have to run the following command.
````
 node index.js

````

## Folder Structure

````
Issue Tracker
  ->|           
    |---> assets --->|
    |                |---> js --->|
    |                             |---> filterissues.js
    |                             |---> searchissues.js
    |                  
    |---> config --->|
    |                |---> mongoose.js
    |
    |---> controllers --->|
    |                     |---> home_controller.js
    |                     |---> project_controller.js
    |             
    |---> models--->|
    |               |---> issue.js
    |               |---> project.js
    |
    |---> routes --->|
    |                |---> index.js
    |                |---> project.js
    |
    |---> views --->|
    |               |---> partials --->|
    |                                  |---> home.ejs
    |                                  |---> layout.ejs
    |                                  |---> project_page.ejs
    |             
    |---> README.md
    |---> index.js
    |---> package-lock.json
    |---> package.json
    ````

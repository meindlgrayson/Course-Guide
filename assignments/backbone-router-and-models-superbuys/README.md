# Backbone Routing + Backbone Models/Collections -- Superbuys

## Objectives

After completing this assignment, you should be able to:

* Breakdown a simple sequence of procedural steps into a series of statements in JS
* Use Backbone Router to listen to the hash and render different UI's
* Use Backbone Models + Collections to fetch data
* Successfully render data to the page in a formatted layout


## Details

### Instructions
1. Download and then unzip [the project files](https://raw.githubusercontent.com/TIY-Charleston-Front-End-Engineering/Course-Guide/master/assignments/22-backbone-router-and-models/backbone-router-and-models.zip) into your `~/TIY/assignments` directory.

2. *All* book data is fetched from: `https://www.googleapis.com/books/v1/volumes?q=subject:«subject-name»`. Examples:
  - https://www.googleapis.com/books/v1/volumes?q=subject:mystery
  - https://www.googleapis.com/books/v1/volumes?q=subject:fiction

### Deliverables
* A page that dynamically fetches and renders data based on information in the hash route

### Requirements

* An application that uses Backbone Collections to fetch JSON data from the [Google Books API](https://developers.google.com/books/docs/v1/using) using AJAX requests.
* An application that shows requests data from different URL endpoints depending on what is in the hash-route

## Normal Mode

Create a simple application that fetches data from the Google Books API. It should have buttons for navigating the various endpoints. The routes should be as follows:
  - `#books/«genearl-category»/«sub-category»`
  - `#books/«general-category»`
  - `""` (home route)

![gif](https://raw.githubusercontent.com/TIY-Charleston-Front-End-Engineering/Course-Guide/master/assignments/22-backbone-router-and-models/mockups/superbuys-routing-and-models.gif)


## Explorer Mode
Add a search feature.

##Adventure Mode
Add the UI logic for breadcrumbs and a sidebar

# Fullstack Nano degree Project 3

***

## Name of Project: Dallas Texas Restaurant app.

### Description: The Dallas Texas Restaurant Application provides a list of restaurants along with particulars such as location, map, type of cuisine, and menu items. Site incorporates user registration, and oauth authentication along with the ability to post, edit and delete new restaurants, and menu items. Site allows the user to filter for particular cuisine types to narrow the list of restaurants to view.
***

### Required Files and software.

#### Python: feb32015.py (Creates db, and tables), dbpopfeb3.py (Populates the DB with items for restaurant), dropallfeb32015.py (Drops all table data in the db), master.py (contains the main server code)

#### json: FB_client_secrets.json, and client_secrets.json provide the needed code to allow for oauth authentication to take palce.

#### restaurantmapped.db: This is a sqlite db where all the apps data is stored and managed.

#### README.md: You are looking at it.

#### static folder: Contains the styles.css files that allows for some customized formatting of the web site. All othe files in the static folder are jpg and png files that are used by the web site application.

#### js: Contains the bootstrap.js file and bootstrap.min.js file used to create cool functions like carousel, drop down menus in a web site. jquery-2.1.4.js provides additional js for the web app.

#### templates folder: Contain all the .html templates used by the application. flask, jinja are used to render templates from python and to script python within html.
***

## Web Application Setup

#### 1. Install Vagrant. Follow these instructions. [vagrant] (https://www.udacity.com/wiki/ud197/install-vagrant)
#### 2. Clone this project from Github. [project] (https://github.com/udacity/proj3fullstack)

***
### List of master.py module functions.

####Functions login, fbconnect, fbdisconnect, gconnect, creatUser, getUserInfo, getUserID, gdisconnect, and disconnect are used for logging in or out of the application using oauth function via facebook and google.

#### restaurantMenuJSON(), menuItemJSON(), restaurantJSON(), and showRestaurantJSON() are used to create output to mobile devices.

#### showRestaurant() displays a list of the restaurants.

#### newRestaurant() builds a new restaurant in the database using sqlachemy.

#### editRestaurant allows the user to change aspects about the restaurant.

#### deleteRestaurant allows the user to delete a restaurant from the database.

#### showMenu will query and display the restaurant menu.

#### showRestCuisine will query on a particular type of cuisine.

#### newMenuItem will allow the user to build a new menu item that.

#### editMenuItem will allow the user to edit a menuitem that belongs to them.

#### deleteMenuItem allows the user to delete a menu item.




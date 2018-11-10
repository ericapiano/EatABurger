# Eat-A-Burger
A burger logger with MySQL, Node, Express, Handlebars and a homemade ORM that uses Node. It also uses MySQL to query and route data, and Handlebars to generate HTML.

## Getting Started
* Clone the EatABurger repo to your computer
* Run a npm install to acquire dependencies
* Create database and tables by running the schema file in your preferred sequel application (ex - Sequel Pro, MySQL Workbench)
* Launch website by entering 'heroku open' from command line

## Functionality
* EatABurger is a restaurant app that allows users to input names of burgers they'd like to eat.

* When a user submits a burger, the app will display the burger above the form under its category -- waiting to be devoured.

* Each burger in the waiting area also has a 'Devour it!' button. When the user clicks it, the burger will move above the form under its category

* The app stores every burger in a database, whether devoured or not.

## Technologies Used
* Express
* Handlebars Templating Engine
* Node.js
* MySQL
* Heroku

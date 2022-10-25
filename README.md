# E-commerce Back End 
Repository link: https://github.com/AaronVenema/e-commercebackend
## Table of Contents
* [Demo](#Demo)

* [Description](#Description)

* [Installation](#Installation)

* [Acceptance Criteria](#Acceptance-Criteria)

### Demo
![gif](https://github.com/AaronVenema/e-commercebackend/blob/main/demo/demoGif.gif)

### Description
e-commerceBackEnd is an mysql2 application that can help the user stay organized when managing server side data. It features the ability to add categories, tags, and product tags. It features the ability to view categories, tags, and product tags. It features the ability to update categories, tags, and product tags. It features the ability to delete categories, tags, and product tags 

### Installation
Node, inquirer, mysql2, sequilize, insominia, and nodemon for development. 


### Acceptance Criteria
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

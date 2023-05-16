# ORM-E-Commerce-Back-End

## Description
The back-end database has been purposed towards e-commerce websites using Express.js API and Sequelize to connect to the MySQL database. The back-end database allows users to create a development database, seed it with test data, and sync Sequelize models to MySQL database. The users have the ability to use GET, POST, PUT, and DELETE routes to display and manipulate data in the users database.

## Table of Contents:
- [Overview](#Overview)
- [The Challenge](#The-Challenge)
- [Usage Information](#Usage-Information)
- [Installation Process](#Installation-Process)
- [Built With](#Built-With)
- [What I Learned](#What-I-Learned)
- [Continued Development](#Continued-Development)


# Overview

## The Challenge:
This challenge required the creation of an e-commerce back-end site. These requirements include the ability to connect to a MySQL database using Sequelize, create a development database that is seeded with test data, sync Sequelize models to the MySQL database, and display data from categories, products, and tags in a formatted JSON. The application should also be able to create, update, and delete data in the database.

## User Story


* AS A manager at an internet retail company
* I WANT a back end for my e-commerce website that uses the latest technologies
* SO THAT my company can compete with other e-commerce companies


## Acceptance Criteria


* GIVEN a functional Express.js API
* WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
* THEN I am able to connect to a database using Sequelize
* WHEN I enter schema and seed commands
* THEN a development database is created and is seeded with test data
* WHEN I enter the command to invoke the application
* THEN my server is started and the Sequelize models are synced to the MySQL database
* WHEN I open API GET routes in Insomnia for categories, products, or tags
* THEN the data for each of these routes is displayed in a formatted JSON
* WHEN I test API POST, PUT, and DELETE routes in Insomnia
* THEN I am able to successfully create, update, and delete data in my database


### Figure .1 

The following photo demonstrates the application functionality in Insomnia: <img width="1440" alt="Screenshot insomnia" src="https://github.com/AlexNanut/ORM-E-Commerce-Back-End/assets/108309770/81c3305b-69b5-404f-8323-83dbf997111e">




## Usage Information
1. Repository: Open documentation run 'npm i' and update '.env'.
2. Create database: use the schema.sql file in the db folder with MySQL shell commands. Use environment variables to store sensitive data like your MySQL username, password, and database name.
3. Run 'npm run seed' to seed the database with test data. Then, run 'npm start' or 'nodemon' to start the server and sync the Sequelize models to the MySQL database.
4. Generate a development database with test data, use the schema and seed commands.
5. Use Insomnia to test http://localhost:3001 with the following route end points API GET, POST, PUT, and DELETE routes for categories, products, and tags, ensuring successful creation, updating, and deletion of data in the database.

## Deployed Application Link:
[Deployed Application Link:](https://github.com/AlexNanut/ORM-E-Commerce-Back-End)

## GitHub Repository:
[GitHub Repository:](https://github.com/AlexNanut/ORM-E-Commerce-Back-End)

## Built With
- JSON
- Dynamic JavaScript
- Express
- Node.js
- Express.js
- Node MySql2
- Sequelize
- Insomnia
- Nodemon


## What I Learned:
1. How to use Express.js to create a functional back end for an e-commerce website.
2. How to connect to a MySQL database using Sequelize.
3. How to generate a development database with test data using schema and seed commands.

## Continued Development:
1. Implement the latest technologies, such as Express.js, MySQL, and Sequelize to create a functional back end for the e-commerce website.
2. Ensure that I can get the routs for all categories in Insomnia. 


# E-Commerce-Backend-ORM

A backend application for the prevalence of internet retail and its fundamental architecture.

# Table of Contents

    Description
    Installation 
    Usage
    Technology
    Questions
    License

# Description

This backend application utilizes Object Relational Mapping by using Sequelize to interact with MySQL. This allows users to perform CRUD operations or Put, Get, Post and Delete operations. Users can make API requests to view all or single products using Express.js.

# Installation

1. A user must clone the main project via the HTTP or SSH key on GitHub with the following command (git clone).

2. Once cloned, and project folder is opened in your text editor run the following command to install all dependencies (npm install).

3. Create a .env file in the main directory and include your data for the following mySQL info..
    DB_NAME=' '
    DB_USER=' '
    DB_PASSWORD=' '

4. Once your .env file is complete be sure your schema.sql file matches and you can run the following command run MySQL ( mysql -u root -p ).

5. Enter your password for MySQL and source your schema.sql file with the following command ( SOURCE schema.sql; ).

6. Before seeding data be sure to reset force:false to true in the server.js file and run the following command ( npm start )

7. To seed the data with the starter data run the following command ( npm run seed ) and ( npm start ) to run the server and begin.

# Usage

Using Insomnia you can begin to make you POST, PUT, GET, DELETE requests.

# Technology
     
     Express.js
     Node.js
     Sequelize
     MySQL2
     JavaScript
     Dotenv

# Questions

If you have any additional questions please email me at miketw1212@hotmail.com. 

# License

Refer to GitHub
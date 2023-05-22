# umbr-code
starter code from umbrella/fantastic

Description

The back-end database has been purposed towards e-commerce websites using Express.js API and Sequelize to connect to the MySQL database. The back-end database allows users to create a development database, seed it with test data, and sync Sequelize models to MySQL database. User's have the ability to use GET, POST, PUT, and DELETE routes to display and manipulate data in the users database. Give it a try and see how it helps your company power up to the next level!

The Challenge:

This challenge requires the creation of an e-commerce back-end site that meets specific user requirements. These requirements include the ability to connect to a MySQL database using Sequelize, create a development database that is seeded with test data, sync Sequelize models to the MySQL database, and display data from categories, products, and tags in a formatted JSON. The application should also be able to create, update, and delete data in the database.

Usage Instructions

Repository: Open documentation run 'npm i' and update '.env'.
Create database: use the schema.sql file in the db folder with MySQL shell commands. Use environment variables to store sensitive data like your MySQL username, password, and database name.
Run 'npm run seed' to seed the database with test data. Then, run 'npm start' or 'nodemon' to start the server and sync the Sequelize models to the MySQL database.
Generate a development database with test data, use the schema and seed commands.
Use Insomnia to test http://localhost:3002 with the following route end points API GET, POST, PUT, and DELETE routes for categories, products, and tags, ensuring successful creation, updating, and deletion of data in the database.


Built With

JSON: JSON
Dynamic JavaScript
Dotenv: 8.6.0
Express: 4.17.1
Node.js: Version 16.18.1
Express.js:Express.js
Node MySql2: 2.1.0
Sequelize: 6.31.1
Insomnia
Nodemon: 2.0.12
Visual Studio Code: Website
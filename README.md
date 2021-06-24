# E-COMMERCE 

## Description 
The goal of this assignment was to build the back-end of an e-commerce application by using Sequelize and MySQL2 to interact with a MySQL database. In developing this application, I was able to gain a stonger understanding of the fundamental architecture of e-commerce platforms, and advance in my path to becoming a full-stack web developer.

## User Story
"As a manager at an internet retail company, I want a back end for my e-commerce website that uses the latest technologies so that my company can compete with other e-commerce companies."

## Acceptance Criteria 
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

## Installation
To get my application up and running, I first reviewed the provided starter code. Next, I installed the necessary npm packages I would need to run my application, including: [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) to connect the Express.js API to the MySQL database, and the [dotenv](https://www.npmjs.com/package/dotenv) to store sensitive data.  

Next, I created the following four models (with their requirements) to be included in my database: Category, Product, Tag, and ProductTag. Then, I executed association methods on those models to create the necessary relationships between them. With my models created, I then filled out the unfinished get, post, put, and delete routes in the starter code files to perform the required CRUD operations. 

After creating the models and routes, I used MySQL Workbench to create my database. After making sure I "used" this newly created database, I seeded it with the provided starter code by running npm run seed, and began testing my routes. There were a few hiccups and edits I needed to make, but I eventually got all of my routes to function correctly and finished developing the application! 

## Usage
[Here](https://github.com/go-yasi/ecommerce-backend) is a link to the GitHub repository containing my application code.  
[Here](https://google.com) is a link to a video walkthrough demonstrating the functionality of my code. 

## Conclusion
Overall, I enjoyed creating this application! It helped me develop a better understanding of databases and how to interact with data on the backend. 
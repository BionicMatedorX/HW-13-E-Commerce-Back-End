# HW-13-E-Commerce-Back-End
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Link to Public Repo on Github:
https://github.com/BionicMatedorX/HW-13-E-Commerce-Back-End
## Table of Contents
1. [Description](#Description)
2. [Video Walkthrough](#Video-Walkthrough)
3. [User Story](#User-Story)
4. [Initialization](#Initialization)
5. [License](#License)
6. [Questions](#Questions)
## Description
- This project is to showcase to a user how to access and work on a database that contains specific Category, Product, and Tag information of a store's inventory. Within this project, the user will have the abilities to create, read, update, and delete the information within the database as they so chose.
## Video Walkthrough
- Here is a walkthrough of how the app works
  <a target="_blank" href="https://watch.screencastify.com/v/Qb2YToN6wR4uR6kPchnk">View the Footage Here</a>
## User Story
    GIVEN a functioning Express.js API

    WHEN I add the database name, MySQL information (username and password) to a .env file
    THEN I am able to connect to a database using Sequelize

    WHEN I enter schema and seed commands
    THEN a development database is created and is seeded with test data

    WHEN I enter the command to invoke the application
    THEN my server is started and the Sequelize models are synced to the MySQL database

    WHEN I open API GET routes in Insomnia Core for categories, products, or tags
    THEN the data for each of these routes is displayed in a formatted JSON

    WHEN I test API POST, PUT, and DELETE routes in Insomnia
    THEN I am able to create, update, and delete data within the database

## Initialization
- Download project files via Github
- Open server.js file and change the password field to your own MySQL password
- Open Terminal and proceed to type "npm install"
- From here we will move to our database so type "cd db/" then type "mysql -u root -p" and enter your personal password. Now we will type "source schema.sql" and "source seeds.sql" 
- To exit MySQL we will type "exit" then proceed to type "npm run start"
- Now you can view the database and add or remove things
## License
- MIT License
- Copyright 2021
    Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
## Questions
- GitHub Profile: <a href="https://github.com/BionicMatedorX">Click Here</a><br>
- My Email: brothajohnny@gmail.com<br>
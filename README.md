# E-Commerce-Back-End
[![License: MIT License](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://choosealicense.com/licenses/mit/)
 
**Project name**: e-commerce Back End Challenge

**Description**: This project purpose was to test skills learned with Sequelize and mySQL database and further node.js & Express.

**Special Notes**: this project is command line applicatoin. the modules used are: Express, mysql2, dotenv, and Sequelize.

**Installation**: 	

access Github repository here: https://github.com/cjsmith1988/E-Commerce-Back-End

Live URL: https://immense-ridge-01896.herokuapp.com/api/

🎥 Part 1: https://youtube.com/embed/d4z1PjVm-go

🎥 Part 2: https://youtube.com/embed/rqCS2gVavKc

🎥 Part 3: https://youtube.com/embed/Fk_Y6Xrakng

🎥 Part 4: https://youtube.com/embed/f3AbxizKcnQ


To download this application localy follow these steps:

- Clone repository

- Open command line with node.js installed and you are located in the cloned directory.

- In the command line type "npm i"

- Open a command line in the location of the cloned directory and type "mysql -u root -h localhost -p" and "CREATE DATABASE ecommerce_db;" and "use ecommerce_db;"

- this will create the mySQL database

- create a new file in the directory to store your connection information by using the git bash command "touch ./.env"

- next enter this command: "echo "DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='<<your mySQL password>>' > ./.env"

- Back in the GItBash console type "npm start" to start the application

**Usage**: This was used for testing sequelize methods.

**Contributing**: open for contribution, keep in seperate branch

**Credits**: This page was made by Curtis Smith

**License**: MIT License

### User Story:

AS A manager at an internet retail company

I WANT a back end for my e-commerce website that uses the latest technologies

SO THAT my company can compete with other e-commerce companies

### Requirements:

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

![Api Category view](https://github.com/cjsmith1988/E-Commerce-Back-End/blob/main/images/insomniaCategoryScreenGrab.PNG?raw=true)
![Api Product view](https://github.com/cjsmith1988/E-Commerce-Back-End/blob/main/images/insomniaProductsScreenGrab.PNG?raw=true)
![Api Product POST view](https://github.com/cjsmith1988/E-Commerce-Back-End/blob/main/images/insomniaProductsPOSTScreenGrab.PNG?raw=true)

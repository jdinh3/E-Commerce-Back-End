# E-Commerce-Back-End

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
## Description

This is an E-Commerce Back End application that allows a user to run Get, Post, Put, and Delete requests in their database to view and update their products and product information. The user is able to run Get requests to see the following:

-All products
-All tags
-All categories
-All products within a certain category
-All products listed by a certain tag
-A singular product
-A singular tag with its associated products
-A singular category

To create new categories, new tags, or new products, the user can run a post request in the application. To update any product, category, or tag information, the user is able to run a put request and the targeted ID will be updated with the new information. The application also allows the user to run a delete request which will delete the targeted product, category, or tag that the user wishes to remove. 
## Usage

Run 'NPM Install' in the terminal to make sure all packages are installed.
Add your MySQL username and password to the .env file.
Run the schema in My SQL Workbench to create the database.
Run 'NPM run seed' in the terminal to seed the database.
Run 'NPM start' in the terminal to connect to the server.

Here are video tutorials (Part 1 and Part 2) to show you how the application works:

[Tutorial Part 1](https://drive.google.com/file/d/1QneYkZaNPEIVITOrONwfParR7NlCI-4t/view)
[Tutorial Part 2](https://drive.google.com/file/d/1kfUOmoRf6gmJ722WT14qEwNnexWSwReO/view)

## Screenshot
[E-Commerce](/assets/screenshot.png)

## Technologies

This application is created using JavaScript, MySQL, sequelize, dotenv, and express. The application displays user data through mySQL models and associations. Express is used to create the API routes which will then display specific data through CRUD operations.
## License 

This project is licensed under MIT License.

## Questions

If you have any questions about the repo, open an issue, or contact me directly at jenny.p.dinh@gmail.com. You can find more of my work at (https://github.com/jdinh3)



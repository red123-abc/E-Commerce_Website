# E-Commerce_Website

Problem Statement & Requirements :

To build a simple e-commerce website with the following pages :

1. Home
2. Register / Login
3. Products
4. CRUD
5. Logout

NOTE : 

In this assignment, an online e-commerce website of a clothes store is created with the following features :

1. Home page is created and the store is selling clothes to the customers.
2. Register/Login feature is included, that is, a new user has to register or create account first, then on logging in he/she can place order(s).
3. Products have been clearly mentioned.
4. The feature of CRUD (Create, Reduce, Update, Delete) is also included.
5. Also, the provision to logout of the website is also enabled.
6. And, appropriate messages are added everywhere, so that the user takes all the steps and places order successfully in a structured ordered.

How to Run the Project :

Run Locally :

1. Clone repo

$ git clone git@github.com:red123-abc/E-Commerce_Website.git
$ cd E-Commerce_Website

2. Install MongoDB

Download it from here: https://docs.mongodb.com/manual/administration/install-community/
3. Run Backend

$ npm install
$ npm start

4. Run Frontend

# open new terminal
$ cd frontend
$ npm install
$ npm start

5. Create Admin User

    Run this on chrome: http://localhost:5000/api/users/createadmin
    It returns admin email and password

6. Login

    Run http://localhost:3000/signin
    Enter admin email and password and click signin

7. Create Products

    Run http://localhost:3000/products
    Click create product and enter product info

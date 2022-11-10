# E-Commerce Backend (Object-Relational Mapping (ORM)

[![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)

## Description

This project is about building the back end for an e-commerce site. This application used Express.js API and Sequelize to interact with a MySQL database. This application creates a database using mySQL with models and associations. API Routes are derived to perform RESTful CRUD operations using sequelized models and the same is being tested in Insomnia.

## Table of Contents

- [Installation](#installation)
- [ScreetShots](#ScreenShots)
- [Demonstration](#Demonstration)
- [License](#license)
- [Tests](#tests)
- [Questions](#questions)

## Installation

- Dependencies/Packages
  - Node.js
  - Express.js
  - MySQL2
  - Sequelize
  - dotenv
- Git clone the repo from Github
- Navigate to the folder and run `npm install` in your terminal.
- Be sure to include your MySQL user/password information in .env file.
- Database Connection
  - `mysql -u root -p`
  - `source schema.sql`
  - `npm run seed` [To seed the file]
- Run the app

  - `npm start` [To start the server] and navigate to <http://localhost:3001/> in your browser OR Use Insomnia Core

  ## ScreetShots

  ![](./Assets/Images/Tag%20Route%20Pic.jpg)
  ![](./Assets/Images/Product%20Routes%20Pic.jpg)
  ![](./Assets/Images/Category%20Routes%20Pic.jpg)

  ## Demonstration

  This application will allow users to view, add, edit, and delete categories, products, and tags. Below videos demonstrate the functionality of the e-commerce back end.

1. Walkthrough video covers MySQL shell [Click here](https://drive.google.com/file/d/1jSVyuvTZGab8mSt78HyyLasmOV9S0cR3/view?usp=sharing)<br>

   - Source the schema <br>
   - Seed the database <br>
   - Start the npm Server

2. Walkthrough video covers API routes being tested in Insomnia Core.

- Categories : [Click here](https://drive.google.com/file/d/1TUBghIW3pE8Jye6t50kF33U0kzs4mqTK/view?usp=sharing)<br>
- Products : [Click here](https://drive.google.com/file/d/1YsJXXlATRk_Q_KfYsUsWnrLYV3aOyy_n/view?usp=sharing)<br>
- Tags : [Click here](https://drive.google.com/file/d/1UsyYfdT3S_7iPmvn0V4x5pKh0oRvla14/view?usp=sharing)<br>
  - GET routes for all categories, all products, and all tags <br>
  - GET routes for a single category, a single product, and a single tag by Id<br>
  - POST, PUT, and DELETE routes for categories, products, and tags

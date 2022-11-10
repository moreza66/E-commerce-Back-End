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

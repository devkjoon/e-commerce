# E-Commerce
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  

## Description

A mySQL database and application to manage a company's catalog. With this application you are able to create, delete, update, and retrieve catalog data.

## Table of Contents

- [Built With](#built-with)
- [Installation](#installation)
- [Usage](#usage)
- [Preview](#preview)
- [License](#license)

## Built With

- Express.js
- Node.js
- mySQL
- dotenv

## Installation

- Open integrated terminal through `schema.sql`, then `mysql -u root -p`
- Enter the password. In this case it would be `password`
- Source the `schema.sql` file
- Open integrated terminal through `server.js`
- Start application by executing `nodemon server.js`

## Usage

- GIVEN a functional Express.js API
- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
- THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands
- THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application
- THEN my server is started and the Sequelize models are synced to the MySQL database
- WHEN I open API GET routes in Insomnia for categories, products, or tags
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia
- THEN I am able to successfully create, update, and delete data in my database

## Preview

### Application Prep
[mySQL Source.webm](https://user-images.githubusercontent.com/114375310/214341588-f7b249f3-d0fd-4e84-90d8-a722ce6da101.webm)
### Category Routes
[Categories Requests.webm](https://user-images.githubusercontent.com/114375310/214341654-1158a2d6-655f-472f-9755-58f0034fab16.webm)
### Product Routes
[Product Routes.webm](https://user-images.githubusercontent.com/114375310/214345973-6de9b352-f53c-446d-af32-68e6b83c35b5.webm)
### Tag Routes
[Tag Routes.webm](https://user-images.githubusercontent.com/114375310/214342216-4536c24e-a2d2-411c-974e-edcba0ee3cc3.webm)

## License

See LICENSE in repository

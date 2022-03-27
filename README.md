# E-commerce Back End
[![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)

## Description 
This application is the back end for an e-commerce site. It was built using Express, MySQL2, Sequelize, and dotenv.
 
## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributing](#contributing)
* [Questions](#questions)

## Installation 
To install, first clone the repository from GitHub and then install Node. Install express, dotenv, mysql2, sequelize, and nodemon by running `npm i` in your command line.

You will then need to create a .env file within the root folder. The file will need to include: DB_USER=(your username), DB_PW=(your password), and DB_NAME=ecommerce_db

To set up the database:
* Run `mysql -u username -p`
* Enter your password
* `source db/schema.sql`
* `quit`
* `npm run seed`

## Usage 
Run `npm start` in your command line. Open Insomnia and check the API GET, POST, PUT, and DELETE routes:
* http://localhost:3001/api/categories/ (add an id if GET by ID, PUT/updating a category, or DELETING a category)
* http://localhost:3001/api/tags/ (add an id if GET by ID, PUT/updating a tag, or DELETING a tag)
* http://localhost:3001/api/products/ (add an id if GET by ID, PUT/updating a product, or DELETING a product)

You can also view a video walkthrough [here](https://youtu.be/aM1WGp4Srj0).

## License 
To read the ISC license click [here](https://opensource.org/licenses/ISC)

## Contributing 
Please read the [installation](#installation) section.

## Questions
If you have any questions please contact email me [here](mailto:nate.granzow@gmail.com). You can also view more of my projects [here](https://github.com/ngranzow/).
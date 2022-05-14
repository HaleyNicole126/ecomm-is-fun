
  
  # EComm is Fun

  ## Table of Contents
  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [Tests](#tests)
  - [License](#license)
  - [Questions](#questions)

  ## Description
  This project is the back end for an e-commerce website. It is an Express.js API that utilizes MySQL2 and Sequelize packages to connect to and interact with a MySQL database. 

  ## Installation
  To install this project, first clone the code from the repository to your computer. Run `npm install` from the root of the project to install the dependencies, which include the express, mysql2, sequelize, and dotenv packages. Next, use the MySQL shell to create the database by first entering the MySQL shell using `mysql -u root -p` and your MySQL password, and then `source db/schema.sql` once you're in the shell. Quit the shell and create a .env file at the root of the project (and remember to add it to your .gitignore file!) to set up the environment variables. Now you're ready to seed the database and start the application! 

  ## Usage
  To seed the database, run `npm run seed`. Then, you can start your server using `npm start`. GET, POST, PUT, and DELETE routes have been defined for categories, products, and tags. These can be tested using Insomnia. 

  ## Contributing
  Contributions are welcome! Please reach out using the information in the **Questions** section below. 

  ## Tests
  I used Insomnia to test the routes. This is demonstrated in the walkthrough video. 

  ## License 

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

  [MIT License](https://opensource.org/licenses/MIT)

  ## Questions
  Please reach out with any additional questions: 
  - [GitHub](https://github.com/haleynicole126)
  - Email: haleynicole126@gmail.com



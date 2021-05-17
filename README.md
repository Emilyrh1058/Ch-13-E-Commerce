# Ch-13-E-Commerce


## Table of Contents
-   [Description](#description)
-   [Demo](#demo)
-   [Installation](#installation)
-   [Test Instructions](#tests)
-   [Questions](#questions)

## Description
This application allows the user to manipulate the database as needed for their e-commerce business.

## Demo
See a walk-through video explaining the functionality of this application [here.](https://drive.google.com/file/d/1yvtIUuxpyk2d5I8kSCOQvdMmQxBtmOlA/view?usp=sharing)

## Installation
As seen in the walk-through video above, the user must first have npm installed. A quick way to ensure all necessary dependencies are properly installed is to run the following command into the terminal: npm install express sequelize mysql2

## Test Instructions
To test the functionality of this application the user must follow these steps:

  1. Ensure the database is sourced and seeded by:
      1. running mysql -u root -p in the terminal
      2. Input password and hit enter
      3. type source db/schema.sql to connect the schema 
      4. Type quit to end the mysql session
  2. Type npm run seed to seed the database with testable data
  3. Type npm start into the terminal to start the server
  4. Open Insomnia and at the top, location the dropdown menu for GET, POST, PUT, DELETE, etc.
  5. Use mentioned tabs query box for manipulating the database 
  6. 


## Questions
Should you have any further questions regarding this application please feel free to contact me via [GitHub](https://github.com/Emilyrh1058/Ch-10---Team-Profile-Generator) or [email](mailto:emilyrh1058@gmail.com).
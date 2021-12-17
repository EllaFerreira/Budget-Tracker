# Budget-Tracker 💰 

![License](https://img.shields.io/github/license/EllaFerreira/Note-Taker)
![Inquirer](https://img.shields.io/badge/Package-Dotenv-red.svg)
![MySQL](https://img.shields.io/badge/AppWith-MySQL-purple.svg)
![Nodejs](https://img.shields.io/badge/AppWith-NodeJS-blue.svg)
![Express](https://img.shields.io/badge/AppWith-ExpressJS-orange.svg)

## About this Project

## Mock up

![mockup]()

[walkthrough video]()

## Content

- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Technologies](#technologies)
- [Installation](#Installation)
- [Sources](#sources)
- [Project Creator](#project-creator)

## User Story
```
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

```
## Acceptance Criteria
```
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.
```


## Technologies

- Node/Express js - backend;
- JavaScript;
- Sequelize;
- Insomnia - to GET routes;
- Console.table npm package;
- Mysql2 npm package;
- Inquirer npm package;
- Dotenv;

## Installation
If you want to run this locally on your machine:

- Clone to your local machine from this repo.
- Open the repo in your code editor (vs code for example)
- Open with F12 the command-line.
- Run `npm install` on the terminal to install the packages, when it's done,
- Run `mysql -u root -p` to connect to the database,
- Also using the command-line now run `SOURCE db/schema.sql` to create the tables, 
- After you create the tables quit the db, now you have to populate it run `node seeds/index`.
- Finally run `node server` to run the express server application.

**Testing endpoints with Insomnia**


## Sources

- [Express](https://expressjs.com/en/starter/hello-world.html)
- [MySQL2](https://www.npmjs.com/package/mysql2)
- [Sequelize](https://www.npmjs.com/package/sequelize)
- [Routes](https://www.katalon.com/resources-center/blog/api-testing-tips/)

## Project Creator

[EllaFerreira](https://github.com/EllaFerreira)

© 2021 Budget Tracker. All rights reserved
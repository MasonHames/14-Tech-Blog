# Tech-Blog

A CMS-style where developers can publish their blog posts and comment on other developers' posts.

## DESCRIPTION

A tech blog application where developers can create an account; view blog posts; create, update, and delete posts; comment on other devevlopers' posts; and read others' comments.

The application follows the MVC paradigm in its architectural structure, uses Handlebars.js as the templating language, Sequelize as the ORM, and the expres-session npm package for authentication.

## TABLE OF CONTENTS

- [DESCRIPTION](#description)
- [INSTALLATION](#installation)
- [USAGE](#usage)
- [LICENSE](#license)
- [CONTRIBUTING](#contributing)
- [TESTS](#tests)
- [TECHNOLOGIES USED](#technologies-used)
- [LINKS](#links)
- [QUESTIONS](#questions)

## INSTALLATION

1. Fork the repository from GitHub to your profile.
2. Clone the repository down to your local machine in command-line using: `git clone`.
3. Node.js is required to run this application. Click [here](#installing-nodejs) for instructions on installing Node.js.
4. Install the required dependices to your cloned directory in command-line using: `npm install`

   - Or install the packages individually...
     - Install [express](https://www.npmjs.com/package/express) to your cloned directory in command-line using: `npm install express`.
     - Install [mysql2](https://www.npmjs.com/package/mysql2) to your cloned directory in command-line using: `npm install --save mysql2`
     - Install [dotenv](https://www.npmjs.com/package/dotenv) to your cloned directory in command-line using: `npm install dotenv`
     - Install [sequelize](https://www.npmjs.com/package/sequelize) to your cloned directory in command-line using: `npm install sequelize`
     - Install [connect-session-sequelize](https://www.npmjs.com/package/connect-session-sequelize) to your cloned directory in command-line using: `npm install connect-session-sequelize`
     - Install [express-handlebars](https://www.npmjs.com/package/express-handlebars) to your cloned directory in command-line using: `npm install express-handlebars`
     - Install [express session](https://www.npmjs.com/package/express-session) to your cloned directory in command-line using: `npm install express-session`
     - Install [bcrypt](https://www.npmjs.com/package/bcrypt) to your cloned directory in command-line using: `npm install bcrypt`

   ###### Installing Nodejs

   1. Check if you already have Node.js in command-line by typing `node`.
   2. If you have Node.js on your machine, a message similar to `Welcome to Node.js` will appear.
   3. If you do not have Node.js, an error message will appear and you need to download it.
   4. To download Node.js, click [here](https://nodejs.org/en/download/).
   5. After download and installation is complete, restart your command-line terminal and redo step 1 to confirm a successful installation.
   6. After Node.js is on your local machine, return to the [installation](#installation) instructions for this project's application above.

## USAGE

_If cloned down to your computer..._

1. Add an .env file with your MySQL username, database name, and MySQL password.
2. Navigate to the directory of the application in your terminal using `cd`, if not already there.
3. If you haven't already, be sure you followed all [installation](#installation) instructions to install node, express, dotenv, express-handlebars, express-session, connect-session-sequelize, brcypt, sequelize and mysql2 dependencies.
4. Create your database by running the schema.sql file (right-clicking on the schema file and selecting Run MySQL Query).
5. Seed your database in CLI using: `npm run seed`.
6. Initialize the application in CLI using: `npm start`.
7. Go to https://localhost:3001 to visit application

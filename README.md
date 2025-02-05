# module14challenge
Solved code for the module 14 challenge

## Project Link
https://module14challenge-irad.onrender.com

## Description
This project solves the challenge for Module 14 with JWT, Express, React, Postgres and Typescript. It uses JWT to autenticate an user to the stie, which is a Kanban project board.

## Usage
1. Open the link to the deployed project: https://module14challenge-irad.onrender.com
2. Click the "login" button on the top right of the page.
3. In the login screen, you may use any of the following users:
   
     | Username      |  Password     |
     | ------------- |:-------------:|
     | FrozenBlossom |  password     | 
     | JollyGuru     |  password     |
     | SunnyScribe   |  password     | 
     | RadiantComet  |  password     |

4. Click on "Submit Form"
5. If logging is correct, you will be able to see a kanban board.

## Images

An image of the login screen (user is not authenticated):
![login_no_token](https://github.com/user-attachments/assets/da917ed5-51bb-4f37-b695-cae7a7809003)

An image of a logged in user, with a token on local storage:
![user_logged_in](https://github.com/user-attachments/assets/f2c6dd9d-f037-4f99-90ce-2c6b88b4762f)


## Installation
In order to use the package ou may need to install NPM packages with:

  npm i

Then you may want to insert data for testing purposes on the postgres db (kanban_db) with:

  npm run seed

To run a local test, run the following command: npm run dev:start (The start script runs "npm run build && node dist/index.js")

## Credits
Fabian Saldierna.

## License
An MIT standard license was used. You may refer to it from the repo.

## Features
Implemented JWT authorization with npm package "jwt-decode".

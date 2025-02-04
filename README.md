# module14challenge
Solved code for the module 14 challenge

Project Link


Description
This project solves the challenge for Module 14 with JWT, Express, React, Postgres and Typescript. It uses JWT to autenticate an user to the stie, which is a Kanban project board.

Installation
In order to use the package ou may need to install NPM packages with:

  npm i

Then you may want to insert data for testing purposes on the postgres db (kanban_db) with:

  npm run seed

Usage
To run a local test, run the following command: npm run dev:start (The start script runs "npm run build && node dist/index.js")

Credits
Fabian Saldierna.

License
An MIT standard license was used. You may refer to it from the repo.

Features
Implemented JWT authorization with npm package "jwt-decode".

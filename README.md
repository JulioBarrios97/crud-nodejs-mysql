# CRUD Node.js and MySQL

This is a basic CRUD (Create, Read, Update, Delete) application built using Node.js and MySQL. It allows users to perform CRUD operations on a MySQL database using a web interface.

## Installation

1. Clone the repository
2. Install the dependencies by running `npm install`
3. Configure the MySQL database in `src/config/db.config.js`
4. Run the application using `npm run start`

## Dependencies

This application uses the following dependencies:

- **ejs** - A simple templating language that lets you generate HTML markup with plain JavaScript.
- **express** - A popular Node.js framework for building web applications.
- **morgan** - A middleware that logs HTTP requests in the terminal.
- **mysql2** - A MySQL library for Node.js that provides a fast, efficient, and reliable way to interact with MySQL databases.

## Usage

Once the application is up and running, you can access it by navigating to `http://localhost:3000` in your web browser. From there, you can add, edit, and delete records in the MySQL database.

## Scripts

This application provides the following npm scripts:

- **dev** - Runs the application in development mode with automatic reloading.
- **start** - Runs the application in production mode.

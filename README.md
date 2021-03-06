# E-Commerce

## Description

This application involved building the back end for an e-commerce site. A working Express.js API was taken and configured to use Sequelize to interact with a MySQL database. The below details the acceptance criteria.


## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Running Application

- First update the .env file with your db info

- Open a mysql terminal to run the schema.sql file in order to create the database

- Open an integrated terminal from the server.js level of the file/folder structure
- Seed the database with

```sh
node ./seeds/index.js
```

- Start the Server with

```sh
node server.js
```

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia:

![In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](./Assets/13-orm-homework-demo-01.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:

![In Insomnia, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](./Assets/13-orm-homework-demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia:

![In Insomnia, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](./Assets/13-orm-homework-demo-03.gif)



## Walkthrough Video

A walkthrough video of the application functionality was created.  The video can be seen by following the link below.

[Video Link](https://drive.google.com/file/d/1SuZFH0kKswb-Qmhj3jT65HfuwpYsIMKm/view) 
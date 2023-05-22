# e-commerce-backend

## Description
For e-commerce sites that need a backend using the latest technologies, I have used a functional Express.js API and configured it to interact with a SQL database. Users of this backend application are able to login with their MySQL username and password in an environment variable file. The development database is seeded with test data. 

Upon invoking the application, users are able to view all categories, products, and tags, as well as create, delete, or update categories, products, and tags. 

![ecomm gif-min](https://github.com/miamreid/e-commerce-backend/assets/124822025/4488b4df-1d81-4154-88cb-caa055c6ac6d)


## Usage
To use this application:

1. Clone the repo
2. Enter MySQL username and password to the environment variable file
3. Enter schema and seed commands to connect the database and add testing data
4. Start the server
5. Use Insomnia to POST, PUT, DELETE, CREATE, and GET routes

-- [Link to Demo](https://drive.google.com/file/d/1XPuCGYdAXtfiwgSekAKijShtTOxjMx5b/view)<br />
-- [View the Repo](https://github.com/miamreid/e-commerce-backend)


## User Story
AS A manager at an internet retail company<br />
I WANT a back end for my e-commerce website that uses the latest technologies<br />
SO THAT my company can compete with other e-commerce companies<br />

## Acceptance Criteria
GIVEN a functional Express.js API<br />
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file<br />
THEN I am able to connect to a database using Sequelize<br />
WHEN I enter schema and seed commands<br />
THEN a development database is created and is seeded with test data<br />
WHEN I enter the command to invoke the application<br />
THEN my server is started and the Sequelize models are synced to the MySQL database<br />
WHEN I open API GET routes in Insomnia Core for categories, products, or tags<br />
THEN the data for each of these routes is displayed in a formatted JSON<br />
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core<br />
THEN I am able to successfully create, update, and delete data in my database

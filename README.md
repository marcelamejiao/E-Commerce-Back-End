# E-Commerce-Back-End

### **This project was created as a web application to manage an E-commerce API, using Node.js, Express.js, Sequelize, and MySQL.** 

### **This web application was developed for a manager at an internet retail company that needs a back end for an e-commerce website that uses the latest technologies, giving the company a plus to compete with other e-commerce companies.**

## **Local set up**

### Create your database in MySQL using the provided schema.sql

Run this in your MySQL console
```
source db/schema.sql
```

### Now set up the application in your terminal

#### Configure your local environment

Create your .env file
```
cp .env.EXAMPLE .env
```

... then fill in your .env file with your Database Credentials

#### Install dependencies
```
npm install
```

#### Create the database tables and seed them
```
npm run seed
```

#### Launch the application
```
npm run start
```

## **How to use the application**

* A user can add a database name, MySQL username, and MySQL password to an environment variable file to connect to a database using Sequelize.

* When the user enters the schema and seed commands a development database is created and is seeded with test data.

* The user can use a command to invoke the application, the server is started and the Sequelize models are synced to the MySQL database.

* The user can open API GET routes in Insomnia for categories, products, or tags and the data for each of these routes is displayed in a formatted JSON.

* The API POST, PUT, and DELETE routes in Insomnia, helps the user to be able to successfully create, update, and delete data in the database.


### **Preview**

💡 Walkthrough video: [https://drive.google.com/file/d/1RewDG4ugqrR6G6oZ9GwN4bJfvJY98w76/view?usp=sharing](https://drive.google.com/file/d/1RewDG4ugqrR6G6oZ9GwN4bJfvJY98w76/view?usp=sharing)

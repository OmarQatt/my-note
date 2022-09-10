# SQL database, ORM, Sequelize

What's the difference between SQL  and NoSQL?


SQL is the programming language used to interface with relational databases. (Relational databases model data as records in rows and tables with logical
links between them).
NoSQL is a class of DBMs that are non-relational and generally do not use SQL

What is Sequlize and how to use it with Node js?
Sequelize is an Object Relational Mapper for Node.js. Sequelize lets us connect to a database and perform operations without writing raw SQL queries.
It abstracts SQL queries and makes
it easier to interact with database models as objects.

Installation of Sequelize:

Configuring database.js 

```
// Include Sequelize module
const Sequelize = require('sequelize')

// Creating new Object of Sequelize
const sequelize = new Sequelize(
	'DATABASE_NAME',
	'DATABASE_USER_NAME',
	'DATABASE_PASSWORD', {

		// Explicitly specifying
		// mysql database
		dialect: 'mysql',

		// By default host is 'localhost'		
		host: 'localhost'
	}
);

// Exporting the sequelize object.
// We can use it in another file
// for creating models
module.exports = sequelize

```
What is an ORM, how does it work, and how should I use one?

An ORM (Object Relational Mapper) is a piece/layer of software that helps map your code Objects to your database.

An ORM library is a completely ordinary library written in your language of choice that encapsulates the code needed to manipulate the data, so you don't use SQL anymore;
you interact directly with an object in the same language you're using.

How does ORM work?
ORMs create a model of the object-oriented program with a high-level of abstraction. In other words, it makes a level of logic without the underlying details of the code.
Mapping describes the relationship between an object and the data without knowing how the data is structured. The model can then be used to connect the application with 
the SQL code needed to manage data activities.
This “plumbing” type of code does not have to be rewritten, saving the developer a tremendous amount of time.

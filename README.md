NodeRestful
Node js user authentication rest api using mysql and express js

Install Node JS and MySQL Software, create a database and exeucte the SQL query.

<code> CREATE DATABASE node-app
 
CREATE TABLE users (
  id int(11) NOT NULL AUTO_INCREMENT,
  name varchar(50) COLLATE utf8mb4_unicode_ci NOT NULL,
  email varchar(50) COLLATE utf8mb4_unicode_ci NOT NULL,
  password varchar(200) COLLATE utf8mb4_unicode_ci NOT NULL,
  PRIMARY KEY (id),
  UNIQUE KEY email (email)
 ) ENGINE=InnoDB AUTO_INCREMENT=4 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_unicode_ci; </code>


Go to terminal or command line.

Execute following commands to run this application.

Start Project

$ mkdir node js mysql auth rest api

$ cd mkdir node js mysql auth rest api

$ npm install

$ npm install express express-validator mysql body-parser jsonwebtoken bcryptjs cors --save

Open your browser

http://localhost:3000/api/register
Tutorial: Create a User Authentication RESTful API using NodeJS Express and MySQL Database


##POST

http://localhost:3000/api/register

http://localhost:3000/api/login

http://localhost:3000/api/get-user


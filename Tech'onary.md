# Words groups

##### Database: [ DCL, DDL, DML, DQL, FK, PK, SQL, TCL ]

##### Web: [ HTTP, HTTPS ]

##### Development: [ API, Interface ]



# Tech'onary



## A

##### API - Application Programming Interface

> API stands for Application Programming Interface, which is, basically, an application that connects two different points (for instance, a front-end client with a database).



## D

##### Database

> A database is a structure that stores organized information in tables, which are objects with fields that define the structure in which the information will be stored.

##### DCL - Data Control Language

> The DCL consists of the SQL commands which deals with permissions and privileges of the database.

> The only two DCL commands are GRANT and REVOKE.

##### DDL - Data Definition Language

> The DDL consists of the SQL commands which deals with database schemas, defining the structure of the objects.

> The most common DDL commands are CREATE, ALTER and DROP.

##### DML - Data Manipulation Language

> The DML consists of the SQL commands which deals with the manipulation of the data present within the database's tables.

> The main DML commands are INSERT, UPDATE and DELETE.

> There is no absolute consensus about the DQL commands existence. Therefore, most of the development community defines the SELECT as a DML command.

##### DQL - Data Query Language

> The DQL consists of the SQL commands which deals with data fetching from the database.

> The only DQL command is SELECT.

> There is no absolute consensus about it's existence. Most of the development community defines the SELECT as a DML command.



## F

##### FK - Foreign Key

> On SQL databases, a foreign key is a column or a group of columns that provides a link between two tables, using a reference of a table's primary key on another one.



## H

##### HTTP - HyperText Transfer Protocol

> The HyperText Transfer Protocol is a stateless protocol used to transfer data over the web. Being stateless means that each command is executed independently, without any acknowledge of previous commands.
>

> The protocol uses a request-response system, in which a request is made and a response is returned, both of them with headers containing crucial information about the command.

##### HTTPS - HyperText Transfer Protocol Secure

>The HyperText Transfer Protocol Secure, as the name suggests, is an implementation strategy of HTTP in which the data is encrypted and then transferred over a secure connection.

>The encryption is bidirectional, done both on client and server sides. The protocol ensures that the client is the only one who can decode the information coming from the server.



## I

##### Interface

> A point in which two subjects meet and interact. The term can be used on multiple contexts, but it usually means the same thing (adapted to the presented context).



## P

##### PK - Primary Key

> On SQL databases, a primary key, also known as ID (identification), is a set of one or more columns whose combined values define each row's identification, which makes them always unique (a primary key value will never appear on multiple rows). Therefore, only one primary key composition is allowed by table.

> When the primary key is composed by a single column, that column value will always be unique. For instance: if the ID column's type is numerical and the first row's ID value is zero (0), there will be no other rows with the value zero (0) as it's ID.

> When the primary key is composed, it's the whole combination of the values that can never be repeated. For instance: if there are two numerical columns (A and B) composing the table's ID and the first row's ID values are zero (0) on the A column and one (1) on the B column, there will be no other rows with the same values as it's ID. However, there can be one more row with the values one (1) on the A column and zero (0) on the B column, since the combination [0, 1] differs from the combination [1, 0].



## S

##### SQL - Structured Query Language

> SQL is a language designed for the manipulation of data held in relational databases.



## T

##### TCL - Transaction Control Language

> The TCL consists of the SQL commands which deals with the changes done with DML commands within the database.

> The main TCL commands are COMMIT, ROLLBACK and SAVEPOINT.
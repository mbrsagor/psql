# psql
> This is PSQL database basic command line here. If you if want to learn aobut `PSQL` you may follow the tutorial.
###### Open database using terminal.
` psql postgres`

###### How to create database?
`CREATE DATABASE db_name;`

###### How to show list of database?
`\l`

###### Switch/connection database form shell.
` \c db_name`

###### Drop database.
`DROP DATABASE db_name;`

###### How to create table?
```
CREATE TABLE student (
id INT,
first_name VARCHAR(50),
last_name VARCHAR(50),
email VARCHAR(75),
created_at DATE);
```
Then show table `data` using `\d`

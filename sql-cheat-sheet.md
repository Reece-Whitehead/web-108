# How to login into mysql from terminal
## mysql -u username -p

# How to SHOW USERS
## show USERS;

# How to CREATE USERS
## CREATE USER 'Reece'@'localhost' IDENTIFIED BY 'password';

# How to GRANT PRIVILEGES, Show granted privileges and remove.
## GRANT typeofprivilege ON nameofdatabase.nameoftable TO 'Reece'@'localhost' IDENTIFIED BY 'password';
## SHOW GRANTS FOR 'Reece'@'localhost';
## REVOKE typeofprivilege ON nameofdatabase.nameoftable FROM 'Reece'@'localhost';

# How to SHOW, DELETE & CREATE DATABASES & SELECT DATABASES
## SHOW GRANTS FOR 'Reece'@'localhost';

# How to CREATE a TABLE with Columns and their data types
## CREATE TABLE nameoftable (
##    column1 datatype1,
##    column2 datatype2,
##    column3 datatype3,
##    etc...
## );

# How to SHOW, DELETE & DROP Tables
## SHOW DATABASES;
## CREATE DATABASE nameofdb;
## DROP DATABASE nameofdb;

# How to Insert ROWS & RECORDS (single and multiple)
## INSERT INTO nameoftable (column1, column2, etc...) VALUES (value1, value2, ...);

# INSERT INTO nameoftable (column1, column2, etc...) VALUES
## (value1_1, value2_1, etc...),
## (value1_2, value2_2, etc...),
## etc...;

# How to SELECT with the WHERE Clause
## SELECT * FROM nameoftable WHERE condition;

# How to SELECT with the WHERE Clause using a range
## SELECT * FROM nameoftable WHERE column BETWEEN value1 AND value2;

# How to DELETE an individual ROW
## DELETE FROM nameoftable WHERE condition;

# How to UPDATE a ROW
## UPDATE tablename SET column = newvalue WHERE condition;

# How to add a new column and modify it
## ALTER TABLE nameoftable ADD COLUMN newcolumn datatype;
## ALTER TABLE nameoftable MODIFY COLUMN column newdatatype;

# How to Order by and use Distinct
## SELECT DISTINCT column FROM nameoftable ORDER BY column;

# How to Concatenate Columns
## SELECT CONCAT(COLUMN1, ' ', COLUMN2) AS concantonatedcolumn FROM nameoftable;

# How to Select Distinct Rows
## SELECT DISTINCT * FROM nameoftable;

# How to use LIKE to Search
## SELECT * FROM nameoftable WHERE column LIKE 'pattern';

# How Select using IN
## SELECT * FROM nameoftable WHERE column IN (value1, value2, etc...);

# How to Create & Remove Index (I added multiple kinds not sure what you wanted)
## CREATE INDEX index_name ON table_name (column_name);
## CREATE UNIQUE INDEX index_name ON table_name (column_name);
## CREATE INDEX index_name ON table_name (column1, column2, ...);

## DROP INDEX nameofindex ON nameoftable;
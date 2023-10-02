# G2_DBMS
# EXP NO 1: DATA DEFINITION LANGUAGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.
## DDL(Data Defintion Language)
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.

## list of DDL commands:
```
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers). 
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed
RENAME: This is used to rename an object existing in the database.
```
## Query:
## 1) Create a table student with the following fields name,rollno,age,address,email.
## SQL QUERY:
```
create table student(name char(50),rollno numeric(5),age numeric(5),address varchar(100),email varchar(100));
```
## OUTPUT:
![Screenshot 2023-10-02 124237](https://github.com/swetha1510/G2_DBMS/assets/120623583/fc85e821-1206-4c7a-9aba-b43dd1351a61)

## 2)Change the above student table by adding another attribute department:
## SQL QUERY:
```
 alter table student add department char(10);
```
## OUTPUT:
![Screenshot 2023-10-02 124255](https://github.com/swetha1510/G2_DBMS/assets/120623583/8518e97a-5c06-48bb-9283-b7b6301934e8)

## 3)  Delete the student table using truncate keyword:
## SQL QUERY:
```
 truncate table student;
```
## OUTPUT:
![Screenshot 2023-10-02 125023](https://github.com/swetha1510/G2_DBMS/assets/120623583/6435a8bd-33de-415c-a121-fcf226ada19f)

## 4) Rename the student table to student_list:
## SQL QUERY:
```
alter table student rename to student_list;
```
## OUTPUT:
![Screenshot 2023-10-02 125037](https://github.com/swetha1510/G2_DBMS/assets/120623583/3f7b8724-13e1-43f3-a909-e3898c13184b)

## 5) Drop the student table:
## SQL QUERY:
```
drop table student_list;
```
## OUTPUT:
![Screenshot 2023-10-02 130049](https://github.com/swetha1510/G2_DBMS/assets/120623583/126a3fc1-cce0-455a-8803-444ba0ba1e7b)

## RESULT:
Thus a student database has been created and DDL queries are executed successfully.











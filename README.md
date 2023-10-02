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
## 1) Create a table student with the following fieds rollno,name,age,address,phoneno.
## SQL QUERY:
```
create table student(rollno numeric(5),name char(50),age numeric(5),address varchar(100), phoneno numeric(10));
```
## OUTPUT:
![Screenshot 2023-10-02 131405](https://github.com/swetha1510/G2_DBMS/assets/120623583/43aeaa17-8b8d-4947-8b5d-c109edccda05)

## 2)Change the above student table by adding another attribute department:
## SQL QUERY:
```
 alter table student add department char(10);
```
## OUTPUT:
![Screenshot 2023-10-02 131952](https://github.com/swetha1510/G2_DBMS/assets/120623583/49500c6b-5bad-4d9a-8fda-6a4bcb438b82)

## 3) Drop the student table:
## SQL QUERY:
```
drop table student;
```
## OUTPUT:
![Screenshot 2023-10-02 131752](https://github.com/swetha1510/G2_DBMS/assets/120623583/d2d94d48-f3fa-4502-8ec5-04dec39170f6)


## 4)  Delete the student table using truncate keyword:
## SQL QUERY:
```
 truncate table student;
```
## OUTPUT:
![Screenshot 2023-10-02 125023](https://github.com/swetha1510/G2_DBMS/assets/120623583/6435a8bd-33de-415c-a121-fcf226ada19f)

## 5) Rename the student table to mystudent:
## SQL QUERY:
```
 alter table student rename to mystudent;
```
## OUTPUT:
![Screenshot 2023-10-02 131413](https://github.com/swetha1510/G2_DBMS/assets/120623583/75505e97-1a87-47da-9153-140bdf60f5bb)

## RESULT:
Thus a student database has been created and DDL queries are executed successfully.











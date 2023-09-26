###AIM:
To create a student database and execute DDL queries using SQL.

###DDL (Data Definition Language)
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
###List of DDL commands:
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers). DROP: This command is used to delete objects from the database. ALTER: This is used to alter the structure of the database. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed. RENAME: This is used to rename an object existing in the database.
###Query:
###1) Create a table student with the following fieds rollno,name,age,address,phoneno.
###SQL QUERY:
```
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);
```
###OUTPUT:
![image](https://github.com/Aishwarya-sankar/F2_DBMS/assets/121418444/c516cf00-e076-477a-9e3f-fc96cb70ce13)


###2) Change the above student table by adding another attribute department
###SQL QUERY:
```
alter table student add department char(30);
```
###OUTPUT:
![image](https://github.com/Aishwarya-sankar/F2_DBMS/assets/121418444/79c63449-c055-406d-83e8-74ed34677d50)


###3) Drop the student table
###SQL QUERY:
```
drop table student;
```
OUTPUT:
![image](https://github.com/Aishwarya-sankar/F2_DBMS/assets/121418444/c1d5fae3-3d7c-49bb-bdef-5f4600e52f6b)


###4) Delete the student table using truncate keyword
###SQL QUERY:
```
truncate table student;
```
###OUTPUT:
![image](https://github.com/Aishwarya-sankar/F2_DBMS/assets/121418444/d7bc937a-eb45-4c37-82ec-065b8f711d2a)


###5) Rename the student table to mystudent
###SQL QUERY:
```
alter table student rename to mystudent;
```
###OUTPUT:
![image](https://github.com/Aishwarya-sankar/F2_DBMS/assets/121418444/b8c02028-6945-421c-9735-08aa18f697ed)


###RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.

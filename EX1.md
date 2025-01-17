# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
## Date:
## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);
```
### OUTPUT:
![image](https://github.com/Aishwarya-sankar/F2_DBMS/assets/121418444/0a408222-71e9-489b-9a1c-e2018c96e9f2)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(30);
```
### OUTPUT:
![image](https://github.com/Aishwarya-sankar/F2_DBMS/assets/121418444/d89fc1a6-0255-4e24-be57-d4a2bdbdb88e)


### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;
```

### OUTPUT:
![image](https://github.com/Aishwarya-sankar/F2_DBMS/assets/121418444/cda2e0c8-50d6-49e1-be64-1db873059e4c)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student;
```

### OUTPUT:
![image](https://github.com/Aishwarya-sankar/F2_DBMS/assets/121418444/321cfd54-fbd4-4ad7-800b-55ab4eda33e1)



### 5) Rename the student table to mystudent

### SQL QUERY: 
```
alter table student rename to mystudent;
```

### OUTPUT:
![image](https://github.com/Aishwarya-sankar/F2_DBMS/assets/121418444/5c0207cf-d846-4bf2-a771-788ccaed64e5)
### RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.

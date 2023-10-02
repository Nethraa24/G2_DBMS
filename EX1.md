# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

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
create table student_table(Roll_no numeric(10) , Name varchar(20) , Age numeric(3), Address varchar(20) , Phone_no numeric(10));

Inserting rows 

query : insert into student_table values ( 1, 'Kothai' , 18 , 'Porur' , 9176977202);

### OUTPUT:
![image](https://github.com/KothaiKumar/G2_DBMS/assets/121215739/7b63cb2e-de07-4117-95db-b1524892b19b)

![image](https://github.com/KothaiKumar/G2_DBMS/assets/121215739/97d92fa5-e61c-4d8e-8f22-f0d18c94490a)

![image](https://github.com/KothaiKumar/G2_DBMS/assets/121215739/bb2d1fed-4072-46e9-8efc-ff1941c4e501)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
alter table student_table 
add Email varchar(100);

### OUTPUT:
![image](https://github.com/KothaiKumar/G2_DBMS/assets/121215739/972f6cf4-62bb-491f-b159-8e1680cb882f)


### 3) Drop the student table
 
### SQL QUERY: 
Drop table student_tabel;

### OUTPUT:
![image](https://github.com/KothaiKumar/G2_DBMS/assets/121215739/078d4170-b7a9-45fa-874b-c950f8dea9ec)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
Truncate table student_table2;

### OUTPUT:
![image](https://github.com/KothaiKumar/G2_DBMS/assets/121215739/e1a3853e-8769-44c8-95c8-d3825398ec06)



### 5) Rename the student table to mystudent

### SQL QUERY: 
alter table student3
rename to mystudent;

### OUTPUT:
![image](https://github.com/KothaiKumar/G2_DBMS/assets/121215739/767b16f4-b9e6-44e9-b9e9-9cdb5ca2af03)

### RESULT:
Thus , a student database is created and DDL queries are executed in SQL.

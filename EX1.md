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

query : insert into student_table values ( 1,'Nethraa' , 19 , 'Korattur' , 9176977202);

### OUTPUT:
![image](https://github.com/KothaiKumar/G2_DBMS/assets/121215739/7b63cb2e-de07-4117-95db-b1524892b19b)

![image](https://github.com/Nethraa24/G2_DBMS/assets/121215786/18c59065-16cd-4a0d-9ee1-bb6b0d1789c4)

![image](https://github.com/Nethraa24/G2_DBMS/assets/121215786/b671b976-2386-4b92-b331-cbbe99dcbf43)

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
Truncate table student_table1;

### OUTPUT:
![image](https://github.com/Nethraa24/G2_DBMS/assets/121215786/d1640a18-5734-4d97-b6e6-9e82bc1e99c8)


### 5) Rename the student table to mystudent

### SQL QUERY: 
alter table student_table2
rename to mystudent;

### OUTPUT:
![image](https://github.com/Nethraa24/G2_DBMS/assets/121215786/4385d082-3a67-4dd1-9cb3-550cf67a2bf6)

### RESULT:
Thus, a student database is created and DDL queries are executed in SQL successfully.

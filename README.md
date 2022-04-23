# gloffyassignment

Beloe schema and tables need to be created on mysql.
create database demo9; --Create Schema 

create table Loginforadminstration(
name varchar(20) not null,
USERID int PRIMARY KEY NOT NULL AUTO_INCREMENT ,
mobile int(50) not null,
email varchar(50) not null,
password varchar(50) not null
); -- create registration table

create table book (book_id int PRIMARY KEY NOT NULL AUTO_INCREMENT, book_name varchar(255) not null,
  author varchar(255), price int , qnty int); -- create book table 
  
  #
  
 

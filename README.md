# Multi-Threaded-Client-Server-Model
It is a python based Client Server model that supports multi-threading.
You need to create a mySQL database first with database name : "client_server" and table name "records".

Table can be made through this code:
create table records(id int primary key auto_increment,name varchar(30),pass varchar(30),email varchar(30),age varchar(5))

# Steps to run:
1) type "python server2.py" in command prompt first.
2) type "python client.py" in command prompt.

Note: Kepp in mind to change the directory in command prompt that holds these files.

Since it supports multi-threading, you can open upto five client.py files simultaneously.
 

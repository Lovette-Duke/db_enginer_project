# db_enginer_project
This is the capstone project of the META Database Engineer course

### Description
This repository contains the necessary instructions to set up a MySQL database for Little Lemon Restaurant, how to create and call stored procedures using a connection pool in Python with MySQL database and instructions for Little Lemon's analysis and sales report.

The provided code creates and configures tables for MenuItems, Menus, Bookings, Orders, and Employees, and populates them with sample data, creates stored procedures, named "PeakHours" and "GuestStatus",designed to perform specific tasks related to Little Lemon Restaurant and provides details on how to establish a connection pool, insert data into the Bookings table, create reports, and display upcoming bookings on the kitchen screen.

### Prerequisites
Before running the code, ensure that you have the following:

Python installed on your machine MySQL server installed on your machine MySQL Connector/Python library installed (you can install it using pip install mysql-connector-python) Database Setup Establish a connection between Python and MySQL using the MySQL Connector/Python library. Provide the appropriate username and password for your MySQL server.

Create a cursor object to communicate with the MySQL database.

Drop the existing database (if it exists) and create a new one called "little_lemon".

Set the "little_lemon" database for use.

Create tables for MenuItems, Menus, Bookings, Orders, and Employees using SQL queries. Each table has its own set of columns and data types, defined in the SQL queries.

Execute the SQL queries using the cursor.execute() function to create the tables in the "little_lemon" database.

Commit the changes to the database using connection.commit().

Optionally, you can populate the tables with sample data using INSERT statements in SQL queries, executed with cursor.execute().

Close the cursor and connection using cursor.close() and connection.close() respectively.

### Usage
After setting up the MySQL database, you can use it to store and manage data related to Little Lemon Restaurant. You can interact with the database using Python and MySQL Connector/Python library, by writing custom code to perform CRUD (Create, Read, Update, Delete) operations on the tables.

For example, you can use Python to insert new menu items, retrieve menus, book tables, place orders, manage employee data, and perform other operations as needed for the restaurant's daily operations as demostrated in the project.

### Conclusion
Setting up the MySQL database using the provided code allows you to create and manage a database for Little Lemon Restaurant, enabling efficient storage and retrieval of data related to menu items, menus, bookings, orders, and employees, and provides detailed instructions for various tasks related to Little Lemon.

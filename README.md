# Mini Project: Bookstore Management System

### Scenario

You are hired as a database administrator for a local bookstore. The bookstore needs a system to manage their inventory, track sales, and keep customer information. They have requested you to create and manage a database for this purpose.

### Objectives

1. **Create Database and Tables:**
    - Create a database named `BookstoreDB`.
    - Create the following tables with appropriate data types and constraints:
        - `Customers`: CustomerID (Primary Key), FirstName, LastName, Email, PhoneNumber, BirthDate.
        - `Books`: BookID (Primary Key), Title, Author, Genre, Price, StockQuantity.
        - `Sales`: SaleID (Primary Key), CustomerID (Foreign Key), BookID (Foreign Key), SaleDate, Quantity, TotalAmount.
2. **Insert Data:**
    - Insert at least 5 records into the `Customers` table.
    - Insert at least 10 records into the `Books` table with varied genres.
    - Insert at least 10 records into the `Sales` table with different sale dates and quantities.
3. **Queries:**
    - Write a query to retrieve all customer records.
    - Write a query to find all books in the "Fantasy" genre.
    - Write a query to list sales made in the last month.
    - Write a query to find the total sales amount for each customer.
    - Write a query to update the stock quantity of a specific book.
    - Write a query to delete a sale record based on the sale ID.

### Deliverables

1. SQL script file containing:
    - Creation of the `BookstoreDB` database.
    - Creation of the `Customers`, `Books`, and `Sales` tables.
    - Insertion of sample data into the tables.
    - The required queries.
2. A brief report explaining:
    - The structure of your database.
    - The reasoning behind your table design.
    - Any challenges you faced during the project. 

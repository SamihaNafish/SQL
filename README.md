# DBMS Project

This repository contains a Database Management System (DBMS) project. The project is divided into two parts: Part 1 involves inserting data into multiple tables, and Part 2 consists of various queries to manipulate and retrieve data.

## Project Structure

### Part 1: Data Insertion

1. **Customer Table**: Insert customer details.
2. **Employee Table**: Insert employee information.
3. **ArtWorks Table**: Insert details about artworks.
4. **Orders Table**: Insert order data.
5. **Vehicle Table**: Insert vehicle details.
6. **Shipment Table**: Insert shipment information.
7. **SalesRep Table**: Insert sales representative data.
8. **Driver Table**: Insert driver information.
9. **Assign Table**: Insert data for assignments of drivers to orders.

### Part 2: Data Queries

1. **List Customer Details**: List all customer names, addresses, and phone numbers.
2. **Order Information**: Retrieve detailed information about a specific order.
   - **Order Header**: Includes order number, sales rep name, customer account, customer name, billing address, and delivery address.
   - **Order Lines**: Includes furniture ID, description, quantity, and unit price.
3. **SalesRep Phone Number**: Retrieve the phone number of the sales representative who took a specific order.
4. **Driver Customer List**: List all customers whose orders have been delivered by a specific driver.
5. **Total Stock Value**: Calculate the total value of all items in stock with unit prices exceeding $25.

## Requirements

- A SQL-compatible database management system (such as MySQL, PostgreSQL, or SQLite).
- Basic understanding of SQL commands for data manipulation and querying.

## Usage

1. **Insert Data**:
   - Use the SQL scripts provided in `part1_insert_data.sql` to insert the initial data into the tables.

2. **Run Queries**:
   - Use the SQL queries provided in `part2_queries.sql` to perform the various data retrieval and manipulation tasks.

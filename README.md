# Sales Management System

A SQL Server project to manage sales data for small businesses, featuring:
- Relational database design
- SQL queries for analysis and reporting
- Basic ETL process implementation

## Database Design (ERD)

- Customers (CustomerID, CustomerName, Email, Phone)
- Products (ProductID, ProductName, Price, Stock)
- Orders (OrderID, CustomerID, OrderDate)
- OrderDetails (OrderDetailID, OrderID, ProductID, Quantity)

## Files

- `SalesDB_Script.sql`: Database creation and sample queries
- `ETL_Script.sql`: ETL example to load new products
- `README.md`: Project overview

## Tools Used

- Microsoft SQL Server
- SQL Server Management Studio (SSMS)

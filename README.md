Created a database and tables to manage a simple e-commerce system. 
The system has three tables: customers, orders, and products.
Requirements:

Create a database named ecommerce.
Create three tables: customers, orders, and products.
Insert some sample data into the tables.

Table Structure:

customers
id (primary key, auto-increment): unique identifier for each customer
name: customer's name
email: customer's email address
address: customer's address

orders
id (primary key, auto-increment): unique identifier for each order
customer_id (foreign key referencing customers.id): a customer who placed the                               order
order_date: date the order was placed
total_amount: total amount of the order

products
id (primary key, auto-increment): unique identifier for each product
name: product's name
price: product's price
description: product's description



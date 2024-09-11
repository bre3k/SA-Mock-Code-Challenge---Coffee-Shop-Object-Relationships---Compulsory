# COFFEE SHOP

# Project Overview
This project implements an Object-Oriented Programming (OOP) model for a Coffee Shop system in Python. The main entities are:

Coffee: Represents a type of coffee.
Customer: Represents a customer in the shop.
Order: Represents an order placed by a customer for a specific coffee.
This project focuses on understanding object relationships, properties, and methods in Python, following best OOP practices.

# Repository Setup
1. Clone the Repository to local machine

2. Installing Dependencies

# CLASSES AND METHODS

1. Customer
Properties:
name: Customer's name (1-15 characters)
Methods:
orders(): Returns a list of all orders placed by the customer.
coffees(): Returns a unique list of all coffees ordered by the customer.
create_order(coffee, price): Creates a new order for the customer.
most_aficionado(coffee): Returns the customer who has spent the most on a given coffee.

2. Coffee
Properties:
name: Coffee's name (min. 3 characters)
Methods:
orders(): Returns all orders for the coffee.
customers(): Returns unique customers who ordered the coffee.
num_orders(): Returns the number of orders for the coffee.
average_price(): Returns the average price of the coffee based on its orders.

3. Order
Properties:
customer: Returns the associated Customer object.
coffee: Returns the associated Coffee object.
price: Returns the price of the order (must be between 1.0 and 10.0).
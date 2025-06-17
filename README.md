# Order Management API Exercise

# Problem statement

A retailer company is looking to develop an order management system to streamline their order processing and product management. 

Your task is to build an API that handles customer orders, processes them, and stores the information in the system. 
Additionally, the system should provide capabilities to generate reports about ordered products.

# Requirements

**Hint**: Some requirements are open-ended, so you can implement them in a way that you think would be most convenient for the system user. 

## Functional
* As a retailer, I can **create** new **products**. Each product should have a **name** and **price**.
* As a retailer, I can retrieve a **list** of **products**. It should be possible to perform **search** by product **name**.
* As a retailer, I can **apply discount** for a **product**. Discount has two settings: **percentage** value of discount and **minimum quantity of products** that must be purchased for the discount to apply.
* As a retailer, I can **create** new **orders** with a list of products. Each product should have a **quantity** of items ordered.
* As a retailer, I can retrieve a **list** of **orders**.
* As a retailer, I can retrieve an **order invoice**. The invoice should contain a list of products where each product has a **name**, **quantity**, **discount (%)** (if applicable), **amount** ($), and additionally show the **total amount** ($) to pay for all products.
* As a retailer, I can retrieve **reports** for each **discounted product**. The report should show the discounted product **name**, **discount (%)**, **number of orders** that include this discounted product, and **total amount** ($) ordered of this discounted product.

## Non-Functional
* The system should use a **persistence layer** (`Mongo` or `Postgres`).
* The API should not accept **invalid requests**.
* Include prerequisites and steps to launch in the **README**.
* The solution code must be in a **git repository**.
* The solution should be implemented using **.NET** (ideally `LTS`).

## Bonus points stuff
* Automated tests.
* RESTful API.
* Think about performance considerations (e.g., the system over time will have a large number of orders).
* API Documentation generated from code (hint - `swagger`).
* Containerization/deployment (hint - `docker compose`).
* Code is structured using some known architecture (e.g., NTier, Onion, etc.).
* Continuous integration (CI).
* Progress of your work (hint - `commits strategy`).
* Comments/thoughts on the decisions you made.

# Time for solution

Take as long as you need on the solution, but we suggest limiting yourself to 8 hours. Do let us know how much time it took you!

The task is not made to be completed in the period of 8 hours, and no one expects you to! However, knowing how much time you spent and seeing the solution you came up with allows us to see what you prioritize and where you would consider cutting corners on a sharp deadline.

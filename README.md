# order-management-exercise

# Problem statement

A retailer company is looking to develop an order management system to streamline their order processing and products management. 

Your task is to build an API that handles customer orders, processes them, and stores the information in the system. 
Additionaly system should provide capabilities to do reports about ordered products.

# Requirements

**Hint**: Some requirements are open ended so you can implement them in a way that you think would be most convinient for the system user. 

## Functional
* As a retailer I can **create** new **product**. Each product should have **name** and **price**.
* As a retailer I can retrieve **list** of **products**. It should be possible to perform **search** by product **name**.
* As a retailer I can **apply discount** for **product**. Discount has two settings: **percentage** value of discount and **quantity of products** from which discount will be applied.
* As a retailer I can **create** new **order** with list of products. Each product should have **quantity** of items ordered.
* As a retailer I can retrieve **list** of **orders**.
* As a retailer I can retrieve **order invoice**. Invoice should contain list of products where `each product` has **name**, **quantity**, **discount (%)** (if applicable), **amount** ($) and additionally show **total amount** ($) to pay for `all products`.
* As a retailer I can retrieve **reports** for each **discounted product**. Report should show `discounted product` **name**, **discount (%)**, **number of orders** that includes this discounted product and **total amount** ($) ordered of this discounted product.

## Non-Functional
* System must use some kind of **persistence layer**.
* Ensure that user can send only **valid requests** to API.
* Include prerequisites and steps to launch in README.
* The solution code must be in a git repository.
* The solution should be implemented using .NET (ideally LTS).

## Bonus points stuff
* Automated tests.
* RESTful API.
* Think about performance considerations (e.g.: system overtime will have big number of orders).
* API Documentation generated from code (hint - `Swagger`).
* Containerization/deployment (hint - `Docker compose`).
* Code is structured using some known architecture (e.g.: NTier, Onion, etc.).
* Comments/thoughts on the decisions you made.

# Time for solution

Take as long as you need on the solution but we suggest to limit yourself at 8 hours. Do let us know how much time it took you!

The task is not made to be completed in the period of 8 hours and no one expects you to! However, knowing how much time you spent and seeing the solution you came up with allows for seeing what you prioritize and where you would consider cutting corners on a sharp deadline.

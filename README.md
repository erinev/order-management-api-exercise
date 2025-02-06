# order-management-exercise

# Problem statement

A retailer company is looking to develop an order management system to streamline their order processing and inventory management. 

Your task is to build an API that handles customer orders, processes them, and stores the information in a database. 
Additionaly system should provide periodical reports about customer orders.

# Requirements

**Hint**: Some requirements are open ended so you can implement them in a way that you think would be most convinient for the system user.

## Functional
* As a retailer I can **create** new order with list of items. Items should have **quantity** and **price**.
* As a retailer I can **retrieve list** of orders.
* As a retailer I can **retrieve single** order.
* As a warehouse worker I can **update** order **status** in the following sequence `new-> in progress -> completed`
* As a retailer I can **retrieve reports for completed orders**. Report should show **total** items **quantity** and **amount** per **customer**. 

## Non-Functional
* **Reports** should be **updated** **periodically** (every 2 minutes)
* Ensure that user can send only **valid requests** to API
* Include prerequisites and steps to launch in README
* The solution code must be in a git repository
* The solution should be implemented using .NET (ideally LTS)

## Bonus points stuff
* **REST**ful API
* Documentation generated from code (hint - Swagger)
* Automated tests
* Containerization/deployment (hint - Docker compose)
* Think about performance considerations
* Comments/thoughts on the decisions you made

# Time for solution

Take as long as you need on the solution but we suggest to limit yourself at 8 hours. Do let us know how much time it took you!

The task is not made to be completed in the period of 8 hours and no one expects you to! However, knowing how much time you spent and seeing the solution you came up with allows for seeing what you prioritize and where you would consider cutting corners on a sharp deadline.

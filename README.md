# SQL-Project

## Overview 
This project is based upon a digital music store database and includes SQL queries to answer business questions to aid in optimization. 
### Query 1
The first query answers the question of the top 5 albums currently in stock and which genres they are. Three tables are joined to gather the necessary data: _album_, _track_, and _genre_. The results are then ordered in descending order to reveal the album with the most in stock within the store. 
### Query 2
The second query is focused on the top 5 genres with the most available tracks in the store's inventory. *Rock* is the leading genre with 1,297 of 3,503 total tracks within the store. The tables _genre_ and _track_ are used to achieve the result. 
### Query 3
The third query focuses on customers with the highest invoice totals. The highest total across all customers is about $50.00. The _invoice_ and _customer_ tables are joined based on the __customerID__ field to gather this information. 
### Query 4
The fourth and final query reveals how many customers are assisted by each customer support representative. The _employee_ and _customer_ tables are joined and grouped by the employee's first and last name, and the customer's support rep ID. 

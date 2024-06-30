🍕 ***Pizza Sales Analysis Project***

**Overview**
Welcome to the Pizza Sales Analysis project! This repository is dedicated to showcasing a comprehensive SQL analysis of pizza sales data. The project is structured to address 13 analytical questions ranging from basic to advanced complexity. Each question is designed to demonstrate SQL proficiency and data analytical skills that are crucial for understanding business insights and driving data-informed decisions.

**Project Objectives**
The primary goal of this project is to:
*  Demonstrate SQL querying skills across different levels of complexity.
*  Extract meaningful insights from a simulated pizza sales dataset.
*  Provide a detailed showcase of SQL capabilities to potential employers.

**Dataset Description**
The dataset used in this analysis simulates a pizza sales environment. It includes various tables representing orders, customers, pizzas, and sales transactions, which collectively allow for in-depth exploration and analysis.

***Analytical Questions***

**Basic Level**
1. Retrieve the total number of orders placed:
*  This query calculates the overall count of orders in the dataset.
*  Skills demonstrated: Basic SQL SELECT and COUNT functions.

2. Calculate the total revenue generated from pizza sales:
*  This query sums up the total sales amount across all orders.
*  Skills demonstrated: Aggregation using SUM().

3. Identify the highest-priced pizza:
*  This query finds the pizza with the maximum price.
*  Skills demonstrated: Use of MAX() function and ORDER BY clause.

4. Identify the most common pizza size ordered:
*  This query determines which pizza size has been ordered the most.
*  Skills demonstrated: GROUP BY and COUNT() for frequency analysis.

5.List the top 5 most ordered pizza types along with their quantities:
*  This query lists the five pizzas that have been ordered the most, along with their order counts.
*  Skills demonstrated: LIMIT clause, ORDER BY for ranking results.

**Intermediate Level**

6. Join the necessary tables to find the total quantity of each pizza category ordered:
*  This query combines tables to sum the quantities of each pizza category.
*  Skills demonstrated: JOIN operations and SUM() aggregation.
  
7. Determine the distribution of orders by hour of the day:
*  This query analyzes the orders based on the time of day they were placed.
*  Skills demonstrated: Date and time functions, GROUP BY for hourly distribution.

8. Join relevant tables to find the category-wise distribution of pizzas:
*  This query identifies the distribution of pizzas across different categories.
*  Skills demonstrated: Advanced JOIN operations, GROUP BY category.

9. Group the orders by date and calculate the average number of pizzas ordered per day:
*  This query groups orders by date and calculates the daily average of pizzas ordered.
*  Skills demonstrated: DATE functions, AVG() aggregation.
  
10. Determine the top 3 most ordered pizza types based on revenue:
*  This query ranks pizzas by their contribution to total revenue and lists the top three.
*  Skills demonstrated: Revenue calculation, ORDER BY with LIMIT.

**Advanced Level**

11. Calculate the percentage contribution of each pizza type to total revenue:
*  This query calculates the revenue percentage each pizza type contributes to the overall sales.
*  Skills demonstrated: Window functions, percentage calculation using SQL.

12. Analyze the cumulative revenue generated over time:
*  This query computes the cumulative revenue over the period of data collection.
*  Skills demonstrated: Cumulative sum with window functions, time-series analysis.

13. Determine the top 3 most ordered pizza types based on revenue for each pizza category:
*  This query identifies the top three pizzas in terms of revenue within each category.
*  Skills demonstrated: Complex GROUP BY operations, ranking within categories using SQL.

**Technical Details**
*Tools and Technologies*
*  MySQL: The relational database management system used for data storage and querying.
*  SQL Workbench: A graphical interface for executing SQL queries and managing the database.
*  SQLTools in Visual Studio Code: A plugin for running SQL queries directly within VS Code.

**SQL Techniques Demonstrated**
*  Basic SQL Commands: SELECT, WHERE, COUNT, SUM, MAX, GROUP BY.
*  Advanced SQL Features: JOINs, window functions, subqueries, and time-series analysis.
*  Aggregation and Ranking: Using GROUP BY, ORDER BY, and LIMIT to extract insights.
*  Date and Time Functions: Extracting and manipulating time-based data.

**Repository Structure**
*  queries/: Contains SQL scripts for each question, organized by complexity.
*  basic/: Scripts for basic questions.
*  intermediate/: Scripts for intermediate questions.
*  advanced/: Scripts for advanced questions.
*  data/: Includes the dataset (CSV or SQL dump) used for the analysis.
*  results/: Contains the results and visualizations generated from SQL queries.
*  README.md: This file, providing an overview and detailed information about the project.
  
**Getting Started**
*Prerequisites*
* MySQL: Ensure MySQL is installed on your system.
* SQL Workbench or VS Code with SQLTools: Recommended for running and managing SQL queries.

**Setup Instructions**

*Clone this repository:*

Click on the "File" menu and select "Clone repository...".
In the window that appears, select the "URL" tab.
Paste the URL of the repository (https://github.com/MAAYAA-MOH/SQL---PIZZA-SALES-ANALYSIS-PROJECT.git) into the input field.
Choose the local path where you want to clone the repository.
Click "Clone".
OR
Copy this code
git clone https://github.com/yourusername/pizza-sales-analysis.git
Import the dataset into your MySQL database. Refer to the data/ directory for the SQL dump file.
Open SQL Workbench or VS Code with SQLTools and connect to your MySQL database.
Navigate to the queries/ directory and execute the SQL scripts according to the level of complexity you are interested in.

**Running the Queries**
* For basic queries, navigate to the basic named files
* For intermediate queries, go to the intermediate named files
* For advanced queries, explore the advanced named files.
Each script can be executed independently to observe the results.

**Contribution**
Contributions to this project are welcome! If you have suggestions for improvements or additional questions, please fork the repository and submit a pull request.

**License**
This project is licensed under the MIT License. See the LICENSE file for more details.

**Contact**
For any inquiries or feedback, please contact me at angel.purnimatripathi@gmail.com.
Contributions to this project are welcome! If you have suggestions for improvements or additional questions, please fork the repository and submit a pull request.


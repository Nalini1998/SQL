Here's an example README.md for the provided SQL queries:

# Trends in Startups

This project involves analyzing the `startups` table that contains data on some of the biggest names in the startup industry. The goal is to use SQL queries with aggregate functions to extract some interesting insights about these companies.

## Data

The data is contained in a `project.sqlite` file which has a table called `startups` covering information about the companies.

To get started, the following queries were executed:

- `SELECT COUNT(*)` to calculate the total number of companies in the table
- `SELECT SUM(valuation)` to calculate the total value of all companies in this table
- `SELECT MAX(raised)` to identify the highest amount raised by a startup
- `SELECT MAX(raised) WHERE stage="Seed"` to find the maximum amount of money raised, during the 'Seed' stage
- `SELECT MIN(founded)` to determine the year the oldest company on the list was founded
- `SELECT AVG(valuation)` to obtain the average valuation of the companies
- `SELECT category, AVG(valuation)` to retrieve the average valuation in each category
- `SELECT category, ROUND(AVG(valuation),2)` to display the average valuation in each category, rounded to two decimal places
- `SELECT category, ROUND(AVG(valuation),2) ORDER BY 2 DESC` to order the average valuation in each category from highest to lowest
- `SELECT category, COUNT(*) HAVING COUNT(*) > 3` to filter and include only categories that have more than three companies
- `SELECT location, AVG(employees)` to find the average size of a startup in each location
- `SELECT location, ROUND(AVG(employees),0) HAVING AVG(employees) > 500` to determine the average size of a startup in each location, with more than 500 employees.

The insights acquired from the queries can help Technology Crunch readers understand the current trends in the startup world.

#### **This project was completed by [Nalini Vo](https://github.com/Nalini1998)
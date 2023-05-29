<p align = "center"><img src='https://github.com/mohan-kartik/Bird-Strike-Analysis-in-SQL/assets/42971268/628088f6-8327-467b-b3c7-a60521c6cf88'>

## Overview
Build a database that can be used to analyze bird strikes based on data fetched from [FAA](https://data.world/hhaveliw/data-visualization-bird-strike]).  

## Objectives:
- build a logical data model,
- realize the relational schema in MySQL, 
- load data into the database, 
- execute analytical SQL queries, 
- performed some visualization of the data
- build a stored procedure

## Tasks
- Set up and configure a MySQL Server 

- Create the database schema described below:
  - Create a table called "incidents" to store wildlife strike incidents with the provided schema.
  - Create a table called "airports" to store airport and state information with the provided schema.
  - Link the "incidents" and "airports" tables using foreign key constraints.
  - Create a lookup table called "conditions" with the provided schema.
  - Create a table called "airlines" to store airline information with the provided schema.
  - Link the "incidents" and "airlines" tables using foreign key constraints.
  
- Populate the tables in the database with the data 

- Perform Data Analysis
  - Create a SQL query to find the 10 states with the greatest number of incidents.
  - Create a SQL query to find the airlines with an above-average number of bird strike incidents.
  - Create a SQL query to find the number of bird strike incidents by month and by flight phase.

-  Visualize the data
  - Build a scatter plot that plots month along the x-axis versus the number of incidents (across all airlines and flight phases).

- Create a stored procedure in MySQL that adds a new incident to the database.




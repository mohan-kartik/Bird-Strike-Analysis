# Bird Strike Analysis
Build a database that can be used to analyze bird strikes based on data fetched from [FAA](https://data.world/hhaveliw/data-visualization-bird-strike]).  

## Objectives:
- a logical data model,
- realized the relational schema in MySQL, 
- loaded data into the database, 
- executed analytical SQL queries, 
- and finally performed some simple visualization of the data

## Tasks
Before starting the project, make sure to read all the questions and inspect the CSV data file to understand its structure.





Create a table called "incidents" to store wildlife strike incidents with the provided schema.
Create a table called "airports" to store airport and state information with the provided schema.
Link the "incidents" and "airports" tables using foreign key constraints.
Create a lookup table called "conditions" with the provided schema.
Create a table called "airlines" to store airline information with the provided schema.
Link the "incidents" and "airlines" tables using foreign key constraints.
Add code chunks to test the table definitions without evaluation.
Load Data into the Database (20 pts / 8 hrs)
Download the bird strikes CSV data file and place it in the same folder as your R Notebook.
Load the CSV data into a dataframe called "bds.raw" in R.
Populate the tables in the database with the data from the appropriate columns using the provided table definitions.
Map the values in the data file to appropriate values in the lookup tables.
Verify that the data loading worked by displaying parts of each table.
Perform Data Analysis (3 pts / 1 hr)
Create a SQL query to find the 10 states with the greatest number of incidents.
Create a SQL query to find the airlines with





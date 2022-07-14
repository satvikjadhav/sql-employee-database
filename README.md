# sql-employee-database

## Description

It is a beautiful spring day, and it is two weeks since you have been hired as a new data engineer at Pewlett Hackard. Your first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.

I have designed the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data. In other words, perform:
1. Data Engineering
2. Data Analysis

### Data Modeling
Inspect the CSVs and sketch out an ERD of the tables. Feel free to use a tool like http://www.quickdatabasediagrams.com.

### Data Engineering
- Setting up the appropriate enviornment using Docker so that this project can be replicated on any machine
- Use the information you have to create a table schema for each of the six CSV files. There are several variables to be specified such as data types, primary keys, foreign keys, and other constraints.
- For the primary keys has to be unique in each column, otherwise create a composite key. Which takes to primary keys in order to uniquely identify a row.
- Create tables in the correct order to handle foreign keys

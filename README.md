# Data and Schema Setup

## Overview
This project sets up a relational company database in MariaDB. It covers creating the database and tables (the schema), inserting sample data, and checking the result with SELECT queries.

## Tools Used
- MariaDB
- HeidiSQL
- SQL

## Database Structure
The `company_db` database contains three related tables:

| Table | Rows | Description |
|-------|------|-------------|
| `companies` | 4 | Company details |
| `departments` | 10 | Departments linked to companies |
| `employees` | 30 | Employees linked to departments |

## What's Inside
- Creating the database and tables with `CREATE DATABASE` and `CREATE TABLE`
- Defining columns, data types and keys
- Loading sample data with `INSERT`
- Verifying the data with `SELECT *`

## How to Run
1. Open HeidiSQL and connect to your MariaDB server.
2. Open `SQL.sql` (File → Load SQL file).
3. Click **Execute** (or press F9) to create the tables and insert the data.
4. Run `SELECT * FROM employees;` to check the result.

## Key Learnings
- Designing tables that relate to each other (companies → departments → employees)
- Choosing suitable data types for each column
- Setting up a database from scratch with a script that can be re-run

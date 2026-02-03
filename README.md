# LINQ to SQL Query Examples (C#)

This project contains a set of unit tests demonstrating how common SQL queries can be expressed using LINQ on in-memory collections in C#.

The examples are based on classic database structures (`Emp`, `Dept`, `Salgrade`) and show how SQL concepts such as filtering, joins, grouping, subqueries, and aggregations can be implemented using LINQ.

## Covered SQL Concepts
- WHERE filtering
- ORDER BY
- JOIN and multi-table joins
- GROUP BY and aggregations (COUNT, AVG)
- Subqueries (IN, correlated subqueries)
- Projections (SELECT)
- BETWEEN conditions

## Data Source
Test data is provided by helper methods:
- `Database.GetEmps()`
- `Database.GetDepts()`
- `Database.GetSalgrades()`

## Technologies
- C#
- LINQ
- xUnit (unit tests)

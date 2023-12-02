---
title: How to Teach People SQL
mata_title: How to Teach People SQL web book
description: Learn the mental models of how SQL works with visuals and gifs. This makes SQL intuitive to explain to others in your organization.
book_slug: how-to-teach-people-sql
book_sort_number: 3
authors:
  - _people/matt.md
reviewers:
  - _people/blake.md
cover_image: /assets/images/book-covers/how-to-teach-people-sql.png
thumbnail_cover_image: /assets/images/book-covers/how-to-teach-people-sql@thumbnail.png
image: /assets/images/book-covers/social-teach-sql.png
main_color: "#147638"
is_featured: false
status: released
topics:
  - _chapters/dictionary/sql.md
meta_title: "How to Teach People SQL: Gifs and Visuals for SQL"
snippet: This book will help you empathize with people learning SQL for the first time. It focuses on the areas where most people get stuck or give up. The book then gives visuals and animations to help people build mental models of the abstract processes behind SQL queries.
tags:
  - books
---
## Introduction
- [### Introduction](dataschool/chapters/how-to-teach-people-sql/introduction.md) 
    
    Introduction about why teaching SQL requires understanding of the audience who is less adept at dealing with abstract ideas
    
    
- [### Why Databases?](why-databases.md) 
    
    Databases are better for managing data than spreadsheets when you consider size, accuracy, and security
    
    
- [### Accessing Data](accessing-data.md) 
    
    Accessing data requires permission to the database, asking questions in SQL, and knowing how to explore a schema.
    
    

## JOINs

- [### SQL Join Types Explained Visually](sql-join-types-explained-visually.md) 
    
    Data within a database exists across multiple tables, JOINs allow you to combine datasets into new tables for analysis. Learn more.
    
    
- [### Inner Join - Animated](inner-join-animated.md) 
    
    Visualize how SQL is joining two tables using an Inner JOIN. See animated visualizations of the data being INNER joined in SQL. Learn more.
    
    
- [### Left & Right Join - Animated](left-right-join-animated.md) 
    
    Visualize how SQL is joining two tables using a Left JOIN and a Right JOIN. See animated visualizations of the data being LEFT and RIGHT joined in SQL. Learn more.
    
    
- [### Full Outer Join - Animated](full-outer-join-animated.md) 
    
    Visualize how SQL is joining two tables using a Full Outer JOIN. See animated visualizations of the data being FULL OUTER joined in SQL. Learn more.
    
- [### Union - Animated](union-animated.md) 
    
    Visualize how SQL is joining two tables using a Union All join. See animated visualizations of the data being Unioned in SQL. Learn more.
    
- [### Cross Join - Animated](cross-join-animated.md) 
    
    Visualize how SQL is joining two tables using a Cross Join. See animated visualizations of the data being CROSS JOINed in SQL. Learn more.
    
    

## Debugging

- [### Syntax Errors](debugging-sql-syntax-errors.md) 
    
    Learn the most common reasons for SQL errors due to syntax. Spelling errors, Quotation marks, Capitalization, Data Types, and more.
    
    
- [### 0 Rows Returned](debugging-sql-0-rows-returned.md) 
    
    Learn the most common reasons you will get 0 rows returned from your SQL query. See how JOINs and over filtering may be the problem.
    
    

## Advanced

- [### How Aggregations Work](how-sql-aggregations-work.md) 
    
    Visualize how SQL aggregates data by viewing examples of COUNT, AVG, and SUM. See animations showing each step of the SQL query.
    
    
- [### How Subqueries Work](how-sql-subqueries-work.md) 
    
    Visualize how subqueries work in SQL by seeing the intermediate table that is created during the process. See animations showing each step of the SQL query.
    
    
- [### How CASE WHEN Works](how-case-when-works.md) 
    
    CASE WHEN is a SQL function that works a lot like IF THEN in other programming languages. Learn to use CASE WHEN in SQL.
    
    
- [### How Window Functions Work](how-window-functions-work.md) 
    
    Learn how window functions work by looking at gifs that show the process in slow motion. See every step in SQL animated in slow motion. Learn more.
    
    

## Appendix

- [### Difference between WHERE and ON in SQL](difference-between-where-and-on-in-sql.md) 
    
    Understand how filtering and joining can be done in both the ON and WHERE clauses in SQL. Choose the best strategy for JOINing data in SQL.
    
    
- [### How to Find Outliers with SQL](how-to-find-outliers-with-sql.md) 
    
    Find Outliers quickly with SQL. Detect outliers using simple ORDER BY techniques and using inter quartile range. Learn more.
    
    
- [### How Regex in SQL Works](how-regex-works-in-sql.md) 
    
    Learn how Regex works in SQL and how to use it in your queries. See the Regex process visualized in gifs. Learn more.
    
    
- [### Syntax Conventions](syntax-conventions.md) 
    
    Learn the most important syntax conventions and styles to writing SQL
    

- [### Third Normal Form _(In progress)_](third-normal-form.md) 
    
    Learn why data is stored in third normal form in a SQL database
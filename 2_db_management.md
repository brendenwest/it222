# Week 2 - Database Management

### Reading
- https://www.freecodecamp.org/news/learn-supabase-open-source-firebase-alternative/
- https://www.splunk.com/en_us/blog/learn/data-normalization.html 
- https://supabase.com/docs/guides/database/tables
- SQL for Data Analytics, [Ch. 2](https://learning.oreilly.com/library/view/sql-for-data/9781801812870/B17466_02_ePub.xhtml), [Ch. 6](https://learning.oreilly.com/library/view/sql-for-data/9781801812870/B17466_06_ePub.xhtml)

### Reference
- https://dbeaver.io/

### Learning Outcomes

- Defining a relational DB 
- Creating a PostgreSQL database in Supabase
- Database normalization
- Access control in PostgreSQL
- Importing data into PostgreSQL
- Tools for managing relational DBs

### Database Normalization

Normalization is a technique for structuring database tables to 
- reduce data duplication
- ensure data consistency
- improve data organization

Normalization takes

- **1st Normal Form (1NF)** - Table values must be atomic (can't be reduced to simpler values)
- **2nd Normal Form (2NF)**
  - 1NF is satisfied
  - All non-key columns depend on the table's primary key
  - often results in new tables but reduces data duplication
- **3rd Normal Form (3NF)** 
  - 2NF is satisfied
  - No transitive dependencies

### Relational DB Tools

You can choose from among a wide range of tools for administering PostgreSQL databases. Some popular and well-supported choices are:

- [psql](https://www.postgresql.org/docs/current/app-psql.html) - psql is a terminal-based front-end to PostgreSQL. It enables you to type queries interactively, issue them to PostgreSQL, and see the query results. psql also provides meta-commands and various shell-like features to facilitate writing scripts and automating a wide variety of tasks.
- [pgAdmin](https://www.pgadmin.org/) - pgAdmin is a popular and feature rich open-source administration and development platform for PostgreSQL.
- [DBeaver](https://dbeaver.io/) - DBeaver Community is a free cross-platform database tool for working with data. It supports all popular relational databases like Microsoft SQL Server, MySQL, PostgreSQL, SQLite, and more.

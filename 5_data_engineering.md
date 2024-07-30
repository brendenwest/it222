# Week 5 - Data Engineering

### Reading
- https://www.coursera.org/articles/what-does-a-data-engineer-do-and-how-do-i-become-one
- https://aws.amazon.com/what-is/etl/
- https://app.datacamp.com/learn/courses/introduction-to-data-engineering


### Learning Outcomes
- What is data engineering
- Key tools for data engineering
- What is ETL
- What are data pipelines

### What is Data Engineering

Data engineering is the process of designing and building systems to collect, store, transform, and analyze large amounts of data.

Data engineers focus on building & managing systems to collect and provide useful information for other parts of an organization (e.g. marketing, product planning, data science, etc.)

This can involve processes to acquire data from external sources or move data between internal systems (e.g. from an accounting system to a data science system).

Data engineering involves a mix of skills:
- Data storage design
- Data analysis
- Software programming
- Cloud systems 

### What is ETL

Extract, transform, and load (ETL) is the process of moving data (usually large sets) from one system to another, transforming it in the process to suit the purposes of the target system.

For example, many companies have ETL processes to extract business data from purpose-specific systems (e.g. accounting, inventory, etc.) and transform it for use by other departments that don't `own` the data. 

The ETL processes often involve combining data into a `data warehouse` or `data lake` that provides a unified view of the company's data.

ETL processes are usually automated and run periodically at times that won't impact end users by slowing systems during data migration.
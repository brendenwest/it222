# Week 5 - Data Engineering

### Reading
- https://www.coursera.org/articles/what-does-a-data-engineer-do-and-how-do-i-become-one
- https://aws.amazon.com/what-is/etl/
- https://www.datacamp.com/blog/a-list-of-the-16-best-etl-tools-and-why-to-choose-them
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

### Key Data Engineering Tools

Data engineers use a wide range of general-purpose tools such as relational databases & SQL, cloud services, & Java or Python programming languages.

They also use tools that are purpose-built for data-engineering tasks

- [Apache Airflow](https://airflow.apache.org/) - An open-source platform to programmatically author, schedule, and monitor workflows.
- [Microsoft SQL Server Integration Services -SSIS](https://learn.microsoft.com/en-us/sql/integration-services/sql-server-integration-services) - An enterprise-level platform for data integration and transformation.
- [Talend Open Studio](https://www.talend.com/products/talend-open-studio/) - A popular open-source data integration software that features a user-friendly GUI.
- [Hadoop](https://hadoop.apache.org/) - an open-source framework for processing and storing big data in clusters of computer servers. Considered the foundation of big data and enables the storage and processing of large amounts of data.
- [Apache Cassandra](https://cassandra.apache.org/) - Open-source schema-less distributed database with a hybrid design between a tabular and key-value store, with a `columnar` data model.
- [Apache Spark](https://spark.apache.org/) - A multi-language engine for executing data engineering, data science, and machine learning. Optimized for distributed & `streaming` data processing.
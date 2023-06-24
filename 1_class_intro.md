# Week 1 - Intro to Database Solutions

### Reading
- https://shopify.engineering/five-common-data-stores-usage

### Reference
- https://www.w3schools.com/sql/

### Learning Outcomes
- Data storage overview
- Types of data storage solutions

## Data Storage Overview

Data storage is an essential feature of most software applications.

Application developers can choose from many data storage options and typically need to consider the following:

- **Location** - e.g. local file system, in-memory, remote server
- **Data Structure** - e.g. relational schema, document, key-value
- **Performance** - how quickly can the DB respond to queries?
- **Scalability** - how well can the DB scale for increased load? Can the DB scale `horizontally` across multiple servers?
- **Reliability** - Can the DB backup & restore data? Can it ensure no data is lost?


## Types of Data Stores

### Key-Value 
Key-value data stores are much like large dictionaries where values are accessed by `key`. 

KV data stores often cache data `in-memory` and are ideal for lightweight information that needs to be accessed quickly.

https://redis.io/ is perhaps the most common key-value data store and is widely used by web applications.

### Relational 
Data is organized into tables, with a defined schema for each table. 

The DB may have a relationship, where a row in one table can reference a row in another table.

Data in relational DB's is typically retrieved with SQL (structured query language), a technology-independent language.

There are widely used commercial relational DB systems - e.g. Microsoft SQL Server, Oracle, Google Big Query - as well as open source systems such as SQLite, MySQL, and PostgreSQL.

SQL syntax generally works the same across these various systems, although there are some slight differences to be aware of when developing queries.

Relational databases are popular for business critical applications because they can enforce consistent transactions and generally have good performance & scalability.

### Schema-less (aka NoSQL)
Schema-less databases are used for non-relational data that doesn't conform to a schema.

These include `document` stores, where each record is a semi-structured document (usually JSON or XML). [MongoDB](https://www.mongodb.com/) and [Firebase](https://firebase.google.com/products/realtime-database) are widely used document db's.

Schema-less DB's are useful where data structure is not well defined or might change frequently. 

A wide column store such as [Cassandra](http://cassandra.apache.org/) has similarities with a document store and a relational DB, and is often the basis for `data lake` solutions that involve massive amounts of disparate data.

### Full-text search engine

Full-text search engines are a type of document data store highly optimized for text searching.

These are not designed for transactions and are typically used as a secondary data copy to support certain read-heavy operations. 

Full-text search engines are particularly good at searching & retrieving`denormalized` data that would otherwise require expensive run-time joins in a relational database.

[ElasticSearch](https://www.elastic.co/guide/en/elasticsearch/reference/current/elasticsearch-intro.html) is a commonly used, open source, full-text search engine.

### Message Queue

Message queues are primarily designed to pass data between loosely coupled applications. But message queues store and persist data reliably.

Message queues such as [Kafka](https://kafka.apache.org/) can be highly distributed and have excellent performance for storing very large amounts of high frequency data.
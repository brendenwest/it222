# Week 6 - Intro to Elasticsearch

### Reading
- https://www.elastic.co/what-is/elasticsearch
- https://granulate.io/blog/elasticsearch-use-cases-architecture-6-best-practices/

### Watch
- https://www.elastic.co/webinars/getting-started-elasticsearch

### Learning Outcomes
- What is Elasticsearch
- Benefits & use cases for Elasticsearch
- Elasticsearch API basics
- Full-text search with Elasticsearch 

### What is Elasticsearch?

Elasticsearch is a distributed, open-source data storage engine optimized for full-text search of unstructured data.

Elasticsearch parses, normalizes, and enriches raw data before storing in an `index`.

An Elasticsearch index is a collection of related JSON documents. Each document correlates a set of `keys` (names of fields or properties) with their corresponding `values` (strings, numbers, Booleans, dates, arrays of values, geolocations, or other types of data).

Elasticsearch stores documents in an `inverted index` to make the data searchable in near real-time. An inverted index lists every unique word that appears in any document and identifies all of the documents each word occurs in.

### Why use Elasticsearch?

- **Speed** - Elasticsearch is a near real-time search platform, meaning the latency from the time a document is indexed until it becomes searchable is very short — typically one second.
- **Scale** - Elasticsearch collections are distributed across different, redundant containers known as `shards`. The distributed nature of Elasticsearch allows it to scale out to hundreds (or even thousands) of servers and handle petabytes of data.
- **Denormalized** - Results of complex & performance-intensive SQL queries can be indexed into Elasticsearch documents, allowing for very fast read queries where data changes infrequently
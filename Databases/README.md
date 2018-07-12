# Databases

### Relational Datbases

Relational databases are what most of us are all used to. They have been around since the 70's and you can think about them like spreadsheets!

- Database
- Tables
- Columns
- Rows

| id        | name    | age    | location   |
| --------- |:-------:| :-----:| :--------:  |
| 1         | nigel   | 30     | San Diego  |
| 2         | jim     | 28     | NYC        |
| 3         | betty   | 31     | San Francisco|

**_Relational Databases Examples_**

- SQL Server
- Oracle
- MySQL
- PostgreSQL
- Aurora
- MariaDB

### Non-Relational (NoSQL)

- Database
  - Collection => Table
  - Document => Row
  - Key, Value Pairs => Columns

**_Non Relational Databases Examples_**

```json
{
  "_id": "394ejojaj903091881dnna",
  "name": "nigel",
  "age": 30,
  "location": "San Diego"
}
```

### Data Warehousing

Used for business intelligence. Tools like Cognos, Jaspersoft, SQL Server, Reporting Services, Oracle Hyperion, SAP NetWeaver.

Used to pull in very large and complex data sets. Usually used by management to do queries on data (such as current performance vs targets etc).

### OLTP (Online Transaction Processing) vs. OLAP (Online Analytics Processing)

OTLP differs from OLAP in terms of the types of queries you will run.

**_OLTP Example_**

Used for transactional type queries.

```
Order number: 2120121

Pulls up a row of data such as Name, Date, Address to Deliver to, Delivery Status etc.
```

**_OLAP Example_**

Used for business logic type queries.

```
Net Profit of given product or device
Pulls in large number of records

Sum of products sold in region
Sum of products sold in continent
Unit cost of product in each region
Sales price of each product
Sales price - unit cost
```

Data Warehousing databases use different type of architecture both from a database perspective and infrastructure layer.

### Elasticache

ElastiCache is a web service that makes it easy to deploy, operate and scale an in-memory cache in the cloud. The service improves the performance of web applications by allowing you to retrieve information from fast, managed, in-memory caches, instead of relying entirely on slower disk-based databases.

ElasticCache supports two open-source in-memory caching engines...

1. Memcached
2. Redis
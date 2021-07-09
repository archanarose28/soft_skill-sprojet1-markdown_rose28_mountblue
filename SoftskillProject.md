# **NoSQL**

NoSQL data models allow related data to be nested within a single data structure.

A NoSQL database provides a mechanism for storage and retrieval of data that is modeled in means other than the tabular relations used in relational databases.

## **Why** **NoSQL**
* The pace of development with NoSQL databases can be much faster than with a SQL database.
* The structure of many different forms of data is more easily handled and evolved with a NoSQL database.
* The amount of data in many applications cannot be served affordably by a SQL database.
* The scale of traffic and need for zero downtime cannot be handled by SQL.
* New application paradigms can be more easily supported.


##  **NoSQL Features & Capabilities**

* Performance

* Availability

* Multi-Model

* Concurrency

* Security

* Scalability

* Data Model Flexibility

* Deployment Model Flexibility


## **Types of NoSL Databases**



 

1. **Document Databases**

   A document database stores data in JSON, BSON , or XML documents. In a document database, documents can be nested. Particular elements can be indexed for faster querying. 



   Documents can be stored and retrieved in a form that is much closer to the data objects used in applications, which means less translation is required to use the data in an application. The most widely adopted document databases are usually implemented with a scale-out architecture, providing a clear path to scalability of both data volumes and traffic.

2. **Key-value stores**
  
   The simplest type of NoSQL database is a key-value store.Every data element in the database is stored as a key value pair consisting of an attribute name and a value. In a sense, a key-value store is like a relational database with only two columns: the key or attribute name and the value.

3. **Column-oriented databases** 

   While a relational database stores data in rows and reads data row by row, a column store is organized as a set of columns. This means that when you want to run analytics on a small number of columns, you can read those columns directly without consuming memory with the unwanted data.

   Columns are often of the same type and benefit from more efficient compression, making reads even faster. Columnar databases can quickly aggregate the value of a given column (adding up the total sales for the year, for example). Use cases include analytics.

   

4. **Graph databases**

   A graph database focuses on the relationship between data elements. Each element is stored as a node (such as a person in a social media graph). The connections between elements are called links or relationships. In a graph database, connections are first-class elements of the database, stored directly. In relational databases, links are implied, using data to express the relationships.

   A graph database is optimized to capture and search the connections between data elements, overcoming the overhead associated with JOINing multiple tables in SQL.

   
![types of NoSQL](https://images.app.goo.gl/6H1Wgac6T9BbgL9N7)




## **List of the Different NoSQL Databases**

1. **MongoDB**

MongoDB is the most widely used document-based database. It stores the documents in JSON objects.According to the website stackshare.io, more than 3400 companies are using MongoDB in their tech stack. Uber, Google, eBay, Nokia, Coinbase are some of them.

**Why MongoDB?**
* In case you are planning to integrate hundreds of different data sources, the document-based model of MongoDB will be a great fit as it will provide a single unified view of the data
* When you are expecting a lot of reads and write operations from your application but you do not care much about some of the data being lost in the server crash
* You can use it to store clickstream data and use it for the customer behavioral analysis.

2. **Cassandra**

Cassandra is an open-source, distributed database system that was initially built by Facebook (and motivated by Google’s Big Table). It is widely available and quite scalable.

**Why Cassanda?**
* When your use case requires more writing operations than reading ones
* In situations where you need more availability than consistency. For example, you can use it for social network websites but cannot use it for banking purposes
* You require less number of joins and aggregations in your queries to the database
* Health trackers, weather data, tracking of orders, and time series data are some good use cases where you can use Cassandra databases

3. **ElasticSearch**


This is also an open-source, distributed NoSQL database system. It is highly scalable and consistent. You can also call it as an Analytics Engine. It can easily analyze, store, and search huge volumes of data.

**Why ElasticSearh**
* If your use case requires a full-text search, Elasticsearch will be the best fit 
* If your use case involves chatbots where these bots resolve most of the queries, such as when a person types something there are high chances of spelling mistakes. You can make use of the in-built fuzzy matching practices of the ElasticSearch
* ElasticSearch is useful in storing logs data and analyzing it

4. **Amazon DynamoDB**

It is a key-value pair based distributed database system created by Amazon and is highly scalable. But, it is not open-source.


**Why Amazon DynamoDB**

* In case you are looking for a database that can handle simple key-value queries but those queries are very large in number
* In case you are working with OLTP workload like online ticket booking or banking where the data needs to be highly consistent
5. **HBase**

It is also an open-source highly scalable distributive database system. HBase was written in JAVA and runs on top of the Hadoop Distributed File System (HDFS).

**Why HBase**
* You should have at least petabytes of data to be processed. If your data volume is small, then you will not get the desired results
* If your use case requires random and real-time access to the data, then HBase will be the appropriate option
* If you want to easily store real-time messages for billions of people


## **REFERENCES**


* [Nesta CMS](http://nestacms.com/docs/creating-content/markdown-cheat-sheet )

* [Analytics Vidhya](https://www.analyticsvidhya.com/blog/2020/09/different-nosql-databases-every-data-scientist-must-know/)

* [mongo DB](https://www.mongodb.com/nosql-explained)

* [Geeksforgeeks](https://www.geeksforgeeks.org/introduction-to-nosql/)














# yet-another-etl

PySpark-based ETL framework facilitating loading of data into diverse sources - including SQL, NoSQL, and Streaming Data, expediting efficient data lake setup.

## Prerequisites

## Spark Connections

1. [Clickhouse](https://clickhouse.tech/): An open-source columnar database management system for online analytical processing (OLAP).
2. [Druid](https://druid.apache.org/): An open-source distributed data store designed for real-time analytics on large datasets.
3. [Kafka](https://kafka.apache.org/): An open-source distributed event streaming platform for building real-time data pipelines and streaming applications.
4. [PostgreSQL](https://www.postgresql.org/): An open-source relational database management system.

You can explore these links to learn more about how Spark can connect and interact with these data sources.

## Other
To ensure code quality and formatting, you can use the following commands:

1. Check your Spark application code for style and PEP8 compliance:
    ```bash
   flake8
2. Automatically format your code according to Black's rules:
    ```bash
   black .
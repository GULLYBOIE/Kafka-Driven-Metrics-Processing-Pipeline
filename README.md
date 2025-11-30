Overview
This project implements a real-time data pipeline using Apache Kafka, Python's psutil library for metric collection, and SQL Server for data storage. The pipeline collects metrics data from the local computer, processes it through Kafka brokers, and loads it into a SQL Server database. 

Technologies Used
Python: Utilized the psutil library for collecting metrics data and Kafka Python client for producing and consuming messages.
Apache Kafka: Implemented a distributed streaming platform to handle real-time data processing and communication between producers and consumers.
Apache Zookeeper: Used for coordinating and managing Kafka brokers.
SQL Server: Stored and managed the collected metrics data in a relational database.

The data pipeline consists of the following steps:
Data Collection: Metrics data is collected from the local computer using the psutil Python library.
Data Production: The collected data is sent as messages to Kafka topics through a Kafka producer.
Data Consumption: Kafka consumers read the messages from the topics, process them, and load the data into SQL Server.


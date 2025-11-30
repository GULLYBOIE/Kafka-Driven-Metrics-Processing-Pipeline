This project implements a real-time data pipeline that captures system performance metrics using Python’s psutil library and streams them through Apache Kafka for continuous processing. Metrics are collected from the local machine and published to Kafka topics, enabling a steady flow of telemetry data through a distributed streaming architecture.

Kafka brokers, coordinated by Apache ZooKeeper, handle message distribution between producers and consumers, ensuring reliable and scalable data movement. The consumer layer processes incoming messages and loads the structured data into SQL Server, where it can be queried and analyzed efficiently in a relational format.

The pipeline provides an end-to-end view of system activity, from metric collection to storage, and forms a foundation for real-time monitoring and analytics. This design showcases practical use of event streaming, OLTP data storage, and Python-based automation to build a lightweight yet effective observability workflow.

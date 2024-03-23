# RealTIme-Data-Streaming-Project
In this project, we will construct a comprehensive real-time data streaming pipeline, encompassing every stage from data ingestion to processing and eventual storage. This endeavor will leverage a robust arsenal of tools and technologies, including Apache Airflow, Python, Apache Kafka, Apache Zookeeper, Apache Spark, and Cassandra, all seamlessly containerized using Docker...........


-The project is designed with the following components:

Data Source: We use randomuser.me API to generate random user data for our pipeline.

Apache Airflow: Responsible for orchestrating the pipeline and storing fetched data in a PostgreSQL database.

Apache Kafka and Zookeeper: Used for streaming data from PostgreSQL to the processing engine.

Control Center and Schema Registry: Helps in monitoring and schema management of our Kafka streams.

Apache Spark: For data processing with its master and worker nodes.

Cassandra: Where the processed data will be stored.

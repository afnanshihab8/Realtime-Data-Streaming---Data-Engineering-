# Realtime Data Streaming | End-to-End Data Engineering Project

This project implements a robust data pipeline leveraging a diverse technology stack. It begins by fetching synthetic user data from the 'randomuser.me' API, orchestrated via **Apache Airflow** and stored in **PostgreSQL**. **Apache Kafka**, integrated with **Zookeeper**, enables real-time data streaming, while **Control Center** and **Schema Registry** manage stream governance. **Apache Spark** processes the data, which is then stored in **Cassandra** for high-availability storage. The entire pipeline is containerized with **Docker** for seamless deployment.

## System Architecture
![System Architecture](https://github.com/afnanshihab8/Realtime-Data-Streaming---Data-Engineering-/blob/main/Data%20engineering%20architecture.png)

## Technologies
- **Data Source**:  `randomuser.me` API is used to generate random user data for the pipeline.
- **Apache Airflow**: Helps with orchestrating the pipeline and storing fetched data in a PostgreSQL database.
- **Apache Kafka and Zookeeper**: Used for streaming data from PostgreSQL to the processing engine.
- **Control Center and Schema Registry**: Helps in monitoring and schema management of the Kafka streams.
- **Apache Spark**: Responsible for data processing with master and worker nodes.
- **Cassandra**: Database to store the processed data.
- **Docker**: Containerize the entire pipeline.

## Acknowledgements
Credits to [Yusuf Ganiyu](https://www.linkedin.com/in/yusuf-ganiyu-b90140107/) for this outstanding project. 





# Real-Time Data Streaming Pipeline

## Overview

Welcome to the Real-Time Data Streaming Pipeline project! In this repository, you will find the necessary code and configuration files to build a robust real-time data streaming pipeline. This pipeline covers each phase from data ingestion to processing and finally storage, utilizing a powerful stack of tools and technologies.

## Technologies Used

- **Apache Airflow**: Our workflow orchestrator, ensuring tasks are executed in the right order and with the necessary dependencies.
- **Python**: The primary programming language used for scripting and coding various components of the pipeline.
- **Apache Kafka**: A distributed streaming platform for handling real-time data feeds and event processing.
- **Apache Zookeeper**: A centralized service for maintaining configuration information, naming, providing distributed synchronization, and more.
- **Apache Spark**: A fast and general-purpose cluster computing system for big data processing.
- **Cassandra**: A highly scalable NoSQL database that serves as our storage solution.

## Prerequisites

Before you get started, make sure you have the following prerequisites installed:

- Docker: Used for containerizing our stack.
- Docker Compose: A tool for defining and running multi-container Docker applications.
- Python: Required for various scripting tasks and Airflow.
- Apache Kafka: You may need to install Kafka separately if not using Dockerized Kafka.

## Getting Started

1. Clone this repository to your local machine.

2. Make sure you have Docker and Docker Compose installed.

3. Set up your environment variables and configurations as needed. Refer to the `config` folder for configuration files.

4. Start the Docker containers using `docker-compose up -d`.

5. Access the different components of the pipeline and follow the setup instructions in their respective folders.

6. Start the data ingestion, processing, and storage components as per your use case.

7. Monitor the pipeline and manage workflows using Apache Airflow.

## Directory Structure

The project directory is organized as follows:

- `config`: Configuration files for various components.
- `data_ingestion`: Code and configuration for data ingestion.
- `data_processing`: Code and configuration for data processing.
- `data_storage`: Code and configuration for data storage.
- `docker-compose.yml`: Docker Compose configuration for the entire stack.
- `scripts`: Utility scripts for setup and management.

## Contributing

Contributions to this project are welcome! If you have ideas for improvements or find any issues, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

Special thanks to the open-source communities behind Apache Airflow, Apache Kafka, Apache Zookeeper, Apache Spark, and Cassandra for providing the core technologies that power this real-time data streaming pipeline.

Happy streaming!


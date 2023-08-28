# ingestion

# summary
Recommended List (in order of recommendation)
1. Apache NiFi
2. StreamSets
3. Apache Airflow
4. Luigi

The recommended order is based on the tools' suitability for real-time data processing scenarios, ease of use, flexibility, and compatibility with various data sources and systems. Remember to evaluate each tool based on your specific use case and requirements before making a decision.

## recommendation reason

### 1. Apache NiFi
- Language: Java
- Database Compatibility: Supports various databases and data formats
- Summary: Apache NiFi is a data integration and automation tool that allows you to design and automate data flows between different systems. It offers a user-friendly interface for building complex data pipelines and supports real-time streaming, making it suitable for scenarios requiring data movement, transformation, and processing in real-time.
- Suitability: Highly suitable for real-time data ingestion, transformation, and movement across different systems and sources.
### 2. StreamSets
- Language: Java
- Database Compatibility: Supports various databases and systems
- Summary: StreamSets Data Collector is an open-source data ingestion tool that focuses on simplifying the process of designing and executing data pipelines. It offers real-time monitoring, error handling, and data transformation capabilities, making it a good fit for real-time data integration and ETL scenarios.
- Suitability: Recommended for real-time data movement, transformation, and integration tasks.
### 3. Apache Airflow
- Language: Python
- Database Compatibility: Works with various databases
- Summary: Apache Airflow is a platform for programmatically authoring, scheduling, and monitoring workflows. While it's primarily designed for workflow orchestration, it can be used to manage real-time data pipelines by integrating with streaming technologies and event-driven workflows.
- Suitability: Suited for managing complex workflows that involve real-time components and dependencies.
### 4. Luigi
- Language: Python
- Database Compatibility: Supports various databases
- Summary: Luigi is a Python-based framework for building data pipelines. It's designed to handle batch processing tasks but can be adapted to include real-time components through custom implementations. It's suitable for orchestrating both batch and near-real-time workflows.
- Suitability: Recommended for orchestrating data workflows with real-time and batch processing components.
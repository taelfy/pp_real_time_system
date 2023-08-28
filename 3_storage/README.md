# ingestion

# summary
1. Cassandra
2. MongoDB
3. Neo4j
4. Hadoop HDFS

The recommended order is based on the suitability of each tool for real-time data storage, considering factors such as low-latency access, scalability, and data model requirements. Keep in mind that the best choice depends on your specific use case, data volume, and performance needs.

## recommendation reason

### 1. Cassandra
- Storage Type: NoSQL
- Query Language: CQL (Cassandra Query Language)
- Summary: Cassandra is a highly scalable, distributed NoSQL database designed for handling large volumes of data with low-latency read and write operations. It offers a decentralized architecture and strong partitioning, making it suitable for real-time applications with high throughput and data availability requirements.
- Suitability: Highly suitable for real-time applications that demand low-latency data access, high availability, and horizontal scalability.
### 2. MongoDB
- Storage Type: NoSQL
- Query Language: MongoDB Query Language
- Summary: MongoDB is a flexible document-oriented NoSQL database that excels at handling semi-structured and rapidly changing data. It provides horizontal scalability and supports real-time data processing scenarios with its dynamic schema and rich querying capabilities.
- Suitability: Well-suited for real-time applications involving diverse data types and structures, as well as the need for flexible schema design.
### 3. Neo4j
- Storage Type: Graph
- Query Language: Cypher Query Language
- Summary: Neo4j is a graph database optimized for storing and querying graph data structures. It's ideal for applications that require deep relationships and complex traversals in real-time. Neo4j's strength lies in its ability to model and analyze intricate connections between data points.
- Suitability: Recommended for real-time applications focused on analyzing and visualizing complex relationships among data entities.
### 4. Hadoop HDFS
- Storage Type: Distributed File System
- Query Language: Apache Hive
- Summary: Hadoop HDFS is a distributed file system that is part of the Apache Hadoop ecosystem. It's designed for storing and processing large volumes of data across clusters of commodity hardware. While it's not primarily known for real-time data access, it can be used in scenarios where batch processing and data retention are the primary concerns.
- Suitability: More suitable for batch-oriented data processing and storage compared to real-time use cases.
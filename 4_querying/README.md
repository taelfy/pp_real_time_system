# ingestion

# summary
Recommended List (in order of recommendation)

1. Presto
2. Druid
3. Elasticsearch
4. ClickHouse
5. Pinot

The order of recommendation is based on the tools' performance, query capabilities, and suitability for real-time data processing scenarios. Remember to consider your specific use case and requirements when choosing a query tool.

## recommendation reason

### 1. Presto
- Storage Type: Various (supports various data sources)
- Query Type: Ad hoc queries, data exploration
- Query Language: SQL
- Database Compatibility: Connects to various data sources
- Summary: Presto is a distributed SQL query engine known for its speed and flexibility. It allows querying data from different sources in real-time, making it suitable for interactive exploration and analytics.
- Suitability: Highly suitable for real-time ad hoc querying and exploratory analysis across diverse data sources.
### 2. Druid
- Storage Type: Columnar, Time-series
- Query Type: Real-time analytics, time-series analysis
- Query Language: Druid Query Language (SQL-like)
- Database Compatibility: Built for Druid data stores
- Summary: Druid is designed for sub-second query response times on large datasets, especially for time-series data. It's suitable for scenarios requiring real-time analytics with high-speed queries.
- Suitability: Well-suited for real-time analytics and exploration of event-driven, time-series data.
### 3. Elasticsearch
- Storage Type: Document-oriented, Full-text search
- Query Type: Full-text search, text analysis, structured queries
- Query Language: Query DSL (JSON-based)
- Database Compatibility: Elasticsearch indices
- Summary: Elasticsearch is known for its full-text search capabilities and efficient text analysis. While not primarily a real-time analytics tool, it's suitable for text-based real-time search and analysis.
- Suitability: Recommended for real-time text search and analysis use cases.
### 4. ClickHouse
- Storage Type: Columnar
- Query Type: Analytical queries, aggregation
- Query Language: SQL
- Database Compatibility: Connects to various data sources
- Summary: ClickHouse excels at analytical queries on large volumes of data with high-speed query execution. It's suitable for real-time analytics and querying of columnar data.
- Suitability: Suitable for real-time analytical queries and data analysis tasks.
### 5. Pinot
- Storage Type: Columnar
- Query Type: Real-time analytics, aggregation
- Query Language: PQL (Pinot Query Language)
- Database Compatibility: Built for Pinot data stores
- Summary: Apache Pinot is designed for real-time analytics with low-latency query responses. It's suitable for scenarios requiring fast querying and analysis of streaming and batch data.
- Suitability: Well-suited for real-time analytical queries and processing of large datasets.

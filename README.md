# pp_real_time_system

# Design
![real_time_design.png](./data/images/real_time_design.png)


# ingestion

identify and connect to the data sources that produce the data you want to analyze. These can be various types of sensors, devices, applications, web services, or APIs that generate data continuously or periodically.

## http

In the context of data ingestion relative to real-time processing, HTTP (Hypertext Transfer Protocol) serves as a communication protocol for transmitting data over the internet. A pro of using HTTP for real-time data ingestion is its widespread support and simplicity, allowing rapid integration into various systems. However, a con is that HTTP might introduce higher latency compared to more lightweight protocols, potentially impacting the timeliness of real-time data ingestion due to its inherent overhead in establishing connections and sending headers.

## mqtt

MQTT (Message Queuing Telemetry Transport) is a lightweight messaging protocol commonly used in data ingestion for real-time applications. It enables efficient communication between devices and servers by allowing data to be published and subscribed to in a publish-subscribe model. In this context, MQTT facilitates the seamless and rapid transfer of data from various sources to a central server, making it ideal for real-time data ingestion scenarios such as IoT applications. One advantage of MQTT is its low overhead, enabling quick transmission and reduced bandwidth usage. However, a potential drawback is that MQTT lacks built-in security features, requiring additional implementation to ensure data privacy and authentication.

## kafka

In the realm of data ingestion for real-time processing, Kafka serves as a distributed streaming platform that excels at handling high-throughput, low-latency data streams. It allows data to be ingested from various sources, processed, and delivered in real-time to multiple consumers. A notable advantage of Kafka is its fault-tolerant architecture, ensuring data durability and reliability even in the face of hardware failures. However, one potential drawback is the complexity associated with configuring and managing Kafka clusters, which may require advanced coding skills to fully harness its capabilities.


## flume

Flume is a distributed data ingestion system designed for efficiently collecting and transporting large volumes of streaming data in real-time. As an advanced coder, you'd appreciate that Flume's architecture comprises a source, channel, and sink, allowing you to customize data flows and integrate with various data sources. One advantage is its scalability, enabling parallel processing of data streams and accommodating growing workloads seamlessly. However, a potential drawback is its complexity, which might require a deep understanding of its configuration and components, posing a challenge for newcomers to grasp its intricacies swiftly.




# processing
Process the data as it flows through your system, using a stream processing framework or tool. Stream processing allows you to perform various operations on the data, such as aggregation, enrichment, joining, windowing, or pattern matching, without storing the data in a database or a file system. Stream processing can also handle complex event processing, which involves detecting and responding to events or conditions that occur within the data stream.

# storage
store the data or the results of the stream processing in a suitable data storage system, depending on your use case and requirements. You may want to store the raw data, the processed data, or both, for later analysis or backup purposes. You may also want to store the data in different formats or structures, such as files, tables, documents, or graphs. 

# querying
 query the data or the results of the stream processing using a query engine or tool that supports real-time or near real-time queries. Querying the data allows you to explore, visualize, and analyze the data in various ways, such as dashboards, reports, charts, or alerts. You can also use queries to perform advanced analytics, such as machine learning, anomaly detection, or sentiment analysis.

# pipeline
orchestrate and manage the data pipeline that connects the different stages of the data analysis process. A data pipeline is a set of components and tasks that move and transform the data from the source to the destination, according to a predefined logic and schedule. A data pipeline can also handle errors, failures, retries, and dependencies, and provide monitoring and logging capabilities.


# visualisation
visualise the data

# governance
govern the data
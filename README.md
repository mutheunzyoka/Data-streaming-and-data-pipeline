# Data-streaming-and-data-pipeline
## Introduction
This architecture diagram represents a data processing pipeline in AWS Cloud using Amazon Kinesis, AWS Glue, Amazon S3, and Amazon Athena.


<img width="592" alt="image" src="https://github.com/user-attachments/assets/b47a3f04-426d-497c-bf76-26a4b6ef7098" />
 
 ### Summary
* Kinesis Data Streams ingests real-time data.
* Kinesis Data Firehose delivers data to Amazon OpenSearch for real-time analytics or Amazon S3 for storage and further processing.
* AWS Glue DataBrew cleans and transforms the data.
* AWS Glue catalogs the data(Stores the meta data).
*  Amazon Athena enables SQL querying on the processed data.
Cross-region replication ensures data durability and availability.

This setup ensures scalability, real-time analytics, and efficient storage for large-scale data processing

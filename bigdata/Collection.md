# Moving Data into AWS

There are three different ways to collect data and move it into AWS.

- Real-Time - Immediate Actions
	- Kinesis Data Streams (KDS)
	- Simple Queue Service (SQS)
	- Internet of Things (IOT)
- Near Real-Time - Reactive Actions
	- Kinesis Data Firehose (KDF)
	- Database Migration Service (DMS)
- Batch - Historical Analysis
	- Snowball
	- Data Pipeline


## AWS Kinesis Overview

Kinesis is a managed alternative to Apache Kafka and is used for:
- Application logs, 
- metrics, 
- IoT, 
- Clickstreams etc.

The data in Kinesis is automatically replicated to 3 Availability Zones.

- Kinesis Streams: Low latency streaming ingest at scale
- Kinesis Analytics: Perform real-time analytics using SQL
- Kinesis Firehose: Load streams into S3, Redshift, Elasticsearch & Splunk
- Kinesis Video Streams: Stream videos to AWS

# Real-time-Telemetric-Streaming-with-Amazon-Kinesis
This solution outlines how to build a complete telemetry streaming pipeline using Amazon Kinesis, Lambda functions, and Kinesis Data Firehose, all deployed via Infrastructure as Code with Terraform and managed through a DevSecOps CI/CD pipeline.
Real-time streaming data using one of the most useful services for handling streaming data is Amazon Kinesis to build a Telemetric stream, develop both a producer and consumer of events, and also deliver them to S3 destination using Kinesis Data Firehose. 1. Create an Amazon Kinesis Data Stream using terraform for IaC
2. Develop a Lambda Function to produce streaming events
3. Develop a Lambda Function to consume streaming events
4. Setup Kinesis Data Firehose to send events to an S3 Bucket
5.  create a DevSecOps CI/CD pipeline using GitHub, GitOps, terraform and ansible.

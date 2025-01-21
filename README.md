# Serverless-Datalake-Pipeline
![Serverless Structure (2)](https://github.com/user-attachments/assets/95099c9f-6796-4bc6-8f7f-385dcb812913)
#Overview
Serverless Watchtower is a serverless solution designed to monitor, process, and alert on events within an AWS ecosystem. By leveraging AWS Lambda, Amazon S3, CloudWatch, and Gmail, this project provides real-time insights and notifications, ensuring seamless automation and issue tracking.
#Key Features
Serverless Architecture: Fully serverless solution powered by AWS Lambda and Amazon S3.
Real-Time Monitoring: Uses CloudWatch to monitor events and trigger appropriate actions.
Automated Alerts: Sends email notifications via Gmail for critical events.
Event-Driven Workflows: Automates processing of S3 bucket changes with Lambda functions.
Data Integrity Checks: Built-in mechanisms to validate and process data during ingestion.

#Workflow
Data Ingestion:

Files uploaded to Amazon S3 trigger an AWS Lambda function for processing.
The Lambda function validates and extracts data.
Event Monitoring:

CloudWatch tracks events and triggers secondary Lambda functions as needed.
Processed data is stored in a secondary S3 bucket.
Alerting and Notifications:

CloudWatch monitors for specific metrics or errors.
Email alerts are sent via Gmail for critical events.

#Technologies Used
Amazon S3: For file storage and triggering events.
AWS Lambda: For serverless compute to process data and automate workflows.
CloudWatch: For monitoring and logging events.
Gmail: For sending email alerts.
AWS IAM: For secure access and role management.

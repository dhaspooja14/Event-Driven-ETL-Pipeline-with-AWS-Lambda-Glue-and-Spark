# Event-Driven-ETL-Pipeline-with-AWS-Lambda-Glue-and-Spark

Description:

This project showcases an event-driven ETL (Extract, Transform, Load) pipeline orchestrated using AWS Lambda, AWS Glue, and Apache Spark. The pipeline automates the processing and storage of data, with results stored in external databases such as MySQL Workbench or Snowflake.

Key Features:

Utilizes AWS Lambda and Glue for orchestration of the ETL pipeline.
Data processing is performed using Apache Spark for efficient and scalable processing.
Results are stored in external databases like MySQL Workbench or Snowflake for easy access and analysis.

How It Works:

A Lambda function, developed with boto3, is created to handle triggers from an S3 bucket.
When a file is uploaded to the S3 bucket, a trigger is activated, initiating the Lambda function.
The Lambda function then triggers a Glue job written in Spark language to process the uploaded file.
Once processed, the file is automatically added to the specified database platform, whether it be SQL Workbench, Snowflake, Oracle, or others.

Benefits:

Automation eliminates the need for manual intervention in the data loading process.
Increases efficiency and reduces the time required for data processing and storage.
Provides a scalable solution for handling large volumes of data seamlessly.

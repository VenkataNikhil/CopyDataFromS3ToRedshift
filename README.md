**Redshift-pipeline** <br>
Scalable data pipeline to efficiently transfer batch data from AWS S3 buckets to Redshift data warehouse daily for analytical workloads.

**Purpose** <br>
Automates the setup of an Amazon Redshift data warehouse and related infrastructure for analytics workloads

**Tech Stack**
* Python, boto3, AWS Redshift, S3, IAM roles

**Key Components** <br>
* **Infrastructure Provisioning**
  * Creates a Redshift cluster programmatically using boto3
  * Handles IAM roles, security groups, and connectivity automatically
* Configuration Management
  * Reads in parameters from a config file (clusters ids, DB names etc.)
  * Allows easy management of different environments
* Data Ingestion
  * Fetches data files stored in S3 bucket
  * Sets up workflow to load data from S3 into Redshift

**Outcomes**
* One-click creation of production-ready Redshift environment
* Code for loading data pipeline from S3 for analysis
* Config file-based configuration for easy management



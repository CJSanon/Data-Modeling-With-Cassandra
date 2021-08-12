### __Udacity Data Engineering Nano Degree | Project 2__

# Data Modeling With Apache Cassandra

## Project
Building an ETL pipeline for analysis on data collected on songs and user activity for a music streaming app. Data being processed are CSV files partitioned by date.  This pipeline was created using a Docker image of Apache Cassandra.
Configuration of Cassandra was followed using this guide: https://hub.docker.com/_/cassandra

## Tools Used
- Apache Cassandra
- Docker
- Jupyter Notebook

## Setup
* An important principle of data modeling in Cassandra is that you model the tables based on queries
1. Run Docker image of Cassandra using the setup guide above.
2. Create a connection to the Cassandra cluster on the default address and port.
3. Read denormalized CSV files and insert into Cassandra table for querying.
4. Mind the partition key and clustering columns for uniquely identyifying rows.

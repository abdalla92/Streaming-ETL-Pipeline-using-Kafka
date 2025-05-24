# Streaming-ETL-Pipeline-using-Kafka
This Project aims to build a streaming ETL Pipeline using Kafka

## Project scenario
As a data engineer at a data analytics consulting company, I have been assigned to a project that aims to de-congest the national highways by analyzing the road traffic data from different toll plazas. As a vehicle passes a toll plaza, the vehicle's data, like vehicle_id,vehicle_type,toll_plaza_id, and timestamp, are streamed to Kafka. My job is to create a data pipeline that collects the streaming data and loads it into a database.

## Objectives
In this project, I created a streaming data pipe by performing these steps:

Start a MySQL database server

Create a table to hold the toll data

Start the Kafka server

Install the Kafka Python driver

Install the MySQL Python driver

Create a topic named toll in Kafka

Download the streaming data generator program

Customize the generator program to steam to toll topic

Download and customize streaming data consumer

Customize the consumer program to write into a MySQL database table

Verify that streamed data is being collected in the database table

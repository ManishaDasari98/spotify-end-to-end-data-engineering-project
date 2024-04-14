# Spotify End-to-End Data Engineering Project
## Overview

In this project, we will build an ETL pipeline using the Spotify API on AWS. The pipeline will retrieve data from the spotify API, transform it to a desired format, and load it into an AWS data store.

## Architecture

![image](https://github.com/ManishaDasari98/spotify-end-to-end-data-engineering-project/assets/166990279/fcdc5ee0-af4c-4ee0-8c86-20a2c4e7b82c)

## About Data

In our project, we leverage data from the Spotify API using the spotipy library. Specifically, we extract the top 50 songs Global data in JSON format. The Spotify API provides a rich source of information about music, including details about songs, artists, albums, and more.

By utilizing the spotipy library, we efficiently retrieve the top 50 songs Global data in JSON format from the Spotify API. This data serves as a valuable source of information for our project, enabling us to analyze trends in global music consumption and derive insights that inform our decision-making processes.

Overall, the Spotify API, coupled with the spotipy library, empowers us to access and utilize rich music data, enhancing the functionality and effectiveness of our project.

## Services Used

1. AWS S3 (Simple Storage Service): Amazon S3 (Simple Storage Service) is a highly scalable object storage service that can store and retrieve any amount of data from anywhere on the web. It is commonly used to store and distribute large media files, data backups and static website files.

2. AWS Lambda: AWS Lambda is a serverless computing service that let you run your code without managing servers. You can use Lambda to run code in response to events like change in S3, DynamoDB, or other AWS services.

3. AWS CloudWatch: Amazon CloudWatch is a monitoring service for AWS resources and the applications you run on them. You can use CloudWatch to collect and track metrics, collect and monitor log files, and set alarms.

4. AWS Glue: AWS Glue is a serverless data integration service that makes it easy for analytics users to discover, prepare, move, and integrate data from multiple sources.. You can use it for analytics, machine learning, and application development.

5. AWS Crawler: A crawler can crawl multiple data stores in a single run. Upon completion, the crawler creates or updates one or more tables in your Data Catalog. Extract, transform, and load (ETL) jobs that you define in AWS Glue use these Data Catalog tables as sources and targets.

6. AWS Athena: Amazon Athena is an interactive query service that makes it easy to analyze data directly in Amazon Simple Storage Service (Amazon S3) using standard SQL

## Installed Packages

pip install spotipy
pip install pandas

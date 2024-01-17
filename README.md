# GaneshRam23-YouTube-Analysis-Project
YouTube Analysis Project - End-to-End Data Engineering utilizing AWS Cloud and Python

Project Title: YouTube Analysis Project - End-to-End Data Engineering utilizing AWS cloud and Python

Project Overview: This project is crafted to effectively manage, optimize, and analyze organized and partially organized data extracted from YouTube videos. The primary objective is to categorize the videos and evaluate trending metrics in order to extract valuable insights.
Project Objectives: 📌 Data Ingestion 📌 ETL System 📌 Data Lake Implementation  📌 Cloud Integration (AWS) 📌 Reporting Dashboards

Pipeline Phases: The project unfolds in three key phases:

📌 Extract:

Data extraction from Kaggle, featuring daily statistics of popular YouTube videos.
AWS Lambda deployment for extraction function.
Automated extraction triggered by AWS CloudWatch at regular intervals.
Raw data stored in AWS S3 Bucket under "de-on-youtube-raw-ind-dev."
📌 Transform:

S3 triggers activating a Lambda function for data transformation.
Categorized data by region, moved from "de-on-youtube-raw-ind-dev" to "de-on-youtube-cleansed-ind."
📌 Load:

Glue Crawler for schema inference upon new data addition.
Amazon Athena renders the final dataset queryable and analyzable.

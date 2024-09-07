# Data Engineering YouTube Analysis Project
## Overview
This project demonstrates an end-to-end data engineering solution designed to manage, streamline, and analyze structured and semi-structured YouTube data based on video categories and trending metrics. The project was executed entirely on AWS to leverage the scalability and flexibility of cloud computing, focusing on efficient data ingestion, transformation, storage, and analysis.

### Project Goals
 * Data Ingestion: Built a robust mechanism to ingest data from multiple sources (CSV files) using Amazon S3.
 * ETL System: Transformed raw YouTube data into a clean, analyzable format using AWS Glue and Athena.
 * Data Lake: Centralized the data from various sources into a unified storage solution using Amazon S3 as a data lake.
 * Scalability: Ensured the architecture could scale as the data size grows by leveraging AWS cloud services.
 * Cloud-Based Processing: Used AWS cloud infrastructure to handle large datasets that couldn't be processed locally.
 * Reporting: Created dashboards using Amazon QuickSight to visualize insights from the processed data.
 * AWS Services Used
 * Amazon S3: Used for centralized storage of raw and transformed data, serving as a data lake.
 * AWS IAM: Managed secure access to AWS services and resources.
 * Amazon QuickSight: Developed interactive dashboards for visualizing trends and metrics.
 * AWS Glue: Set up serverless ETL jobs to discover, clean, and transform raw YouTube data.
 * AWS Lambda: Leveraged serverless compute to automate certain parts of the workflow.
 * AWS Athena: Used for querying data directly from S3 using SQL, without needing to load it into a database.

### Dataset Used
The project used a YouTube trending dataset available on Kaggle, which contains statistics on daily trending YouTube videos from various regions. The dataset includes video details such as:

 * Video ID, title, channel title
 * Publication time, tags, views, likes, dislikes
 * Description, comment count, and category ID

https://www.kaggle.com/datasets/datasnaek/youtube-new/data

# For more details please refer to the documetation document!

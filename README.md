# YouTube-Analysis-using-AWS

## Overview
This project aimed to analyze the structured and semi-structured YouTube video data based on the video categories and trending metrics using AWS services.

## AWS Services used
1. Amazon S3: Used to store raw data, cleaned/processed data, and analytics data.
2. AWS IAM: Used to securely manage access to AWS services and resources.
3. QuickSight: For building dashboards from the analytics data.
4. AWS Glue: Built ELT pipelines to process raw data for analysis.
5. AWS Lambda: Virtual function, used to format data in the desired format while storing raw data in an S3 bucket.
6. AWS Athena: Athena is used to query data directly from S3 and act as a quicksight source.

## Artitecture Diagram


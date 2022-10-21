# Twitter-ETL-Project

This is a Twitter ETL Project in which twitter data(user,Tweet text, no. of likes,no. of retweets,tweet date) of any twitter user (Paul Graham in my case) 
is extracted using Twitter API (Tweepy) and then transformed using Pandas and then load in AWS S3 Bucket. 

This pipeline workflow is being orchestrated using Apache Airflow.

The ETL Python code and Airflow DAG code  is being deployed in an AWS EC2 machine.

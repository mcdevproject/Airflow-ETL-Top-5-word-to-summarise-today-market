# [Airflow][ETL]Top 5 words to summarise today’s market and/or your watchlist

## Introduction
In this project, we will set up a simple ETL pipeline using Airflow to collect news headline data from various sources. Airflow, as an orchestrator, will run the defined DAG (Directed Acyclic Graph - basically a workflow diagram) every Monday to Friday during the US market opening. After the every-hour extraction and transformation, we could further process the collected data and find out the top 5 words of the day, or of the week and month.

## High-level Diagram
![alt text](https://i.imgur.com/P4HiTPF.jpg)


## Data Collection
Currently, there are two news sources (and more will be added, hopefully...):
1. **NewsAPI - JSON response**: contains news headline data with author, source, title, publishing time and url.
2. **yFinance - DataFrame structure**: contains headline data with author, news title, news contents and url.

## Technology
**Airflow**, **Docker**, **GCP BigQuery & Cloud Storage (GCS)**, **Python**, **SQL**, and **Terraform**

## Future Development 
1. Dashboard to visualize news data
2. Grafana + Prometheus to monitor Airflow jobs 

## Credit to Data Source
NewsAPI: https://newsapi.org <br/>
yFinance: https://pypi.org/project/yfinance/




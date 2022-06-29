# [Airflow][ETL]Top 5 words to summarise today’s market and/or your watchlist

## Introduction
In this project, we will set up a simple ETL pipeline using Airflow to collect news headline data from various sources. Airflow, as a orchestrator, will run the defined DAG (Directed Acyclic Graph - basically a workflow diagram) for every Monday to Friday during the US market opening. After the every-hour extraction and transformation, we could further process the collected data and find out top 5 words of the day, or of the week and month.

## High-level Diagram

## Data Collection
Currently, there are two news sources (and more will be added, hopefully...):
1. **NewsAPI - JSON response**: contains news headline data with author, source, title, publishing time and url.
2. **YFinance - DataFrame structure**: contains headline data with author, news title, news contents and url.

## Technology
**Airflow**, **Docker**, **GCP Cloud Storage (GCS)**, **Python** and **Terraform**

## Future Development 
1.
2.

## Credit to Data Source
NewsAPI: https://newsapi.org <br/>
YFinance: https://pypi.org/project/yfinance/




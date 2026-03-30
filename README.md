# S&P 500 ETL Pipeline

## Overview
Built an ETL pipeline in Google Colab to extract, transform, and load S&P 500 stock data.

## Data Source
- S&P 500 company universe (DataHub)
- Alpha Vantage stock API

## Pipeline
1. Extract S&P 500 ticker list
2. Pull stock price data for multiple companies
3. Transform data (cleaning + feature engineering)
4. Calculate:
   - Daily returns
   - 7-day moving average
   - 30-day moving average
5. Export centralized dataset

## Tech Stack
- Python
- Pandas
- Requests
- Google Colab

## Features
- Multi-stock ingestion (S&P 500 structure)
- Time-series transformation
- Financial feature engineering

## Output
- Clean structured dataset for analysis

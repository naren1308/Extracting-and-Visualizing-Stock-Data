# Revenue Data & Dashboard

📓 Notebook: /mnt/data/Revenue Data and Building a Dashboard.ipynb

## Overview
This project extracts, cleans, and visualizes historical **stock price** and **revenue data** for public companies using two sources:

- `yfinance` for stock market data  
- Web scraping for revenue data  

The analysis is applied to **Tesla (TSLA)** and **GameStop (GME)** to demonstrate real-world data collection, cleaning, and visualization.

This is foundational financial data analysis and dashboard preparation.

## Tech Stack
- Python
- pandas
- yfinance
- matplotlib / plotly
- BeautifulSoup4
- requests
- Jupyter Notebook

## What This Notebook Does
- Retrieves stock price history via API
- Scrapes revenue data from the web
- Cleans messy real-world data (symbols, nulls, formatting)
- Aligns and processes multiple datasets
- Visualizes stock and revenue trends
- Uses reusable plotting functions

## How to Run

1. Install dependencies:
   ```bash
   pip install yfinance pandas matplotlib beautifulsoup4 requests

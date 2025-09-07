# Analyzing-Historical-Stock-Revenue-Data-and-Building-a-Dashboard
Fetches TSLA &amp; GME prices (yfinance), scrapes quarterly revenue, and builds Plotly dashboards to compare price vs revenue (data shown up to Jun 2021).
This repository contains a reproducible Jupyter notebook that analyzes Tesla (TSLA) and GameStop (GME) by pairing historical stock prices (via yfinance) with quarterly revenue (web-scraped), then visualizes both in clean, side-by-side Plotly dashboards. The project follows the course rubric: extracting stock data, scraping revenue tables, light cleaning (removing $ and commas), and plotting price vs revenue for each company. Per assignment requirements, charts display data up to June 2021.

What’s inside

Stocks_Revenue_Dashboard.ipynb – end-to-end workflow (Q1–Q7)

Helper functions for scraping (BeautifulSoup/read_html), cleaning, and plotting

Two dashboards: Tesla and GameStop (Close price + quarterly revenue)

Tech
python, pandas, yfinance, requests, beautifulsoup4/lxml, plotly

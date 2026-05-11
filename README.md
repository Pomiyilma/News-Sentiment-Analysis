# Financial News Sentiment & Market Analysis

## Overview
This project explores a large-scale financial news dataset containing over 1.4 million headlines collected between 2010 and 2020. The objective is to analyze publication trends, publisher activity, headline characteristics, and recurring financial themes in preparation for downstream sentiment analysis and stock movement prediction tasks.

## Task 1 Objectives
- Set up GitHub workflow and CI/CD
- Perform exploratory data analysis (EDA)
- Analyze headline statistics
- Investigate publisher activity
- Perform temporal analysis on publication dates
- Extract keywords and recurring financial topics
- Generate visualizations and insights

## Dataset Summary
- Total Articles: 1,407,328
- Columns:
  - headline
  - url
  - publisher
  - date
  - stock

## Key Findings
- Financial reporting is heavily centered around earnings, stock updates, analyst ratings, and trading activity.
- Publisher activity is highly concentrated among major financial news providers.
- The dataset spans nearly a decade of market-related reporting.
- Timestamp inconsistencies were identified where some records lacked exact publication times.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Git & GitHub Actions


## Task 2 Progress

Implemented:
- Stock price data loading using pandas
- Data quality inspection and missing value analysis
- Time-series preprocessing
- Simple Moving Average (SMA) computation
- Exponential Moving Average (EMA) computation
- Technical indicator visualizations

Upcoming:
- RSI analysis
- MACD analysis
- Correlation analysis between news sentiment and stock movement
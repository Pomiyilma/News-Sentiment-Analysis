# Financial News & Stock Movement Analysis

## Overview

This project investigates the relationship between financial news sentiment and stock market behavior using Natural Language Processing (NLP), technical analysis indicators, and statistical correlation methods.

The project was completed as part of a multi-phase financial analytics challenge focused on building a data analysis pipeline capable of linking financial news headlines with stock price movements.

The workflow combines:
- Exploratory Data Analysis (EDA)
- Financial Technical Indicators
- Sentiment Analysis
- Correlation Analysis
- Time-Series Visualization

---

# Business Objective

The project focuses on two major analytical goals:

1. **Sentiment Analysis**
   - Extract sentiment from financial news headlines using NLP techniques
   - Quantify headline tone using numerical sentiment scores

2. **Correlation Analysis**
   - Measure the statistical relationship between news sentiment and daily stock returns
   - Identify whether positive or negative news trends align with stock price movement

The insights generated from this analysis can support:
- Investment strategy development
- Market trend monitoring
- Risk assessment
- Financial decision-making

---

# Project Structure

```bash
.
├── data/
│   ├── raw/
│   └── yfinance/
│
├── notebooks/
│   ├── task-1.ipynb
│   ├── task-2.ipynb
│   └── task-3.ipynb
│
├── .github/
│   └── workflows/
│       └── unittests.yml
│
├── requirements.txt
├── README.md
└── .gitignore


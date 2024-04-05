# Enhancing Stock Market Forecasts with Double Deep Q-Network in Volatile Stock Market Environments - Dataset

## Introduction

This repository has been established in conjunction with the publication of the research paper titled "Enhancing Stock Market Forecasts with Double Deep Q-Network in Volatile Stock Market Environments" It serves as a supplementary resource for researchers, financial analysts, and stock market enthusiasts engaged in conducting in-depth analyses and creating predictive models related to NVIDIA stock.

Within this repository, you will find a carefully curated collection of data related to NVIDIA stock, covering both financial and sentiment aspects from the years 2020 up to Q3 of 2023. The data is presented in a structured format, processed, analyzed (using 'Twitter-roBERTa-base') and cleansed, making it accessible for anyone wishing to apply predictive modeling that incorporates both financial and sentiment data.

## Data Source

The data contained within this repository have been collected from the official [Yahoo! Finance](https://www.finance.yahoo.com) and [StockTwits](https://www.stocktwits.com) platforms. The data is used under the terms of their usage policies, and all appropriate credit for the original data collection goes to Yahoo! Finance and StockTwits.

Please note that this repository is not affiliated with, sponsored by, or endorsed by Yahoo! Finance or StockTwits.

## Repository Contents

- `Yahoo Finance Data`: Financial data from Yahoo Finance, covering Date, Open, High, Low, Close, Adjusted Close, and Volume metrics for the NVIDIA stock.
- `StockTwits Sentiment Data`: Sentiment and social media metrics from StockTwits, including creation time, user general information (e.g. home country, followers), total likes and sentiment scores (basic, negative, neutral, positive).

## How to Use This Data

The data related to NVIDIA's stock provided in this repository is intended to support academic and research activities exclusively. It is suited for a variety of scholarly and investigative applications, including but not limited to:
- **Academic Financial Analysis**: Employ in comprehensive financial analysis and equity research for scholarly purposes, offering insights into stock performance and market dynamics with a focus on academic outcomes.
- **Research in Machine Learning**: Leverage the dataset for academic research in predictive modeling and machine learning, aiming at forecasting stock price movements or analyzing sentiment trends within a research or educational context.
- **Investor Sentiment Analysis**: Utilize sentiment analysis techniques and social media metrics in academic studies to explore the impact of investor sentiment on stock prices, which is suitable for research papers or educational projects.

# Glossary of Stock Market Metrics and KPIs

## Yahoo Finance Metrics
- `Date`: The trading date for which data is provided.
- `Open`: The price at which a stock first trades upon the opening of an exchange on a given trading day.
- `High`: The highest price at which a stock is traded during the trading day.
- `Low`: The lowest price at which a stock is traded during the trading day.
- `Close`: The final price at which a stock trades during a regular trading session.
- `Adj Close`: The closing price after adjustments for all applicable splits and dividend distributions.
- `Volume`: The number of shares that changed hands during a given day's trading session.

## StockTwits Sentiment Data
- `created_at`: The original timestamp when the text was posted.
- `created_at_datetime_format_UTC`: The formatted text creation time in UTC.
- `symbols`: The stock symbols mentioned in the text.
- `user.identity`: The status of the user (User or Official).
- `user.home_country`: The user's home country.
- `user.followers`: The number of followers the user has on StockTwits.
- `likes.total`: The total number of likes a text has received.
- `entities.sentiment.basic`: The basic sentiment of the text, e.g., Bullish or Bearish.
- `score_negative`: A score representing the negative sentiment in the text.
- `score_neutral`: A score representing the neutral sentiment in the text.
- `score_positive`: A score representing the positive sentiment in the text.

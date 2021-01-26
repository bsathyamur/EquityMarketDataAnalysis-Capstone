# Guided Capstone project for Equity Market Data Analysis

Spring Capital is an investment bank who owe their success to Big Data analytics. They make critical
decisions about investments based on high-frequency trading data analysis. High-frequency financial data
relate to important financial market events, like the price of a stock, that are collected many times
throughout each day.

Spring Capital collects data on trades and quotes from multiple exchanges every day. Their data team
creates data platforms and pipelines that provide the firm with insights through merging data points and y
calculating key indicators. Spring Capital’s business analysts want to better understand their raw quote
data by referencing specific trade indicators which occur whenever their quote data is generated,
including:
- Latest trade price
- Prior day closing price
- 30-minute moving average trade price (Average price over the past 30 minutes, constantly
updated. This is a common indicator which smooths the price trend and cuts down noise.)

The goal of this project is to build an end-to-end data pipeline to ingest and process daily stock market
data from multiple stock exchanges. The pipeline should maintain the source data in a structured format,
organized by date. It also needs to produce analytical results that support business analysis.

# Architecture diagram

!(img)(https://github.com/bsathyamur/EquityMarketDataAnalysis-Capstone/blob/main/EMDA-Architecture%20Diagram.jpg)

# A Beginner's Guide to Personal Investing
This project was created by University of Chicago MBA students as a class project for Data Visualization for Decision-Making (BUSN32130), taught by Professor [Lara Kattan](https://www.chicagobooth.edu/faculty/directory/k/lara-kattan)

Team members:
* Gonzalo Tenorio
* Michael Logan

## Overview
When breaking into the world of personal investing, there are a few questions that always need answering:
1. Why invest? Why not just keep my cash under my mattress like the good ole days?
2. If I do decide to invest, when should I start?
3. After I start, what can I trust to not lose my hard-earned money?

These questions can be answered through countless google searches or by our friend ChatGPT, but we thought it would be easier to not only tell you about the benefits of investing, but to also show you with several visualizations that illustrate its importance.

This project walks through key investing rationale that helps inform potential investors. It is inteded to not only explain the important features of investing, but to also give visual context that provides another way to comprehend complex topics. It is especially helpful for those brand new to investing, and also visual learners.

## Deliverables
**"A Beginner's Guide to Personal Investing"** is a PDF report found above that walks through several questions and insights related to personal investing. *[Note: see "Table of Contents" below for more information]* 

**"Explore Your Portfolio Options"** is a tableau workbook that allows you to test different allocations of asset classes to see how the expected return and risk changes based on historic timelines. 

## Data Sources
1. **Equity Data:**
   * Data: Daily price information for tradeable assets
   * Tradeable assets:
      * SPDR S&P 500 ETF Trust (SPY) - *proxy for S&P 500 (stocks)*
      * Vanguard Total Bond Market Index Fund ETF (BND) - *proxy for US bond market*
      * SPDR Gold Trust (GLD) - *proxy for commodities market*
      * Vanguard Real Estate Index Fund ETF (VNQ) - *proxy for real estate market*
      * Grayscale Bitcoin Trust (GBTC) - *proxy for cryptocurrency*
   * Timeframe: 2020-01-01 to 2025-01-01
   * Source: Yahoo Finance
   * Retrieval Method: jupyter notebook

2. **Inflation Data:**
   * Data: Monthly Consumer Price Index (CPI) data
   * Timeframe: 2020-01-01 to 2025-01-01
   * Source: U.S. Bureau of Labor Statistics via FRED®
   * Retrieval Method: excel export 

## Reposity Layout
* `Folder` Data
  * "Equity_Data_Download" (jupyter notebook) - Python script to download data
  * "Equity_Data" (csv) - Daily closing prices of several equities
  * "Inflation_Data" (csv) - Monthly Consumer Price Index (CPI) data
* `Folder` Vizualizations
  * "Excel Graphs" (excel worksheet) - Visualizations for Sections #, #, #
  * "Python Graphs" (jupyter notebook) - Visualizations for Sections #, #, #
  * "Tableau Graphs" (tableau workbook) - Dashboard
* "A Beginner's Guide to Investing" (PDF) - Final report submission with all visualizations and explanations
* "Explore Your Portfolio Options" (tableau workbook) - Interactive workbook for you to explore how you may build your portfolio

## "A Beginner's Guide to Personal Investing" Table of Contents
1. Why Invest? Impact of inflation
2. The benefits of compounding
3. ...


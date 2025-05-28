# A Beginner's Guide to Personal Investing
This project was created by University of Chicago MBA students as a class project for Data Visualization for Decision-Making (BUSN32130), taught by Professor [Lara Kattan](https://www.chicagobooth.edu/faculty/directory/k/lara-kattan)

Team members: Gonzalo Tenorio, Michael Logan

## Overview
When breaking into the world of personal investing, there are a few questions that always need answering:
1. Why should I invest at all? Wouldn't it be safer to just keep my cash under the mattress like the good old days?
2. If I do decide to invest, when's the right time to start?
3. Once I'm in, how do I know where to put my money so I don't lose it all?

While these questions can be answered through countless Google searches or even a quick chat with ChatGPT, we wanted to make the investing journey more approachable. Instead of just reading about the benefits of investing, we created interactive visualizations that let new investors explore the data for themselves: showing, not just telling, why investing matters.

This project walks through key investing rationale that helps inform potential investors. It is inteded to not only explain the important features of investing, but to also give visual context that provides another way to comprehend complex topics. It is especially helpful for those brand new to investing and visual learners.

## Deliverables
**"A Beginner's Guide to Personal Investing"** is a PDF report found above that walks through several questions and insights related to personal investing. *[Note: see "Table of Contents" below for more information]* 

**"Explore Your Portfolio Options"** is a tableau workbook that allows you to test different allocations of asset classes to see how the portfolio risk/return profile changes based on historic timelines. 

## Data Sources
1. **Equity Data:**
   * Data: Daily price information for tradeable assets
        * SPDR S&P 500 ETF Trust (SPY) - *proxy for S&P 500 (stocks)*
        * Vanguard Total Bond Market Index Fund ETF (BND) - *proxy for US bond market*
        * SPDR Gold Trust (GLD) - *proxy for commodities market*
        * Vanguard Real Estate Index Fund ETF (VNQ) - *proxy for real estate market*
        * Grayscale Bitcoin Trust (GBTC) - *proxy for cryptocurrency*
   * Timeframe: 2020-01-01 to 2025-01-01
   * Source: [Yahoo Finance](https://finance.yahoo.com/)
   * Retrieval Method: jupyter notebook

2. **Inflation Data:**
   * Data: Monthly Consumer Price Index (CPI) data
   * Timeframe: 2020-01-01 to 2025-01-01
   * Source: [U.S. Bureau of Labor Statistics via FRED®](https://fred.stlouisfed.org/series/CPIAUCSL)
   * Retrieval Method: excel export 

## Reposity Layout
* `Folder` Data Files
  * "Equity_Data_Download" (jupyter notebook) - Python script to download data
  * "Equity_Data" (csv) - Daily closing prices of several equities
  * "Inflation_Data" (csv) - Monthly Consumer Price Index (CPI) data
* `Folder` Vizualizations for Report
  * "Excel Graphs" (excel worksheet) - Visualizations for Sections #, #, #
  * "Python Graphs" (jupyter notebook) - Visualizations for Sections #, #, #
  * "Tableau Graphs" (tableau workbook) - Dashboard
* "A Beginner's Guide to Investing" (PDF) - Final report submission with all visualizations and explanations
* "Explore Your Portfolio Options" (tableau workbook) - Interactive workbook for you to explore how you may build your portfolio

## Table of Contents: "A Beginner's Guide to Personal Investing"
1. ...
2. ...
3. ...


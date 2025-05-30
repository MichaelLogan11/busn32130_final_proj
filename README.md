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

## Process
### Motivation
This project began with the goal of simplifying how people learn about personal investing, using visualizations as the primary tool. Since many people are visual learners, we felt that a visual approach would make complex financial concepts more accessible and engaging.

We aimed to make the guide especially helpful for beginner investors. To reflect that personal investing doesn’t have to be intimidating, we adopted a casual and approachable tone. Many of the questions we addressed were ones we had ourselves when we were first considering investing. We created the visualizations we wish we had back then to make these topics more accessible and easier to understand.

### Assumptions/Limitations
A key assumption throughout this project is that the stock proxies we selected adequately represent their respective asset classes. While there are countless tradeable assets, we chose five as a representative sample to keep things simple and focused.

For example, we use SPY (a widely traded ETF that tracks the S&P 500) to represent the overall U.S. stock market. Each asset class is paired with a single tradeable proxy for visualization purposes. While we acknowledge this approach isn’t perfectly accurate, we believe it’s a reasonable simplification for the goals of this project. A full list of proxies can be found in the "Data Sources" section below.

Another limitation is time coverage. SPY and similar long-standing assets offer decades of data, while newer asset classes like cryptocurrency have relatively short histories. This didn’t significantly impact our analysis, but it’s an important consideration.

### Data Sources
We used 2 primary data sources: 
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
  
### Data validation
**Equity Data**

Equity data was retrieved with open, close, high, and low prices, so we calculated daily returns (the percentage change in price from one day to the next) based on each day's closing price using Python or Excel. Refer to the "Equity_Data_Download" file in the "Data Files" folder for details.

We then spot-checked various dates in the dataset and plotted the price history of each asset to verify that the overall shape and trends appeared accurate. Additionally, we calculated SPY yearly returns and compared them with [Yahoo Finance Yearly Historic Returns](https://finance.yahoo.com/quote/SPY/performance/?guccounter=1&guce_referrer=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&guce_referrer_sig=AQAAAIRildlPZJFMbluMnDgA-AulwkGT5irlw1iAzw1r-xcGJ85ZVsxgBqYE5vbRJhZ4a2C4u8b1JULHvQ3mF1NZkzcicC2yHtvKm-k8OASMQ8NnfAaWL0zq0ZKGrfoUqxk0sbBlaPBo7eD2JlP8G_nOvGTHP2mCo3Q7mr9aWslVJKTl) for consistency. 

**Inflation Data**

We were confident in the quality of the inflation data, as it was directly downloaded from FRED. However, since the equity data is daily and the inflation data is monthly, merging the two required careful alignment. We ensured that each equity entry was accurately matched to the correct month and year from the inflation data.

### Future work
While we think this guide provides a helpful foundation for learning, given more time we would have liked to provide a more forward looking perspectives on how modifying a portfolio would impact risk and returns. More specifically, adding a "projection" of asset prices for future years that the beginning investor could use to help build there portfolio right now would be useful. 

We also understand that we used a very small sample of assets, so we would have liked to expand that selection to provide more detail on what assets are available for purchase.

### Use of ChatGPT and LLMs
While some of the visualizations used were rather simple, LLMs were used in the creation of some more detailed graphics, specifically those in Python. Particularly, ChatGPT was used when adding a complex feature, like multiple charts on one plot, overlaying text callouts, or shading appropriate portions. The use of LLMs is noted at the top of each Jupyter Notebook in the "Visualizations" folder. 

## Reposity Layout
* `Folder` Data Files
  * "Equity_Data_Download" (jupyter notebook) - Python script to download data
  * "equity_data" (csv) - Daily closing prices of several equities
  * "inflation_data" (csv) - Monthly Consumer Price Index (CPI) data
* `Folder` Vizualizations for Report
  * "Excel Graphs" (excel worksheet) - Visualizations for Sections 1, 2, 4, 6
  * "Python Graphs" (jupyter notebooks) - Visualizations for Sections 3, 4, 5
  * "Tableau Graphs" (tableau workbook) - Visualization for Section 4
* "A Beginner's Guide to Investing" (PDF) - Final report submission with all visualizations and explanations
* "Explore Your Portfolio Options" (tableau workbook) - Interactive workbook for you to explore how you may build your portfolio

## Table of Contents: "A Beginner's Guide to Personal Investing"
* Introduction
* Definitions
* Section 1: Why invest in the first place?
* Section 2: When is the right time to start investing?
* Section 3: What about everything out of my control?
* Section 4: How smooth is the ride?
* Section 5: Why take any risk at all?
* Section 6: How should I pick what to buy and how much?
* Section 7: Try It Yourself – Building a Portfolio
* Conclusion: Investing with Confidence


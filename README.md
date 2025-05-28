# Beginner's Guide to Personal Investing: Visual Overvier

## Overview
When breaking into the world of personal investing, there are a few questions that always need answering:
1. Why invest? Why not just keep my cash under my mattress like the good ole days?
2. If I do decide to invest, when should I start?
3. After I start, what can I trust to not lose my hard-earned money?

These questions can be answered through countless google searches or by our friend ChatGPT, 
but we thought it would be easier to not only tell you about the benefits of investing, but to also
show you with several visualizations that illustrate its importance.

## Data Sources
1. **Equity Data:**
   Data: Daily price information for the following tradeable assets
      * SPDR S&P 500 ETF Trust (SPY) - *proxy for S&P 500 (stocks)*
      * Vanguard Total Bond Market Index Fund ETF (BND) - *proxy for US bond market*
      * SPDR Gold Trust (GLD) - *proxy for commodities market*
      * Vanguard Real Estate Index Fund ETF (VNQ) - *proxy for real estate market*
      * Grayscale Bitcoin Trust (GBTC) - *proxy for cryptocurrency*

   Timeframe: 2020-01-01 to 2025-01-01<br>  
   Source: Yahoo Finance<br>  
   Retrieval Method: jupyter notebook<br>  

2. **Inflation Data:**
   Data: Monthly Consumer Price Index (CPI) data<br>  
   Timeframe: 2020-01-01 to 2025-01-01<br>  
   Source: U.S. Bureau of Labor Statistics via FRED®<br>  
   Retrieval Method: excel export<br>  

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

## Sections with Accompanying Visulations
1. Why Invest? Impact of inflation
2. The benefits of compounding
3. ...


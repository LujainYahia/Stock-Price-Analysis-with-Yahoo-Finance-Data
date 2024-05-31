# Stock-Price-Analysis-with-Yahoo-Finance-Data
Here's a README file for the provided Python script:

---

# Stock Price Analysis with Yahoo Finance Data

## Overview:
This Python script analyzes historical stock price data obtained from Yahoo Finance using the yfinance library. It performs various data analysis tasks including visualization of closing prices, calculation of moving averages (50-day and 200-day), distribution analysis, and regression analysis.

## Requirements:
- Python 3.x
- Required Python libraries:
  - yfinance
  - matplotlib
  - seaborn
  - statsmodels

## Installation:
Ensure you have Python 3.x installed on your system. Install the required Python libraries using pip:

```
pip install yfinance matplotlib seaborn statsmodels
```

## Usage:
1. Run the script using a Python interpreter.
2. The script will perform the following tasks:
   - Retrieve historical stock price data for the specified ticker (e.g., 'GOOG') from Yahoo Finance.
   - Analyze the data by plotting closing prices over time, calculating 50-day and 200-day moving averages, and visualizing them.
   - Conduct distribution analysis of closing prices and 50-day moving averages.
   - Perform regression analysis to model the relationship between closing prices and the 50-day moving average.
3. Review the generated plots and analysis results.

## Files:
- `stock_price_analysis.py`: Python script for analyzing historical stock price data.

## Notes:
- Ensure that all required Python libraries are installed before running the script.
- The script assumes that yfinance can access Yahoo Finance data without any authentication issues.
- Modify the ticker symbol (e.g., 'GOOG') to analyze data for different stocks.


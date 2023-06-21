# Futures-Momentum-Strategy-and-VIX-Analysis
# Description:

This project analyzes the momentum strategy for a list of futures: ES=F (E-mini S&P 500), NQ=F (E-mini NASDAQ-100), CL=F (Crude Oil), and GC=F (Gold). The script downloads historical data for these futures and calculates the return and volume change over the past 5 days. The data is then visualized in bar charts, showing the return and volume change for each future. Bars are colored green for positive values and red for negative values. Each bar is also annotated with the total traded volume in millions.

In addition to the futures analysis, the project also downloads and visualizes data for the VIX (Volatility Index). It calculates the percentage change in the VIX over the past 5 days and plots the VIX closing prices over time.

The script uses the yfinance library to download data, pandas for data manipulation, and matplotlib for visualization. The date range for the data can be adjusted by modifying the start and end parameters in the yf.download() function calls.

The project is intended to help users visualize and understand the recent performance of these futures and the VIX, as well as the concept of a momentum strategy in futures trading.

Please note that this script is for informational and educational purposes only, and should not be used as a basis for making investment decisions. Always consult with a qualified professional before making decisions about your personal finances.

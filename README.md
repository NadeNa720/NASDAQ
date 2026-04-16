# NASDAQ Stock Analysis
# Overview

This project provides an analysis of historical stock price data for selected major NASDAQ companies. The goal is to collect, process, and visualize stock performance over time using Python.

The project focuses on analyzing daily closing prices of the following companies: Apple (AAPL), Microsoft (MSFT), Google (GOOGL), Amazon (AMZN), and Tesla (TSLA). The data is obtained from Yahoo Finance using the yfinance library.

The analysis includes data collection, cleaning, validation, and visualization to better understand trends and behavior in the stock market.

# Project Structure

The repository contains the main Jupyter notebook with the analysis, a data card describing the dataset, a requirements file with dependencies, and this README file.

# Dataset Description

The dataset is collected programmatically from Yahoo Finance. It includes daily stock data for selected companies over the period from 2020 to 2024.

The dataset contains the following variables: date, closing price, and stock symbol. The data is structured in a time series format and is suitable for exploratory analysis and visualization.

# Data Source

The data is retrieved using the yfinance Python library, which accesses publicly available financial data from Yahoo Finance.

# Data Collection Process

The data is automatically downloaded using Python scripts within the notebook. Each stock ticker is queried individually, and the results are combined into a single dataset for analysis.

# Data Quality

Basic data validation is performed to ensure consistency and completeness. Missing values are checked and handled where necessary. Since the data comes from a reliable public source, it is generally accurate, but it may still contain minor inconsistencies or delays.


# Technologies Used

The project is implemented using Python and relies on several libraries, including pandas for data manipulation, yfinance for data collection, and matplotlib for visualization.

# Project Functionality

The notebook downloads historical stock data, processes and organizes it, performs basic validation, and generates visualizations to compare stock performance across companies.

# Usage

To use this project, clone the repository, install the required dependencies, and run the Jupyter notebook. The notebook will automatically fetch the data and produce the analysis.

# Limitations

The dataset is limited to selected companies and a fixed time range. It does not include external factors such as macroeconomic indicators or company-specific events. The analysis is basic and does not include predictive modeling.


# Disclaimer

This project is created for educational purposes only. It should not be used as financial advice or for making investment decisions.

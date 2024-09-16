# Efficient_portfolio_analysis

Welcome to the Efficient Portfolio Analysis project! This initiative focuses on a detailed examination of a select portfolio of stocks, specifically ADANI, GAIL, LARSEN & TOUBRO, and RELIANCE, prominent entities in the Indian stock market. Using advanced statistical and financial tools within Python, this project aims to derive the efficient frontiers and the minimum variance portfolios for these stocks. Additionally, it evaluates the Value at Risk (VaR) and Conditional Value at Risk (CVaR) to estimate potential losses in the portfolio, providing a comprehensive risk management framework.

## Purpose of the Analysis: 

The primary goal of this project is to apply Modern Portfolio Theory (MPT) principles to determine optimal asset allocation that maximizes returns while minimizing risk. By calculating the efficient frontier, we can visualize the best possible returns we can achieve for a given level of risk. The analysis of minimum variance portfolio helps in identifying the combination of stocks that will yield the least amount of volatility.

## Table of contents
- [Installation](#installation)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Key Findings](#key-findings)
- [Dependencies](#dependencies)


## Installation

To run the Portfolio Optimization Analysis project, follow these steps:
Install Anaconda: Download and install Anaconda from the official website. Anaconda includes Python and Jupyter Notebook, which are essential for running the project.

Python Version: Ensure you have Python 3.10 or above installed. Verify by running the command python --version in the terminal.

Launch Jupyter Notebook: Open Anaconda Navigator and start Jupyter Notebook. This will open a web browser tab with the Jupyter interface.

## Dataset

The project utilizes real-time data from Yahoo Finance, accessed using the yfinance library. The dataset includes the adjusted closing prices for major Indian stocks:
Reliance Industries
Adani Enterprises
Larsen & Toubro
GAIL
The data spans the last five years and is fetched dynamically, allowing for up-to-date analysis of each stock’s performance and risks.

## Project Structure

The Portfolio Optimization Analysis project includes:
Portfolio_Optimization_Analysis.ipynb: Main Jupyter Notebook containing all analyses, including computations of efficient frontiers and portfolio optimizations.
README.md: Overview of the project, installation guide, and usage instructions.

## Usage
Steps to utilize the Portfolio Optimization Analysis project:
Complete the installation steps.
Launch Jupyter Notebook and open Portfolio_Optimization_Analysis.ipynb.
Execute the code cells to compute returns, covariance, and visualize the efficient frontier.
Adjust the stock list or the timeframe as needed to explore different scenarios.

## Key Findings
Insights from the portfolio optimization include:
Efficient Frontier Analysis: Determination of the risk-return trade-offs available from different portfolio combinations.
Minimum Variance Portfolio: Identification of the portfolio composition that minimizes risk for a given return level.
Optimal Asset Allocation: Suggested weights for each stock to maximize returns per unit of risk taken.
These analyses provide crucial insights into how best to allocate investments among selected stocks to achieve desired financial outcomes.

## Dependencies
Essential Python libraries for this project:
numpy: For numerical calculations.
pandas: For data manipulation.
yfinance: For fetching stock data.
matplotlib and seaborn: For creating visualizations.

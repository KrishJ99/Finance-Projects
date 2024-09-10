# Portfolio Optimization and Risk Analysis

## Project Overview

This project focuses on portfolio optimization and risk analysis using historical stock data. The objective was to identify optimal portfolios by assessing various financial metrics and risk factors, this time leveraging diversification to achieve better risk-adjusted returns. This report details the methodology, results, and insights derived from the analysis.

## Table of Contents

1. [Introduction](#introduction)
2. [Data and Methodology](#data-and-methodology)
3. [Portfolio Optimization](#portfolio-optimization)
4. [Results and Analysis](#results-and-analysis)
5. [Comparison with Previous Project](#comparison-with-previous-project)
6. [Conclusion](#conclusion)

## Introduction

In this project, we applied portfolio optimization techniques to evaluate and compare different investment strategies. We focused on analyzing two portfolios: the Minimum Risk Portfolio and the Maximum Sharpe Ratio Portfolio. The goal was to assess their performance, risk, and return metrics, and to understand the impact of diversification on these portfolios.

## Data and Methodology

### Data

- **Historical Stock Data:** Includes daily returns for a diversified set of stocks from different sectors and markets.
- **Time Frame:** Data spans from 2015 to 2024, with training data from 2015 to 2023 and test data from 2023 to 2024.

### Methodology

1. **Data Preparation:**
   - Collected and cleaned historical price data.
   - Calculated daily returns and other financial metrics.

2. **Portfolio Optimization:**
   - Simulated 1,000,000 portfolios to explore the efficient frontier.
   - Identified the Maximum Sharpe Ratio Portfolio and Minimum Risk Portfolio based on historical data.

3. **Risk Analysis:**
   - Evaluated performance using returns, volatility, and Sharpe ratio.

4. **Testing and Evaluation:**
   - Compared expected returns with actual returns from the test data.
   - Assessed the portfolio values based on historical performance.

## Portfolio Optimization

### Minimum Risk Portfolio

- **Annualized Return:** 10.90%
- **Volatility:** 9.35%

### Maximum Sharpe Ratio Portfolio

- **Annualized Return:** 40.18%
- **Volatility:** 13.41%

## Results and Analysis

### Expected vs. Actual Returns

- **Minimum Risk Portfolio:**
  - **Expected Return (Adjusted):** $11,089.96
  - **Actual Return:** Ending value of $11,277.11 from an initial $10,000 investment

- **Maximum Sharpe Ratio Portfolio:**
  - **Expected Return (Adjusted):** $14,018.05
  - **Actual Return:** Ending value of $15,247.25 from an initial $10,000 investment



## Comparison with Previous Project

### Previous Project Summary

- **Stocks Analyzed:** AAPL, AMZN, GOOGL, MSFT, NVDA
- **Maximum Sharpe Ratio Portfolio:**
  - **Annualized Return:** 73%
  - **Volatility (Annualized):** 48.88%
  - **Maximum Drawdown:** -63.26%
- **Minimum Volatility Portfolio:**
  - **Annualized Return:** 29%
  - **Volatility (Annualized):** 27.38%

### Comparative Insights

- **Diversification Impact:** The current project’s diversified portfolio approach resulted in significantly lower volatility compared to the previous project’s concentrated technology-focused portfolios.
- **Sharpe Ratio Improvement:** The Maximum Sharpe Ratio Portfolio in the current project achieved a higher Sharpe Ratio of 3.00, compared to 1.00 in the previous project, reflecting better risk-adjusted returns.
- **Risk and Return Balance:** The diversified approach led to competitive returns with reduced risk, emphasizing the benefits of spreading investments across various sectors and markets.

## Conclusion

This project highlights the value of diversification in portfolio management. By incorporating a broad range of stocks across different sectors, the current project demonstrated substantial improvements in reducing volatility and achieving better risk-adjusted returns compared to a previous project focused on a narrow selection of technology stocks. The findings underscore the practical benefits of diversification for managing risk and optimizing performance.

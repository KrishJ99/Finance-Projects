# Multi-Asset Investment Analysis Project

## Overview

This project aims to analyze a diverse set of investment assets, including Treasury bonds, corporate bonds, currency ETFs, commodities, and gold, by evaluating their expected returns and risk profiles. The analysis employs various statistical metrics, including Value at Risk (VaR), Conditional VaR (CVaR), maximum drawdown, kurtosis, Sharpe ratio, and Sortino ratio, to provide a comprehensive view of each asset's risk-return characteristics.

## Objectives

- **Assess Investment Opportunities**: Evaluate different asset classes to identify suitable investments based on risk tolerance and market conditions.
- **Quantitative Risk Analysis**: Utilize statistical measures to quantify and compare the risk profiles of each asset.
- **Portfolio Optimization**: Suggest optimal asset allocations to balance risk and return for diverse investor profiles.

## Methodology

### 1. Data Collection
- Gathered historical price data for various asset classes including TLT (Treasury Bonds), LQD (Investment Grade Corporate Bonds), BND (Total Bond Market), FXE (Euro Currency ETF), CYB (Chinese Yuan Currency ETF), FXY (Japanese Yen Currency ETF), GLD (Gold ETF), USO (Oil ETF), and DBA (Agricultural Commodities ETF).

### 2. Statistical Analysis
- **Risk Statistical Analysis**:
  - Calculated **Value at Risk (VaR)** at the 5% level to estimate potential losses in normal market conditions.
  - Computed **Conditional VaR (CVaR)** to understand expected losses exceeding the VaR threshold.
  - Analyzed **Maximum Drawdown** to assess the largest drop from a peak to a trough, indicating downside risk.
  - Evaluated **Kurtosis** to measure the "tailedness" of the return distribution, indicating the likelihood of extreme price movements.

- **Performance Metrics**:
  - Calculated **Sharpe Ratio** to assess risk-adjusted returns, measuring how much excess return is received for the extra volatility endured.
  - Computed **Sortino Ratio** to focus on downside risk, differentiating harmful volatility from total volatility, thus providing a clearer picture of an investment's risk-return profile.

## Findings

### Standardized Investment Metrics
| Security | Standardized Expected Final Price | Standardized Standard Deviation | Standardized VaR (5%) | Standardized CVaR | Standardized Sharpe Ratio | Standardized Sortino Ratio | Standardized Maximum Drawdown | Standardized Kurtosis |
|----------|-----------------------------------|-------------------------------|-----------------------|--------------------|---------------------------|----------------------------|-------------------------------|----------------------|
| TLT      | -0.25                             | -0.72                         | -0.02                 | 0.02               | 1.64                      | 1.59                       | -0.76                         | -0.66                |
| LQD      | -1.26                             | -0.92                         | -1.16                 | -1.14              | 0.71                      | 0.64                       | -0.62                         | -0.33                |
| BND      | -1.36                             | -0.85                         | -1.30                 | -1.29              | -0.52                     | -0.54                      | -0.12                         | -0.49                |
| FXE      | 0.32                              | -0.45                         | 0.57                  | 0.61               | 0.88                      | 1.07                       | -0.60                         | -0.38                |
| CYB      | -0.29                             | -0.59                         | -0.11                 | -0.09              | 0.56                      | 0.56                       | -0.47                         | -0.40                |
| FXY      | 2.23                              | 1.26                          | 2.11                  | 2.08               | -0.66                     | -0.63                      | -0.19                         | 0.25                 |
| GLD      | 0.47                              | -0.16                         | 0.59                  | 0.59               | 0.05                      | -0.06                      | -0.30                         | -0.64                |
| USO      | 0.31                              | 0.28                          | 0.22                  | 0.19               | -0.82                     | -0.85                      | 0.37                          | -0.07                |
| DBA      | -0.17                             | 2.16                          | -0.89                 | -0.97              | -1.83                     | -1.78                      | 2.68                          | 2.73                 |

### Investment Recommendations
- **TLT (Treasury Bonds)**: Recommended for conservative investors due to strong risk-adjusted returns (high Sharpe and Sortino ratios), low drawdown, and minimal VaR, indicating stable performance with fewer extreme movements.
- **CYB (Chinese Yuan Currency ETF)**: Suitable for conservative investors looking for exposure to the Yuan with minimal risk, highlighted by low maximum drawdown and VaR values.
- **DBA (Agricultural Commodities ETF)**: Appeals to speculative investors due to high kurtosis and extreme risk, ideal for those looking to capitalize on significant market movements.

### Risk Analysis Insights
- Investments with negative kurtosis, like TLT and CYB, suggest lower likelihoods of extreme price swings, making them attractive for risk-averse portfolios. Conversely, assets like DBA exhibit higher kurtosis, indicating increased chances of extreme outcomes, suited for risk-tolerant investors.

## Conclusion

This multi-asset investment analysis project provides valuable insights into the risk-return profiles of various assets, facilitating informed decision-making for diverse investor profiles. The use of robust statistical measures enables a comprehensive understanding of potential risks and rewards, guiding multi asset investment strategies.

## Future Work
- Further exploration of alternative investments and their implications for diversification.
- Development of a dynamic portfolio optimization model using machine learning techniques.


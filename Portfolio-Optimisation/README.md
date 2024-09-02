# Investment Strategy and Portfolio Optimization
Overview: In this project, we analyzed a set of 5 stocks—AAPL, AMZN, GOOGL, MSFT, and NVDA—using various portfolio optimization techniques. The goal was to identify the best investment strategies based on different risk profiles and scenarios, including:

- Simulated Portfolio Optimization for Efficient Frontier: Exploring the risk-return trade-offs to identify the optimal portfolio.
- Maximum Sharpe Ratio Portfolio: Maximizing returns per unit of risk.
- Minimum Volatility Portfolio: Minimizing risk while maintaining reasonable returns.
- Two-Stock Portfolio Optimization: Identifying the best pair of stocks for investment based on historical performance.
  
## **Key Findings:**

### **1. Efficient Frontier and Sharpe Ratio Optimization - Simulated for 100,000 portfolios**
Efficient Frontier Analysis revealed the risk-return trade-offs for portfolios formed from the 5 stocks. By calculating the Sharpe Ratio, we identified the portfolio with the highest return per unit of risk. This portfolio was found to provide the best balance between risk and return.

**Maximum Sharpe Ratio Portfolio:**
- Annualized Return: 0.73
- Volatility (Annualized): 0.4888
- Maximum Drawdown: -0.6326
- Value at Risk (95%, Annualized): -0.7160

Optimal Allocation:
- AAPL: 5.03%
- AMZN: 1.44%
- GOOGL: 1.35%
- MSFT: 1.51%
- NVDA: 90.67%


### **2. Minimum Volatility Portfolio - Simulated for 100,000 portfolios**
Minimum Volatility Analysis focused on reducing portfolio risk by finding the least volatile combination of the 5 stocks.

**Minimum Volatility Portfolio:**
- Annualized Return: 0.29
- Volatility (Annualized): 0.2738
- Maximum Drawdown: -0.3702
- Value at Risk (95%, Annualized): -0.4230

Optimal Allocation:
- AAPL: 24.73%
- AMZN: 12.11%
- GOOGL: 27.94%
- MSFT: 35.13%
- NVDA: 0.08%


### **3. Optimal Two-Stock Portfolio**
Two-Stock Portfolio Analysis was conducted to determine the best pair of stocks for a £1,000 investment with optimal allocation.

Best Two-Stock Combination: AAPL and NVDA

Optimal Allocation:
- AAPL: 10% (£100)
- NVDA: 90% (£900)

Final Portfolio Value: £31,404.59
Total Return: 3140.46% (£30,404.59)

Risk Metrics:
- Volatility (Annualized): 0.4914
- Maximum Drawdown: -0.6271
- Value at Risk (95%, Annualized): -0.7128
- Sharpe Ratio: 1.4395



## **Recommendations**

### **For Conservative Investors (Minimize Risk):**
The Minimum Volatility Portfolio is ideal for conservative investors who prioritize capital preservation and stable returns. This portfolio, with the lowest annualized volatility at 0.27, focuses on minimizing risk while still offering a reasonable return. The final portfolio value of £4,273.49 represents a total return of 327.35% on the initial £1,000 investment.

Recommended Allocation for £1000 investment at the start of 2019:
- AAPL: 27.37% (£273.71)
- AMZN: 12.9% (£129.01)
- GOOGL: 27.07% (£270.70)
- MSFT: 35.65% (£326.50)
- NVDA: 0.08% (£0.08)
  
Final Portfolio Value: £4,273.49
Total Return: 327.35% (£3,273.49)
  
This allocation provides a diversified, lower-risk portfolio with steady growth over time, making it suitable for risk-averse investors.



### **For Risk-Tolerant Investors (Maximize Return/Risk Ratio):**
Investors with a higher risk tolerance, seeking to maximize returns relative to risk, should consider the Maximum Sharpe Ratio Portfolio. This portfolio aims to optimize the return per unit of risk, resulting in a total return of 2801.17% and a final portfolio value of £29,011.67 from an initial £1,000 investment.

Recommended Allocation for £1000 investment at the start of 2019:
- AAPL: 2.91% (£29.14)
- AMZN: 2.69% (£26.93)
- GOOGL: 2.87% (£28.70)
- MSFT: 2.35% (£23.51)
- NVDA: 89.17% (£891.72)

Final Portfolio Value: £29,011.67

Total Return: 2801.17% (£28,011.67)
  
This portfolio is highly concentrated in NVDA, reflecting its significant contribution to overall returns, and is ideal for investors willing to accept higher short-term volatility in exchange for potentially substantial long-term gains.



### **For High Potential, High Risk Investors:**
For investors with a very high-risk appetite and a focus on maximizing potential returns, the Best Two-Stock Combination of AAPL and NVDA provides an exceptional opportunity. This portfolio delivered an outstanding total return of 3140.46%, resulting in a final portfolio value of £31,404.59 from an initial £1,000 investment.

Optimal Allocation for £1000 investment at the start of 2019:
- AAPL: 10% (£100)
- NVDA: 90% (£900)

Final Portfolio Value: £31,404.59
Total Return: 3140.46% (£30,404.59)

This strategy suits investors who are comfortable with large fluctuations in portfolio value and are willing to risk substantial drawdowns in exchange for the possibility of outsized returns. The concentrated investment in NVDA maximizes potential gains but comes with increased risk due to the lack of diversification.


## **Overall Investment Strategy:**
**Diversification vs. Concentration:** The 5-stock portfolios offer a more balanced approach with diversification benefits, spreading risk across multiple assets and sectors. In contrast, the concentrated two-stock portfolio focuses on maximizing returns but at the cost of significantly higher risk.

**Tailoring to Risk Appetite:** Investors should select the portfolio that aligns with their individual risk tolerance and investment goals. Conservative investors may prefer the stability and consistent growth of the minimum volatility portfolio, while aggressive investors might be drawn to the high return potential of the maximum Sharpe ratio or two-stock portfolios.

**Long-Term Considerations:** Each portfolio's suitability depends on the investor's time horizon and risk tolerance. While high-risk portfolios can deliver substantial returns, they may not be appropriate for all investors, especially those with shorter time frames or those approaching retirement.

## Summary
In summary, this project highlights the importance of aligning investment strategies with individual risk profiles. It offers tailored solutions ranging from conservative, risk-minimizing portfolios to aggressive, high-reward strategies, enabling investors to make informed decisions based on their financial goals.

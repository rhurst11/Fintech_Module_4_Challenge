# Fintech_Module_4_Challenge
## Evaluating Funds against the market

### Purpose:
  
  
## Summary of Analysis

### Analyze the Performance

### Analyze the Volatility

**Proposed Question** Based on the box plot visualization of just the four fund portfolios, which fund was the most volatile (with the greatest spread) and which was the least volatile (with the smallest spread)?

**Answer** The Berkshire Hathaway Fund had the greatest spread. Tiger Global Management LLC appears to have the smallest spread based on its total range including outliers and also has the smallest spread between its lower and upper quartiles.


### Analyze the Risk

**Question 1**  Based on the annualized standard deviation, which portfolios pose more risk than the S&P 500?

**Answer 1** # Based on the annualized standard deviation, no portfolios pose more risk than the S&P 500 for any signifcant amount of time. On two instances, Berkshire Hathaway Inc had a higher rolling standard deviation relative to the S&P 500, but these instances were short-lived and don't represent any sort of trend.

**Question 2** Based on the rolling metrics, does the risk of each portfolio increase at the same time that the risk of the S&P 500 increases?

**Answer 2** # Based on the rolling metrics, the risk of each portfolio seems to increase slightly as the S&P 500 increases, but all of these funds react with significantly less volatiliy than the S&P 500. Even during the spike in volatility towards the early middle of 2020, presumably from the covid crash, none of the funds came close to the volatility of the S&P 500.

**Question 3** Based on the rolling standard deviations of only the four fund portfolios, which portfolio poses the most risk? Does this change over time? 

**Answer 3** # 

Based on the rolling standard deviations for the four fund portfolios, the Berkshire Hathaway fund posed the highest risk over the longest period of time. 

The only time periods where the Berkshire fund was surpassed in terms of risk (assuming we are gauging risk solely off of the annualized std dev), were in the beginning and the end of the data set for brief trends that soon waned in momentum.


### Analyze the Risk-Return Profile

Berkshire Hathaway INC offers the best risk-return profile according to the above comparison. In contrast, Paulson and Co INC appears to offer the worst risk-return.

### Conclusion and Choice of Fund for Inclusion in Company Offerings

I would recommend the Tiger Management LLC portfolio for inclusion in my firm's suite of fund offerings for the following reasons: The Tiger LLC portfolio offers a competitive sharpe ratio value, representing a good return on assumed risk, compared with the other three funds, but it also remains less sensitive to market movements than funds that otherwise perform similarly in terms of return on risk. The Tiger Management LLC fund has a solid track record of maintaining a low positive beta value, meaning it won't react to market movements as much as some of the other funds with more extreme beta value trends. 
Given that my company wishes to offer funds that assist clients in planning for retirement, the Tiger fund seems like the logical choice as it possesses a conservative risk profile while still providing growth near the rate of the broader market.

## Visual Analysis

### Cumulative Returns

![alt text](https://github.com/rhurst11/Fintech_Module_4_Challenge/blob/main/Workspace/Screenshots_Mod_4_Challenge/Screen%20Shot%202021-07-25%20at%2012.10.03%20PM.png)

### Daily Returns

![alt text](https://github.com/rhurst11/Fintech_Module_4_Challenge/blob/main/Workspace/Screenshots_Mod_4_Challenge/Screen%20Shot%202021-07-25%20at%2012.09.55%20PM.png)

### Daily Returns Dispersion of Funds Only

![alt text](https://github.com/rhurst11/Fintech_Module_4_Challenge/blob/main/Workspace/Screenshots_Mod_4_Challenge/Screen%20Shot%202021-07-25%20at%2012.10.33%20PM.png)

### 21 Day Rolling Standard Deviation

![alt text](https://github.com/rhurst11/Fintech_Module_4_Challenge/blob/main/Workspace/Screenshots_Mod_4_Challenge/Screen%20Shot%202021-07-25%20at%2012.10.47%20PM.png)

### 21 Day Rolling Standard Deviation Funds Only

![alt text](https://github.com/rhurst11/Fintech_Module_4_Challenge/blob/main/Workspace/Screenshots_Mod_4_Challenge/Screen%20Shot%202021-07-25%20at%2012.10.53%20PM.png)

### Annualized Sharpe Ratios

![alt text](https://github.com/rhurst11/Fintech_Module_4_Challenge/blob/main/Workspace/Screenshots_Mod_4_Challenge/Screen%20Shot%202021-07-25%20at%2011.59.04%20AM.png)

### Tiger Global Managament 60 Day Rolling Beta

![alt text](https://github.com/rhurst11/Fintech_Module_4_Challenge/blob/main/Workspace/Screenshots_Mod_4_Challenge/Screen%20Shot%202021-07-25%20at%2012.00.49%20PM.png)

### Berkshire Hathaway Fund 60 Day Rolling Beta

![alt text](https://github.com/rhurst11/Fintech_Module_4_Challenge/blob/main/Workspace/Screenshots_Mod_4_Challenge/Screen%20Shot%202021-07-25%20at%2012.00.42%20PM.png)

### Overlay Plot of Tiger and Berkshire 60 Day Rolling Betas
![alt text](https://github.com/rhurst11/Fintech_Module_4_Challenge/blob/main/Workspace/Screenshots_Mod_4_Challenge/Screen%20Shot%202021-07-25%20at%2012.06.10%20PM.png)
  
## Software Requirements:
  Python -- version 3.7.10,
  Conda -- version 4.10.3,
  Jupyter Lab -- version 3.0.14
  
  
  Libraries:
  Pandas,
  pathlib,
  NumPy,
  %matplotlib

# Performance Analysis of Tesla vs NYSE Using Financial Ratios

In this project, we analyzed the performance of Tesla Inc. over the past year and compared it with the NYSE Composite Index. Using daily price data for both Tesla and NYSE, 
we calculated returns and applied several well-known financial performance metrics. These include the Sharpe Ratio, Treynor Ratio, Jensen’s Alpha, and the Information Ratio. 
All calculations were performed using Microsoft Excel.

# Data Collection and Preparation

We obtained one year of historical daily price data for both Tesla and the NYSE index. From these prices, we calculated the daily returns and then annualized them to estimate the annual return for each asset. We also calculated the annual standard deviation (as a measure of risk), beta values (for market risk), and tracking error (for the Information Ratio).

The risk-free rate was assumed to be 1.5% for the year. These inputs formed the basis for calculating each performance metric.

# Sharpe Ratio

The Sharpe Ratio measures the excess return an asset earns per unit of total risk. It is calculated using the formula:

![image](https://github.com/user-attachments/assets/b84af9f6-7df6-4a3e-89ca-11bace976eec)

Where:



![image](https://github.com/user-attachments/assets/858a2cab-3274-40c0-8258-c13eaad9d394)

A higher Sharpe Ratio indicates a better risk-adjusted return. In our results, both Tesla and NYSE had negative Sharpe Ratios, indicating that neither asset delivered a return greater than the risk-free rate, after adjusting for volatility.

# Treynor Ratio

The Treynor Ratio is similar to the Sharpe Ratio but only considers systematic risk (measured by beta), not total volatility. The formula is:

![image](https://github.com/user-attachments/assets/0ceb38e4-c2e3-4f65-957a-019e69ddb491)

This ratio tells us how much return is generated per unit of market risk. Again, both Tesla and NYSE had negative Treynor Ratios, reflecting underperformance relative to their market exposure.

# Jensen’s Alpha

Jensen’s Alpha evaluates whether a security has performed better or worse than expected under the Capital Asset Pricing Model (CAPM). The formula is:

![image](https://github.com/user-attachments/assets/74402b0c-1edc-4464-9c54-16e61546fa39)

Where Rm is the market return. A positive alpha indicates outperformance. Tesla had a very high positive Jensen’s Alpha, which was somewhat misleading due to the use of Tesla’s own return as the market return, highlighting the importance of choosing an appropriate benchmark. NYSE showed a neutral alpha close to zero.


# Information Ratio

The Information Ratio compares a portfolio’s excess return over a benchmark to the volatility of that excess return. It is given by:

![image](https://github.com/user-attachments/assets/a1f1989f-f616-475c-b3df-c50461d46903)

Where Rb is the benchmark return, and tracking error is the standard deviation of the difference in returns. Both Tesla and NYSE had negative Information Ratios, meaning they underperformed their benchmarks (10% for NYSE and 77% for Tesla), and did so with high inconsistency.


# Conclusion

All financial ratios were calculated correctly in Excel using standard formulas. 
The results reflect the actual performance of Tesla and NYSE over the past year. 
Negative values in these ratios do not imply errors—they highlight the fact that both assets underperformed, either compared to the risk-free rate or a benchmark. 
This project demonstrates how Excel can be used to apply core financial analysis concepts and interpret real market performance.


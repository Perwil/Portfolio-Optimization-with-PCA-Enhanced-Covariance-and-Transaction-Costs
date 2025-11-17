# Portfolio-Optimization-with-PCA-Enhanced-Covariance-and-Transaction-Costs
Developed and deployed an active equity portfolio solution utilizing Principal Component Analysis for high-precision covariance estimation and transaction cost modeling. Achieved risk-adjusted, stable allocations with significant improvement in portfolio return and cost efficiency.

# Solution Approach
##  Evaluated Risk Measures for S&P 500 and 10 other stocks
1. Historical data for the S&P 500 Index and 10 additional stocks of your choice using yfinance.
All functions should accept start_date and end_date as input parameters to define the analysis period.
2. Implemented the following functions:
A. Compute Average Daily Return:
B. Calculate the mean daily return over the specified period.
C. Compute Daily Volatility / Standard Deviation:
D. Measure the standard deviation of daily returns over the specified period.
E. Compute and determine Maximum Drawdown a specific period:
F. Calculate the tracking error of each stock relative to the S&P 500 Index over the specified period.
G. Calculate the Sharpe ratio using the average daily return and daily volatility over the specified period.


PCA to extract systematic risk for improved covariance estimation

Integration of asset-specific idiosyncratic risk for robust allocation

CVXPY-based constrained optimization, balancing expected return, variance, and trading costs

Main Results & Data Highlights
Present actionable quantitative outcomes up front:

Portfolio of top S&P 500 equities—optimized for 252 trading days, starting from $1 million capital

Sharpe Ratios: e.g., Apple 0.0496, Microsoft 0.0258, Johnson & Johnson 0.0746​

Transaction cost per rebalance: $200.00​

Projected annualized return: $105,021.92​

Weights and trades explicitly shown for transparency

Metric	Value
Holding Period	252 days
Initial Investment	$1,000,000
Expected Return	$105,021.92
Transaction Cost	$200.00
Industry-Relevant Skills
List technologies and methodologies as both badges and keywords:

Python, Pandas, NumPy, yFinance API

PCA, Portfolio Theory, Risk Metrics (VaR, CVaR, Tracking Error)

CVXPY, Quadratic Programming, Data Visualization

Financial Modeling Best Practices, Transaction Cost Analysis

Impact & What Makes It Stand Out
“Brings together state-of-the-art quantitative risk modeling and practical execution constraints in a scalable framework applicable to real trading environments.”

“Demonstrated robust estimation under high-dimensionality, balancing theoretical rigor with realistic implementation.”

How to Run & Explore
Give quickstart instructions for notebook execution and suggestions for parameter changes, so readers can experiment and replicate:

Requirements.txt (CVXPY, scikit-learn, yFinance)

Step-by-step command for running simulations or updating tickers

Final Touches
Add visuals: covariance heatmap, weight barplot, risk/return chart

Link to supplementary report or presentation slide deck (if available)

State you welcome professional connection and feedback from practitioners

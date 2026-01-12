# Market-Beating-Portfolio-Builder
End-to-end Python pipeline that pulls/cleans equity data (yfinance), ranks stocks using a multi-factor signal (CAPM residual momentum, Sharpe, volatility penalty, liquidity), runs 10,000-path CAPM expected-return, and builds a constraint-aware long-only portfolio with share-based allocation + commissions. Benchmarked vs S&amp;P 500 and TSX Composite.

## Input: Stock Universe (CSV Required)
This project requires importing a CSV file containing the list of stocks you want to filter and evaluate (your stock universe).

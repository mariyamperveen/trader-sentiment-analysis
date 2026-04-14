Overview

This project analyzes how Bitcoin market sentiment (Fear, Neutral, Greed, Extreme Fear, Extreme Greed) impacts trader behavior and performance on Hyperliquid.

The objective is to understand how sentiment affects:

Trader profitability
Risk-taking behavior
Trade frequency
Position sizing
Long/short bias
Project Structure
├── notebook.ipynb        # Full analysis (Part A, B, C)
├── data/
│   ├── sentiment.csv     # Market sentiment data
│   ├── trades.csv        # Hyperliquid trades
├── outputs/
│   ├── charts/           
│             
└── README.md
Setup & How to Run
1. Install dependencies
pip install pandas numpy matplotlib seaborn
2. Run notebook
jupyter notebook notebook.ipynb

Run all cells in order:

Data preparation
Feature engineering
Analysis
Insights & strategy
Methodology
Merged trader dataset with sentiment data on date level
Created key metrics:
Closed PnL
Win rate
Number of trades
Position size (USD)
Long/short ratio
Analyzed behavior across sentiment regimes
Segmented traders based on activity, size, and performance
Key Insights
Performance vs Sentiment
Traders perform better during Greed and Extreme Greed periods
Fear periods show lower profitability and weaker win rates
Behavioral Changes
Higher trade activity during Greed phases
Larger position sizes in bullish sentiment
Strong long bias during Greed
Reduced activity during Fear
Trader Segments
High activity traders are more sentiment-sensitive
Large position traders show higher volatility
High win-rate traders remain more stable across regimes
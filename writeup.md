

# 2. Writeup (1-Page Summary – Clean Version)

```markdown
# Trader Performance vs Market Sentiment – Summary Report

## 1. Methodology

This project analyzes the relationship between Bitcoin market sentiment and trader behavior on the Hyperliquid trading platform.

Two datasets were used:
- Daily market sentiment data (Fear, Neutral, Greed, Extreme Fear, Extreme Greed)
- Historical trader execution data

Both datasets were merged on the date level to align trading activity with sentiment conditions.

The following metrics were constructed:
- Daily closed PnL per account
- Win rate
- Number of trades per day
- Average position size
- Long/short ratio

In addition, traders were segmented based on activity levels, position sizes, and win rates to understand behavioral differences across groups.



## 2. Key Insights

### Performance vs Sentiment
Trader performance varies across sentiment regimes. Greed and Extreme Greed periods generally show higher profitability, while Fear periods are associated with weaker performance and lower win rates.

### Behavioral Changes
Trading activity increases during Greed phases, with traders executing more trades and taking larger positions. In contrast, Fear periods lead to reduced participation and lower risk-taking.

A strong long bias is also observed during Greed conditions, indicating directional confidence in bullish markets.

### Trader Segmentation
High activity traders are more sensitive to sentiment changes. Traders with larger position sizes experience higher volatility in performance. High win-rate traders remain relatively stable across different sentiment regimes.



## 3. Strategy Recommendations

### Position Sizing Strategy
Position sizes should be reduced during Greed phases to avoid overexposure during potentially overheated market conditions. During Fear phases, traders should adopt a conservative approach and focus only on high-confidence setups.

### Sentiment-Aware Trading Behavior
Trading activity should be increased during Greed periods when market momentum is stronger. During Fear periods, traders should avoid overtrading and focus on selective opportunities.



## 4. Conclusion

Market sentiment plays a significant role in shaping trader behavior and performance. A strategy that adapts to sentiment conditions can improve decision-making, reduce risk, and enhance overall consistency in trading performance.

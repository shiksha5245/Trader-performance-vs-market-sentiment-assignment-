Trader Performance vs. Market Sentiment

Overview

This project combines Hyperliquid trading data ("historical_data.csv") with the Bitcoin Fear & Greed Index ("fear_greed_index.csv") to investigate how market sentiment influences trader behavior, profitability, and risk exposure.

By integrating these datasets, the analysis reveals clear relationships between market psychology and trading performance, providing actionable insights for building sentiment-aware trading strategies.



Key Findings

1. Win Rate Increases with Market Optimism

A strong positive relationship exists between market sentiment and trader success.

Market Sentiment| Win Rate
Extreme Fear| 29.3%
Fear| 38.2%
Neutral| 49.5%
Greed| 43.6%
Extreme Greed| 55.3%

Insight: As market sentiment becomes more bullish, trader win rates improve significantly, reaching their highest level during periods of Extreme Greed.



2. Profitability Changes Across Market Cycles

Although traders remain profitable on average across all sentiment categories, the magnitude of profits varies considerably.

Market Sentiment| Average Closed PnL
Extreme Fear| $1.89
Fear| $128.29
Neutral| $27.09
Greed| $53.99
Extreme Greed| $205.82

Insight: Profit generation accelerates during bullish markets, with Extreme Greed producing the highest average returns per trade.



3. Trading Activity is Highly Sentiment-Driven

More than 72% of total trading volume and executions occur during either Fear or Greed market conditions.

This indicates that traders tend to participate more aggressively during emotionally charged markets rather than during stable or range-bound periods.



Behavioral Analysis

Extreme Fear

- Lowest win rate (29.3%)
- Frequent small losses due to panic selling and stop-loss triggers
- Positive overall profitability suggests a few large winning trades offset many small losses
- Strong evidence of trend-reversal opportunities



Extreme Greed

- Highest win rate (55.3%)
- Momentum-based trading performs exceptionally well
- FOMO-driven strategies appear consistently profitable
- High profitability may conceal excessive leverage and elevated downside risk if market sentiment reverses



Trading Strategy Recommendations

Market Sentiment| Recommended Strategy
Extreme Fear| Preserve capital, reduce position size by 50%, tighten stop-losses, or remain in stablecoins
Fear| Accumulate quality assets using spot positions or low-leverage longs near major support levels
Neutral| Deploy mean-reversion strategies, grid bots, or range-trading systems
Greed| Follow established trends with trailing stop-loss protection
Extreme Greed| Secure profits, reduce leverage, and avoid aggressively adding positions near local market tops



Risk Management Recommendation

A practical enhancement for algorithmic trading systems is to integrate the Fear & Greed Index into the risk management framework.

Suggested Rule:

- Monitor the daily Fear & Greed Index.
- When the index rises above 80 (Extreme Greed):
  - Automatically reduce maximum leverage.
  - Scale down new position sizes.
  - Increase profit-taking frequency.
  - Apply stricter risk controls to reduce exposure before potential market reversals.

This sentiment-aware approach can help minimize liquidation risk during overheated market conditions.



Conclusion

The analysis demonstrates that market sentiment has a measurable impact on trader performance.

Key observations include:

- Win rates improve as market sentiment becomes more optimistic.
- Average profitability is highest during Extreme Greed.
- Trading activity is concentrated during emotionally driven market phases.
- Incorporating sentiment indicators into trading systems enables more adaptive position sizing, improved risk management, and stronger long-term performance.

Overall, this project highlights how combining market sentiment data with trading performance analytics can produce valuable insights for both discretionary traders and automated trading systems.

# ETH Swing

## Trader Request

> "I’m looking for a swing trade on ETH. Nothing crazy, just buy the dip when it’s oversold but still in an overall uptrend. I like Bollinger Bands and RSI."

## Agent Interpretation

**Strategy:** Swing capture on ETH/USD
**Timeframe:** 4-hour candles
**Direction:** Long only

**Entry conditions:**
- RSI(14) is below 35 — price is oversold
- Price touches or closes below the lower Bollinger Band
- SuperTrend indicator is still bullish
- We only take the trade if the daily trend is up

**Exit / Risk:**
- Stop loss at the recent swing low minus 1.2%
- Trailing take profit using a 3R trailing stop
- Maximum position size: 2.5% of account equity

**Why it works:**
Oversold bounces within an uptrend have a high probability of short-term reversal. The Bollinger Band touch gives a clear entry zone, and the SuperTrend keeps us aligned with the bigger trend.

## Status
- Paper trading live
- Backtest Sharpe: 1.64
- Win rate: 58%
- Trades: 43

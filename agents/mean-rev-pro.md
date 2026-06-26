# Mean Rev Pro

## Trader Request

> "I want a mean reversion strategy. When price gets stretched too far from its average, snap back. But I want confirmation — not just blindly buying the dip."

## Agent Interpretation

**Strategy:** Mean reversion on major pairs and indices
**Timeframe:** 5-minute candles
**Direction:** Long and short

**Entry conditions:**
- Z-score of price vs 50-period SMA is below -2.2
- Price touches the lower Keltner Channel
- Bullish RSI divergence detected over the last 5 candles
- For shorts: reverse — z-score above +2.2, upper Keltner, bearish divergence

**Exit / Risk:**
- Stop loss at 1.8% adverse move from entry
- Take profit target at the 50-period SMA
- Maximum position size: 3% of account equity

**Why it works:**
Price extremes with momentum divergence often revert to the mean. The Keltner Channel gives a volatility-adjusted entry zone instead of a fixed percentage.

## Status
- Live trading
- Backtest Sharpe: 2.04
- Win rate: 71%
- Trades: 214

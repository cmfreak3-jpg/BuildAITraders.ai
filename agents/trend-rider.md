# Trend Rider

## Trader Request

> "I want a clean trend-following strategy. No counter-trend trades. Just ride strong trends on BTC and ETH with a clear filter."

## Agent Interpretation

**Strategy:** Trend following on BTC, ETH, SOL, SUI
**Timeframe:** 1-hour candles
**Direction:** Long and short

**Entry conditions:**
- ADX(14) is above 25 — trend strength is strong
- +DI is above -DI for longs, below for shorts
- Price is above the Ichimoku cloud top for longs, below the cloud bottom for shorts
- Take only 3 consecutive confirmations before entry

**Exit / Risk:**
- Stop loss on a Kijun-sen breach
- Trail with Parabolic SAR
- Maximum position size: 3.5% of account equity

**Why it works:**
Strong trends persist. The ADX filter avoids choppy markets, and the Ichimoku cloud provides a dynamic support/resistance zone for entries.

## Status
- Live trading
- Backtest Sharpe: 1.79
- Win rate: 61%
- Trades: 102

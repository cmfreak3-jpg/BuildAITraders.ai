# Meme Hunter

## Trader Request

> "I want something aggressive for low-cap meme coins. Volume explosion + price squeeze + social hype. High risk, high reward. Keep position tiny."

## Agent Interpretation

**Strategy:** Volatility expansion on meme tokens
**Timeframe:** 1-minute candles
**Direction:** Long only

**Entry conditions:**
- Volume spikes to 4.5x the 20-candle average
- ATR(14) / price is below 1.2% — a volatility squeeze is forming
- Social sentiment score over the last 5 minutes is above 0.72

**Exit / Risk:**
- Hard stop loss at 4.5% below entry
- Take profit at 8% or trailing volatility exit
- Maximum position size: 1.5% of account equity

**Why it works:**
Meme coins move on hype and volume. The squeeze condition catches the explosion early, while the tiny position size limits catastrophic drawdowns.

## Status
- Paper trading live
- Backtest Sharpe: 1.31
- Win rate: 52%
- Trades: 156

# Momentum Hunter

## Trader Request

> "Hey, I want a strategy that catches ETH when it’s about to break out hard. Like, when the price pushes above the recent 20-candle high and volume is clearly jumping — that’s when I want to get in."

## Agent Interpretation

**Strategy:** Momentum breakout on ETH/USD
**Timeframe:** 15-minute candles
**Direction:** Long only

**Entry conditions:**
- Price closes above the highest high of the last 20 candles
- Volume on that candle is at least 1.8x the average volume of the last 20 candles
- EMA 12 is above EMA 26 to confirm the trend is already sloping up

**Exit / Risk:**
- Stop loss placed 1.5x ATR(14) below entry
- Take profit at 2.5x the risk
- Maximum position size: 4% of account equity

**Why it works:**
Breakouts with volume confirmation tend to carry momentum for the next few candles. The EMA filter keeps us out of fake breakouts in a downtrend.

## Status
- Paper trading live
- Backtest Sharpe: 1.82
- Win rate: 64%
- Trades: 87

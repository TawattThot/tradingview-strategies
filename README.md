# TradingView strategies

Pine Script strategies for Joseph. Free — paste into TradingView.

## VWAP + RSI (1H) — exchange session VWAP

- File: [`vwap_rsi_1h.pine`](vwap_rsi_1h.pine)
- Best when the exchange session VWAP reset matches how you trade

## Anchored VWAP + RSI (1H) — crypto / 24-7

- File: [`vwap_anchored_rsi_1h.pine`](vwap_anchored_rsi_1h.pine)
- VWAP resets on **Daily / Weekly / Monthly** (default Weekly) instead of a cash-session open
- Same pullback + RSI logic as the session version

### Install

1. TradingView → Pine Editor → New strategy  
2. Paste file → Save → Add to chart  
3. Timeframe **1 hour**  
4. Strategy Tester before live size  

Default anchor for crypto: **W** (weekly). Try **D** if you want a faster fair-value reset.

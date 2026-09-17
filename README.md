# TradingView strategies

Pine Script strategies for Joseph. Free / paste into TradingView.

## VWAP + RSI (1H)

- File: [`vwap_rsi_1h.pine`](vwap_rsi_1h.pine)
- Chart: **1 hour**
- VWAP = fair value; RSI = momentum complement
- Logic: pullback to VWAP/−SD band, reclaim VWAP with RSI on your side; ATR stop/target

### Install
1. TradingView → Pine Editor → Open → New strategy
2. Paste the file contents → Save → Add to chart
3. Set chart timeframe to **1H**
4. Run Strategy Tester; tweak inputs for your symbol

# Technical Indicators — Elite Reference Guide

## RSI (Relative Strength Index)
- **Period**: 14 (standard), 7 (scalp), 21 (position)
- **Overbought**: >70 (extreme: >80)
- **Oversold**: <30 (extreme: <20)
- **Key Signals**:
  - Bullish Divergence: Price makes LL, RSI makes HL → Reversal signal
  - Bearish Divergence: Price makes HH, RSI makes LH → Reversal signal
  - Hidden Bull Div: Price HL, RSI LL → Trend continuation up
  - Hidden Bear Div: Price LH, RSI HH → Trend continuation down
  - RSI 50 cross: Above = bullish momentum; Below = bearish momentum
  - Failure swings: High-probability reversal when RSI fails to reach prior extreme

## MACD (Moving Average Convergence Divergence)
- **Settings**: 12/26/9 (standard), 5/13/1 (scalp)
- **Signals**:
  - Signal line crossover (bullish/bearish)
  - Zero line cross (stronger signal)
  - Histogram expansion/contraction
  - MACD divergence (same as RSI divergence logic)
- **Context**: Best on H4 and above. Lagging on lower TFs.

## Moving Averages
- **EMA 9/21**: Short-term trend
- **EMA 50**: Medium-term trend filter
- **EMA 100/200**: Long-term trend (institutional level)
- **SMA 200**: Major institutional S/R level on daily
- **Golden Cross**: EMA 50 crosses above EMA 200 → Bullish
- **Death Cross**: EMA 50 crosses below EMA 200 → Bearish
- **MA Confluence**: Price bouncing off cluster of MAs = strong level

## Bollinger Bands
- **Settings**: 20 SMA, 2 std dev
- **Squeeze**: Bands narrow = low volatility = explosive move incoming
- **Expansion**: Bands widen = trending market
- **%B**: Above 1 = overbought; Below 0 = oversold
- **Walking the band**: Price hugging upper/lower band in strong trend
- **W/M patterns**: W at lower band = buy; M at upper band = sell

## Volume Analysis
- **Volume Spike**: High volume on breakout = confirmation
- **Volume Dry-up**: Low volume on pullback = trend continuation
- **Volume Divergence**: Price up, volume down = weak move
- **VWAP**: Institutional benchmark; above = bullish, below = bearish
- **Volume Profile**: POC (Point of Control), VAH, VAL levels

## Stochastic RSI
- **Settings**: 14,3,3
- **Overbought**: >80
- **Oversold**: <20
- **Best use**: Timing entries within a trend; %K crossing %D

## ATR (Average True Range)
- **Use**: Setting proper stop losses (1.5–2x ATR)
- **Volatility filter**: High ATR = wider stops needed
- **Trail stop**: Use 2x ATR trailing stop for position trades

## Ichimoku Cloud
- **Above cloud**: Bullish bias
- **Below cloud**: Bearish bias
- **Inside cloud**: Uncertain/ranging
- **TK Cross**: Tenkan/Kijun cross = entry signal
- **Kumo twist**: Future cloud color change = trend shift

## Fibonacci Levels
- **Key retracements**: 0.236, 0.382, 0.5, 0.618, 0.786
- **Golden zone**: 0.618–0.786 (highest probability pullback entry)
- **Golden Pocket**: 0.618–0.65 specifically (most precise retracement entry)
- **Extensions**: 1.272, 1.414, 1.618, 2.0, 2.618 (TP targets)
- **How to draw**: Swing low to swing high (bullish), Swing high to low (bearish)
- **Best use**: Combine with OB, FVG, or SMC level in same zone = highest confluence

## VWAP (Volume Weighted Average Price)
- The average price weighted by volume — institutional benchmark
- **Price above VWAP**: Bullish — institutions trading at a discount are happy
- **Price below VWAP**: Bearish — selling pressure dominates
- **VWAP as S/R**: First test of VWAP after a gap = often strong reaction
- **Anchored VWAP**: Draw from specific dates (earnings, halving, ATH) for custom S/R levels
- Best used on intraday charts (M15–H4)

## Multi-Timeframe Divergence Protocol
When looking for high-conviction reversals, check divergence on BOTH timeframes:

1. **Weekly RSI Divergence** (for position trades — most reliable)
   - Price: new high/low
   - RSI: lower high / higher low
   - Confirmation: when weekly candle CLOSES, not just intrabar

2. **Daily RSI Divergence** (for swing trades)
   - Same logic, faster
   - Combine with Daily OB for entry precision

3. **H4 RSI Divergence** (for day trades)
   - Enter on H1 entry trigger (OB/FVG retest)

4. **Hidden Divergence** (continuation signal)
   - Price makes HL but RSI makes LL = bullish continuation (uptrend)
   - Price makes LH but RSI makes HH = bearish continuation (downtrend)

## Indicator Confluence Scoring
Rate from 0–10. Score ≥6 = valid signal.

| Indicator | Bullish Condition | Score |
|-----------|-------------------|-------|
| RSI (D1) | <40 or bullish divergence | +2 |
| MACD (H4) | Bullish crossover + histogram positive | +1 |
| EMA 200 (D1) | Price above | +1 |
| Golden Cross | EMA 50 > EMA 200 | +1 |
| Volume (D1) | Above 20-day avg on up candles | +1 |
| Stoch RSI (H4) | Crossed up from oversold | +1 |
| Bollinger | Squeeze resolved upward | +1 |
| VWAP | Price reclaimed VWAP | +1 |

**Minimum score to issue signal: 6/10**

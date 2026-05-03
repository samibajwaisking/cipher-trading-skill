# Risk Management — Institutional Framework

## The Golden Rule
**Never risk more than 1-2% of total capital on any single trade.**

## Position Size Formula

### Forex:
```
Position Size (Lots) = (Account Balance × Risk %) / (Stop Loss in Pips × Pip Value)

Example:
Account: $10,000
Risk: 1% = $100
SL: 50 pips on EUR/USD
Pip Value (standard lot): $10

Position Size = $100 / (50 × $10) = 0.2 lots (mini lot)
```

### Crypto (Spot):
```
Position Size ($) = (Account Balance × Risk %) / (Entry Price - Stop Loss Price) × Entry Price

Example:
Account: $10,000
Risk: 1% = $100
Entry: $45,000 (BTC)
Stop: $43,500 (distance = $1,500)

Position Size = ($100 / $1,500) × $45,000 = $3,000 in BTC
```

### Crypto (Futures/Leverage):
```
Margin Required = Position Size / Leverage
Max Leverage Recommendation: 
  - Scalp: 10–20x max
  - Swing: 3–10x max  
  - Position: 2–5x max
  - NEVER 50x–100x (casino, not trading)

Liquidation Buffer: Always keep 30%+ margin buffer
```

## Risk-Reward Minimums
- Scalp: Minimum 1:1.5 (not worth it below)
- Swing: Minimum 1:2
- Position: Minimum 1:3
- **Ideal target**: 1:3 to 1:5

## Portfolio Risk Rules
1. **Max open risk at once**: 5% of portfolio
2. **Max correlated trades**: Don't hold BTC long + ETH long + SOL long (all correlated — count as 1)
3. **Drawdown rule**: Stop trading if -10% drawdown in a week. Review and reset.
4. **Winning streak danger**: Don't increase size after wins — stick to fixed %. 

## Stop Loss Placement
- **Below support** (for longs): Place 1 ATR below the structure level
- **Above resistance** (for shorts): Place 1 ATR above the structure level
- **Never**: Round numbers only (e.g., exactly $50,000 — everyone puts SL there)
- **Tight SL**: Higher winrate but higher chance of getting stopped out
- **Wide SL**: Lower winrate but gives trade room to breathe

## Take Profit Strategy
- **TP1** (40% of position): Near-term resistance / 1:1 RR (lock in profit, reduce stress)
- **TP2** (40% of position): Main target / 1:2–1:3 RR
- **TP3** (20% of position): Extended target, trail stop
- Move SL to Break Even after TP1 → **Risk-free trade**

## Leverage Warning Levels
| Leverage | Risk Level | Suitable For |
|----------|------------|--------------|
| 1–3x | Low | Position trades |
| 5–10x | Medium | Swing trades |
| 10–20x | High | Experienced scalpers only |
| 25x+ | Extreme | NOT recommended |
| 50x–100x | DANGER | Avoid — liquidation trap |

---

## Liquidation Price Calculator

### Formula for Long Position:
```
Liquidation Price = Entry Price × (1 - (1/Leverage) + Maintenance Margin Rate)

Example (10x leverage, entry $50,000, maintenance margin 0.5%):
Liquidation = $50,000 × (1 - 0.1 + 0.005) = $50,000 × 0.905 = $45,250
```

### Formula for Short Position:
```
Liquidation Price = Entry Price × (1 + (1/Leverage) - Maintenance Margin Rate)
```

**Rule**: Your stop loss should trigger at minimum 15–20% BEFORE liquidation price. Never let price get close to liquidation.

---

## Drawdown Recovery Math

This is why small losses matter so much:

| Drawdown | Recovery Needed |
|----------|----------------|
| -10% | +11.1% |
| -20% | +25% |
| -30% | +42.9% |
| -40% | +66.7% |
| -50% | +100% |
| -70% | +233% |
| -90% | +900% |

**The deeper you fall, the harder recovery becomes. Small losses are NOT the enemy — large losses from broken risk rules are.**

---

## Kelly Criterion (Advanced Position Sizing)

For traders with tracked win rate data:
```
Kelly % = Win Rate – (Loss Rate / Reward:Risk Ratio)

Example:
Win Rate = 60% = 0.60
Loss Rate = 40% = 0.40
Average R:R = 1:2

Kelly = 0.60 – (0.40 / 2) = 0.60 – 0.20 = 0.40 = 40% position size

Use HALF-KELLY for safety: 20% max position size
```

Note: Only use Kelly Criterion after 200+ tracked trades with verifiable statistics.

---

## Correlation Risk Management

When multiple trades are open simultaneously:

**High Correlation (count as ONE risk unit):**
- BTC Long + ETH Long + SOL Long = correlated, not diversified
- EUR/USD Short + GBP/USD Short = correlated to USD strength
- All risk-on assets in same direction during macro event

**True Diversification:**
- BTC Long + Gold Long (both can work in USD weakness)
- Crypto Long + DXY Short (inverse correlation hedge)
- Long one sector + short another sector simultaneously

**Rule**: Never have more than 3% total correlated risk open at once.

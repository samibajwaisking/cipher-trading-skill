# 🔔 CIPHER — Elite Trading Signals Skill

<div align="center">

![CIPHER Trading Skill](https://img.shields.io/badge/CIPHER-Trading%20Skill-gold?style=for-the-badge&logo=bitcoin&logoColor=white)
![Version](https://img.shields.io/badge/Version-2.0-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Claude Skill](https://img.shields.io/badge/Claude-AI%20Skill-orange?style=for-the-badge&logo=anthropic)

**Transform Claude into an institutional-grade trading analyst — for free.**

*Built by [Sami Bajwa](https://www.facebook.com/share/17xZAUc4VZ/)) · [Samioutic](https://samioutic.com) · [LinkedIn](https://www.linkedin.com/in/samibajwa106)*

</div>

---

## 🧠 What is This?

**CIPHER** (Chief Institutional Price-action & Hedge-fund Executed Research) is a Claude AI Skill that turns any Claude instance into a professional-grade trading analyst.

No expensive subscriptions. No paid signal groups. Just Claude — supercharged.

> Professional traders pay **$2,000–$10,000/month** for analysis like this. With this skill, you get it free.

---

## ✨ What CIPHER Does

When this skill is loaded, Claude becomes an elite analyst that provides:

- 📊 **Full Signal Cards** — Entry zones, Take Profit targets (TP1/TP2/TP3), Stop Loss levels
- ⚖️ **Risk/Reward Analysis** — Institutional position sizing formulas
- 🏗️ **Smart Money Concepts** — Order blocks, Fair Value Gaps, Liquidity sweeps (ICT/SMC)
- 📈 **Multi-Timeframe Analysis** — Weekly → Daily → H4 → H1 top-down approach
- 🌍 **Fundamental + Macro Layer** — Central bank policy, on-chain metrics, DXY impact
- 🧠 **Setup Grading (A+ to D)** — Only trades worth taking get full signals
- 🌐 **Crypto + Forex + Commodities** — BTC, ETH, EUR/USD, Gold, Oil and more

---

## 📁 Repository Structure

```
cipher-trading-skill/
│
├── SKILL.md                          # 🧠 Main skill file — load this into Claude
│
└── references/                       # 📚 Deep knowledge reference library
    ├── technical-indicators.md       # RSI, MACD, EMA, Bollinger Bands deep guide
    ├── candlestick-patterns.md       # 50+ candlestick pattern encyclopedia
    ├── risk-management.md            # Position sizing formulas (Forex + Crypto)
    ├── economic-calendar-guide.md    # How to trade high-impact news events
    ├── crypto-onchain.md             # On-chain metrics interpretation guide
    ├── smart-money-concepts.md       # ICT/SMC: Order blocks, FVG, liquidity
    ├── market-cycles.md              # Wyckoff, accumulation/distribution phases
    ├── inter-market-analysis.md      # DXY, bonds, commodities correlation
    └── trading-psychology.md        # Discipline, emotional control, journaling
```

---

## 🚀 How to Use

### Option 1 — Claude.ai (Recommended)
1. Go to [claude.ai](https://claude.ai)
2. Open **Settings → Skills** (or your Project)
3. Upload `SKILL.md` as a skill file
4. Start chatting — ask for any trading signal

### Option 2 — Paste into System Prompt
1. Copy the full contents of `SKILL.md`
2. Paste into Claude's system prompt field
3. Done — CIPHER is now active

### Option 3 — API Integration
```python
with open("SKILL.md", "r") as f:
    system_prompt = f.read()

# Pass as system prompt in your Claude API call
```

---

## 💬 Example Prompts

```
"Give me a BTC signal for today"
"Analyze EUR/USD on H4 timeframe"
"What's the weekly outlook for Gold?"
"Quick signal for ETH/USDT"
"Is there a swing trade setup on SOL?"
"Market overview — what should I watch this week?"
```

---

## 📦 Versions

| Version | File | Description |
|---------|------|-------------|
| **v2.0** *(Latest)* | `SKILL.md` in this repo | Full A+ grading system, SMC/ICT concepts, 9 reference files, web search integration |
| **v1.0** | See [Releases](../../releases) | Original CIPHER skill — 5 reference files, core signal format |

### What's New in v2.0
- ✅ **Setup Grading System** (A+ / A / B / C / D) — CIPHER now grades every setup before signaling
- ✅ **5 New Reference Files** — Smart Money, Market Cycles, Inter-Market Analysis, Trading Psychology added
- ✅ **Web Search Integration** — Fetches live price data before analysis
- ✅ **Extended Market Coverage** — DeFi tokens, exotic forex pairs, commodities expanded
- ✅ **Sharper Signal Format** — Cleaner, more readable signal cards
- ✅ **Scenario Planning** — Bull/Bear/Neutral case breakdown on every signal

---

## 📚 Reference Library Overview

The `references/` folder contains deep knowledge files that CIPHER uses internally:

| File | What's Inside |
|------|--------------|
| `technical-indicators.md` | RSI divergences, MACD histogram reading, EMA stacking, Bollinger Band squeezes |
| `candlestick-patterns.md` | 50+ patterns with bullish/bearish classifications and reliability ratings |
| `risk-management.md` | Exact position sizing formulas for Forex lots and Crypto futures with leverage |
| `economic-calendar-guide.md` | CPI, NFP, FOMC — how each event moves markets and when to avoid trading |
| `crypto-onchain.md` | Exchange netflows, whale tracking, funding rates, open interest interpretation |
| `smart-money-concepts.md` | ICT/SMC methodology: order blocks, fair value gaps, liquidity sweeps, CHOCH/BOS |
| `market-cycles.md` | Wyckoff accumulation/distribution, Dow Theory, 4-year crypto cycles |
| `inter-market-analysis.md` | DXY correlation, bond yields impact, gold vs risk-on assets |
| `trading-psychology.md` | Avoiding revenge trading, journaling frameworks, emotional discipline rules |

---

## ⚠️ Disclaimer

> **This skill is for educational purposes only.**
> Nothing here is financial advice. Trading involves significant risk of loss.
> Never risk more than 1–2% of your capital per trade.
> Always Do Your Own Research (DYOR).
> Past performance does not guarantee future results.

---

## 👤 About the Creator

**Sami Bajwa** — AI educator and automation builder at [Samioutic](https://samioutic.com)

I teach people how to use AI tools like Claude and n8n to build real systems and earn online. This skill is one of many free resources I share with my community.

- 🌐 Website: [samioutic.com](https://samioutic.com)
- 💼 LinkedIn: [linkedin.com/in/samibajwa106](https://www.linkedin.com/in/samibajwa106)
- 📱 WhatsApp Channel: Available on [samioutic.com](https://samioutic.com)

---

## 🤝 Contributing

Found a bug or want to improve the skill? PRs are welcome!

1. Fork the repo
2. Create your branch: `git checkout -b improve/signal-format`
3. Commit changes: `git commit -m "Improve signal card readability"`
4. Push: `git push origin improve/signal-format`
5. Open a Pull Request

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

Free to use, modify, and distribute. Just give credit. ✌️

---

<div align="center">

*If this helped you, drop a ⭐ on the repo — it helps others find it!*

**By [Samioutic](https://samioutic.com)**

</div>

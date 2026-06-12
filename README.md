# Nifty Options Playbook — Ojha CPR + Five-Layer Confirmation System

A complete intraday options trading reference for **Nifty 50** and **BankNifty**, combining six confirmation layers into one structured framework.

## Live Demo

[View the Playbook →](https://YOUR-USERNAME.github.io/nifty-options-playbook)

> Replace `YOUR-USERNAME` with your GitHub username after deployment.

---

## What's Inside

The playbook covers the full system from foundation to operations:

| Layer | Tool | Purpose |
|-------|------|---------|
| 1 | **Ojha CPR + Supertrend** | Day classification, entry setups, no-trade filters |
| 2 | **VWAP** | Institutional bias confirmation |
| 3 | **India VIX** | Premium pricing — buy vs sell decision |
| 4 | **RSI (14)** | Momentum confirmation, false-breakout filter |
| 5 | **Volume Profile** | POC / VAH / VAL positional intelligence |
| 6 | **OI + PCR** | Options market walls, PCR bias, max pain |

### Sections

- **Ojha CPR + Supertrend** — all 6 setups (3 long, 3 short) with entry / SL / target
- **When to stay out** — 4 explicit no-trade conditions
- **VWAP** — signal matrix, SD bands, sizing rules
- **India VIX** — 5 zones, strategy per zone, IV crush trap
- **RSI** — zones, scenarios, divergence exits, settings
- **Volume Profile** — key levels, 80% Value Area rule, CPR combos
- **OI + PCR** — OI fundamentals, PCR zones, combo setups, option chain guide
- **Master checklist** — 8-point pre-trade checklist for long and short
- **Pre-market routine** — 10-minute morning workflow
- **Strike selection** — 8 scenarios across VIX zones
- **Expiry day rules** — timing guide for Thursday (Nifty) / Wednesday (BankNifty)

---

## How to Use

### Option 1 — GitHub Pages (recommended)

1. Fork or push this repo to your GitHub account
2. Go to **Settings → Pages**
3. Source: `Deploy from a branch` → `main` → `/ (root)`
4. Save — your playbook will be live at `https://YOUR-USERNAME.github.io/nifty-options-playbook`

### Option 2 — Open locally

```bash
git clone https://github.com/YOUR-USERNAME/nifty-options-playbook.git
cd nifty-options-playbook
open index.html   # macOS
# or
start index.html  # Windows
```

No build step. No dependencies. Pure HTML — works offline.

---

## File Structure

```
nifty-options-playbook/
├── index.html        # The entire playbook (self-contained)
└── README.md         # This file
```

Everything is in `index.html` — fonts load from Google Fonts CDN, no other external dependencies.

---

## Disclaimer

This playbook is for **educational purposes only**. It does not constitute financial advice. Options trading involves significant risk. Always do your own research and consult a registered financial advisor before trading.

---

## Contributing

Found an error or want to add a section? Open an issue or submit a PR.

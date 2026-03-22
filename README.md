# Startup Valuation Calculator

A clean, minimal tool to calculate **pre-money** and **post-money** valuations for startup funding rounds — and the resulting equity dilution.

🔗 **Live at [startupval.ggglni.xyz](https://startupval.ggglni.xyz)**

---

## What it does

Given any two of the three variables, it calculates the third:

```
Post-money = Pre-money + Round
```

It also computes:
- **Investor equity** acquired in this round
- **Founder equity** after dilution (with optional pre-round ownership input)

## Features

- Two modes: start from **pre-money** or from **post-money**
- Optional **founder ownership** field for non-first rounds (accurate dilution across multiple rounds)
- Input multipliers: enter values in units, K, or M
- Outputs formatted as $K / $M / $B

## Usage

Enter any two values and the third is calculated instantly:

| Input | Result |
|-------|--------|
| Pre-money + Round | Post-money, % investors, % founders |
| Post-money + Round | Pre-money, % investors, % founders |

If you leave **Founder Ownership Before This Round** blank, the calculator assumes it's the first round (100% founder ownership pre-round).

## Stack

Plain HTML, CSS, and vanilla JavaScript. No dependencies, no build step.

## Local development

```bash
git clone https://github.com/ggglni/valuation-calculator.git
cd valuation-calculator
open index.html
```

## Deploy

Hosted on **GitHub Pages** with a custom domain via Squarespace DNS.

---

Built by [ggglni](https://github.com/ggglni)

# 🔍 IDX Elite Screener

A structured single-file stock screener report for the Indonesian stock market (IDX), applying a scoring framework across volume anomalies, smart money flow, technical setup, fundamentals, catalysts, and risk/reward.

## Problem

Screening Indonesian equities for short-to-medium term setups required combining several distinct signals — foreign flow, technical breakout, fundamental strength, and catalyst timing — into one consistent framework instead of judging each stock ad hoc.

## Features

- **Market Context Engine** — summarizes IHSG condition, foreign flow direction, rupiah trend, and global market risk appetite
- **Stock scoring cards** — each candidate stock scored across 6 weighted categories (Volume Anomaly, Smart Money, Technical, Fundamental, Catalyst, Risk/Reward) out of 100
- **Trade levels** — entry zone, stop loss, and multiple take-profit targets with R:R ratio for each pick
- **Avoid list** — stocks explicitly flagged with the reasoning for exclusion
- **Macro positioning summary** — sector focus and cash allocation guidance based on current market regime

## Tech Stack

- Vanilla HTML/CSS — static single-file report, styled as a dark-mode research briefing

## Why I built it this way

This applies the same discipline I use in crypto/forex research (structured scoring instead of gut feel) to a different market — Indonesian equities — to test whether the same systematic approach transfers across asset classes.

---

*Part of a series of self-built tools for market research and trading discipline.*

# ZCAT / ZEC + HYPE Yield Tracker

Private tracker for Hubert's ZCAT-related ZEC & HYPE accumulation.

## What's here
- `index.html` — projections + tracking UI (live spots when opened in a browser)
- `data/tracking.json` — durable Friday check-in log + wallet/ATA map

## Yield balances (auto)
Phantom owner: `5pEa24BzssBdaRpsubywmFyaNvccgHKakt6m9gC8qCY4`

| Asset | Token account (ATA) | Mint |
|------|---------------------|------|
| HYPE | `oVBKQAqXVrJmRKjN5QxA9Avy7fs5a4pdg9qtLo3u5od` | `98sMhvDwXj1RQi5c5Mndm3vPe9cBqPrbLaufMXFNMh5g` |
| ZEC | `AfXmyDjAZ6zh52ntAskTdcSu2VgDoVZ4oeG9FNvsBMvc` | `A7bdiYdS5GjqGFtxf17ppRHtDKPkkRqbKtR27dxvQXaS` |

**Important:** those Solscan links are ATAs — read with `getAccountInfo`, not as wallets.

Week-1 run rate: **1.62605 ZEC + 21.40849 HYPE** / week (implied daily ÷7).

## Automation
Grok Bot Quant runs a Friday 9:00 AM America/New_York routine that:
1. Pulls ATA balances + Solana mint prices
2. Appends `data/tracking.json`
3. Digests Hubert with Δ vs last week and vs run-rate

Cold ZEC `t1JECiYpXQ4uTZYgHvtDpZXbmPZ8jTohPhe` is tracked separately in portfolio, not mixed into yield entries by default.

## Local preview
Open `index.html` in a browser (needs network for live spots).

## Disclaimer
Illustrative projections only — not financial advice. Read-and-advise; no trading or fund moves.

Last packaged: 2026-09-13 15:33 UTC

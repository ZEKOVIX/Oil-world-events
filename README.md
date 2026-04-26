# 🛢️ Crude Oil Prices & World Events (2005–2024)

**How do geopolitical shocks, financial crises, and supply decisions move the price of oil?**

This notebook maps every major macro event of the last two decades onto the WTI Crude Oil price chart — turning a noisy time series into a readable story.

## What's inside

A single Jupyter notebook (`oil_world_events.ipynb`) that:
- Downloads WTI Crude Oil futures data via `yfinance`
- Annotates 20 key events: Lehman Brothers, Arab Spring, OPEC cuts, COVID-19, Russia-Ukraine war, and more
- Colour-codes events by type: geopolitical, crisis, OPEC, pandemic
- Overlays a 200-day moving average
- Summarises major price regimes in a styled table

## Quick start

```bash
pip install yfinance pandas matplotlib
jupyter notebook oil_world_events.ipynb
```

## Data

Source: Yahoo Finance — WTI Continuous Futures (`CL=F`), 2005–2024.

---
*Built with Python · yfinance · Matplotlib*

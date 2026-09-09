# Final Project: BoE Statement Tone -> UK Market Reaction Predictor

## Overview

A retrieval-based analysis tool that:
1. Attributes historical Bank of England hawkish/dovish tone to macro
   factors (inflation, unemployment, wage growth, GDP) and tracks how
   factor weightings shift across economic regimes.
2. Retrieves historically similar past BoE statements to a current one
   and uses analogous past market reactions (gilts, FTSE 100, GBP) to
   predict the likely reaction this time.

## Project Structure

```
final-project/
â”œâ”€â”€ notebooks/        # Exploration and analysis notebooks
â”œâ”€â”€ src/               # Reusable Python modules (data pulls, models, retrieval logic)
â”œâ”€â”€ data/
â”‚   â”œâ”€â”€ raw/           # Unmodified source data (ONS, BoE, market data)
â”‚   â””â”€â”€ processed/     # Cleaned/feature-engineered data
â”œâ”€â”€ models/            # Saved model artifacts
â”œâ”€â”€ docs/              # Write-up, architecture notes, diagrams
â””â”€â”€ tests/             # Unit tests
```

## Data Sources

- **Macro data**: ONS (Office for National Statistics) â€” inflation, unemployment, wages, GDP
- **BoE statements**: Bank of England â€” MPC minutes, statements, speeches
- **Market data**: yfinance â€” gilt yields, FTSE 100, GBP/USD

## Status

_Work in progress â€” see docs/ for design notes._

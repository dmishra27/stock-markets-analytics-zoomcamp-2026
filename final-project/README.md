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

\\\
final-project/
├── notebooks/        # Exploration and analysis notebooks
├── src/               # Reusable Python modules (data pulls, models, retrieval logic)
├── data/
│   ├── raw/           # Unmodified source data (ONS, BoE, market data)
│   └── processed/     # Cleaned/feature-engineered data
├── models/            # Saved model artifacts
├── docs/              # Write-up, architecture notes, diagrams
└── tests/             # Unit tests
\\\

## Data Sources

- **Macro data**: ONS (Office for National Statistics) — inflation, unemployment, wages, GDP
- **BoE statements**: Bank of England — MPC minutes, statements, speeches
- **Market data**: yfinance — gilt yields, FTSE 100, GBP/USD

## Status

_Work in progress — see docs/ for design notes._

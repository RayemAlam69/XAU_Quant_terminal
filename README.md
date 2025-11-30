# XAU/USD Quant Dashboard

A real-time analytics engine for gold (XAU/USD) including:
• live data ingestion
• EMA indicators
• Monte Carlo simulations
• volatility metrics
• heat maps
• interactive dashboard (Streamlit)

## Features
- Real-time XAU/USD price feed using AlphaVantage API
- Automated data pipeline
- Indicator calculations (EMA10/20/50)
- Monte Carlo forecasting module
- Interactive dashboard interface

## Project Structure
xau-quant-dashboard/
    src/
        data_fetch.py
        indicators.py
        monte_carlo.py
        visualize.py
        dashboard.py
    data/
        raw/
        processed/
    notebooks/
        experiments.ipynb
    config.py
    main.py
    requirements.txt
    README.md
    .gitignore

## Requirements
pip install -r requirements.txt

## Getting Started
1. Clone repo
2. Add your API key in config.py
3. Run: python main.py
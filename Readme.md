# Trading Algorithms Collection

## Overview
This repository contains a collection of trading algorithms developed for TradingView, utilizing Pine Script version 5. The algorithms are designed for various trading strategies with different technical indicators and entry/exit conditions.

## Algorithms Included

1. **2BB (Two Bollinger Bands) Strategy**
   - Uses Bollinger Bands with multiple standard deviation levels
   - Implements long and short entry/exit conditions
   - Customizable parameters for band length and standard deviation

2. **Angle Strategy**
   - Combines angle calculation, EMA, and RSI
   - Flexible entry and exit conditions
   - Configurable moving average and RSI lengths

3. **ATRC+MAC+STC Strategy**
   - Integrates ATR, Moving Average Convergence, and Stochastic indicators
   - Time-bound trading with configurable start and end dates
   - Advanced position sizing and risk management

4. **Body Volume Weighted Price Strategy**
   - Calculates weighted price lines based on body and volume
   - Multiple length configurations
   - Crossover and crossunder entry/exit signals

5. **Body Weighted Price Strategy**
   - Similar to Body Volume Weighted Price strategy
   - Simplified price weighting calculation
   - Configurable line lengths

## Features
- Implemented in Pine Script v5
- Percent of equity position sizing
- Configurable commission rates
- Dynamic stop-loss and take-profit mechanisms
- Equity value tracking
- Profit calculation with leverage

## Installation
1. Open TradingView
2. Go to Pine Editor
3. Create a new script
4. Copy and paste the desired algorithm
5. Adjust input parameters as needed

## Disclaimer
These algorithms are for educational purposes. Always backtest and paper trade before real trading.

## License
These algorithms are subject to the Mozilla Public License 2.0.

## Contributing
Contributions, improvements, and new strategies are welcome. Please submit a pull request.

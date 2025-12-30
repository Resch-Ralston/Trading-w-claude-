# Ross Cameron Momentum Day Trading Strategy

A TradingView screener implementation based on Warrior Trading's momentum day trading approach by Ross Cameron.

## Overview

This repository provides a complete setup for screening stocks using Ross Cameron's proven momentum trading strategy, optimized for small accounts ($2K+ minimum) focusing on scalping and 1-2 day trades.

## Strategy Framework

### Five-Pillar Stock Screening System

1. **Price Range**: $2 - $100 (small to mid-cap focused)
2. **Float**: Unlimited (flexible for all opportunities)
3. **Relative Volume**: Minimum 2x average volume
4. **Daily Gain**: 3%+ minimum
5. **Catalysts**: News-driven momentum stocks

### Technical Indicators Used

- **MACD** (Moving Average Convergence Divergence)
- **RSI** (Relative Strength Index)
- **Moving Averages**: 9 EMA, 20 EMA, 50 EMA, 200 EMA
- **ATR** (Average True Range) - volatility measurement
- **VWAP** (Volume Weighted Average Price)
- **Bollinger Bands**
- **Stochastic Oscillator**

### Candlestick Patterns

- Doji (indecision)
- Hammer patterns
- Engulfing patterns
- Morning/Evening Star
- Three White Soldiers

## Risk Management Rules

### Position Sizing
- **Options**: 5% maximum risk per trade
- **Shares**: 10% maximum risk per trade

### Options Criteria
- Weekly expirations only
- Maximum 30-minute hold time
- ITM/ATM strikes with delta 0.5-0.8
- Bid/ask spread < 10%
- Open interest > 100

### Performance Targets
- Win rate: 75%+
- P/L ratio: 2:1+
- Sharpe ratio: 2.0+

## Files in This Repository

- `README.md` - This file, strategy overview
- `tradingview-screener-setup.md` - Step-by-step TradingView screener setup guide
- `custom-indicators.pine` - Pine Script code for custom indicators

## Getting Started

1. Read the [TradingView Screener Setup Guide](tradingview-screener-setup.md)
2. Set up the screener in TradingView using the provided criteria
3. Apply the custom Pine Script indicators from `custom-indicators.pine`
4. Follow the risk management rules strictly

## Trading Approach

This is a **momentum day trading** strategy focusing on:
- Stocks with strong intraday momentum
- News-driven catalysts
- High relative volume (2x+)
- Quick scalps and day trades
- Strict risk management

## Disclaimer

This repository is for educational purposes only. Trading stocks and options involves substantial risk of loss. Past performance does not guarantee future results. Always trade responsibly and never risk more than you can afford to lose.

## Resources

- [Warrior Trading](https://www.warriortrading.com/) - Ross Cameron's platform
- Original strategy reference: [Moon Dev Code PR #1](https://github.com/melFranklin-76/Moon-Dev-Code/pull/1)

## License

MIT License - Feel free to use and modify for your own trading.

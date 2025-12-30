# TradingView Screener Setup Guide

This guide will walk you through setting up a stock screener in TradingView that matches Ross Cameron's momentum trading strategy.

## Step 1: Access the Stock Screener

1. Go to [TradingView.com](https://www.tradingview.com/)
2. Click on **"Screener"** in the top menu
3. Select **"Stock Screener"**

## Step 2: Set Basic Filters

### Market & Exchange
- **Market**: US Stocks
- **Exchange**: All (or focus on NYSE, NASDAQ)

### Price Filter
1. Click **"Add Filter"**
2. Search for **"Price"**
3. Set range: **$2.00 to $100.00**

### Volume Filter
1. Click **"Add Filter"**
2. Search for **"Relative Volume"**
3. Set to: **Greater than or equal to 2.0**

Alternative if Relative Volume isn't available:
- Use **"Volume"** > 1,000,000 shares
- Use **"Average Volume (30 day)"** as comparison

### Daily Gain Filter
1. Click **"Add Filter"**
2. Search for **"Change %"** or **"Performance (Day)"**
3. Set to: **Greater than or equal to 3%**

## Step 3: Technical Indicator Filters

### RSI (Relative Strength Index)
1. Add Filter → **"RSI (14)"**
2. Typical settings:
   - **For overbought momentum**: RSI between 50-80
   - **For oversold bounces**: RSI between 20-40
   - Ross Cameron often looks for RSI > 50 for bullish momentum

### Moving Averages
1. Add Filter → **"Price above SMA 9"** - Stock trending above 9-period moving average
2. Add Filter → **"Price above EMA 20"** - Above 20-period exponential moving average
3. Optional: **"SMA 9 above SMA 20"** - Confirms bullish trend

### MACD
1. Add Filter → **"MACD Level (12, 26)"**
2. Set to: **Greater than 0** (bullish momentum)
3. Or look for **"MACD Signal (12, 26)"** where MACD line is above signal line

### Volume Confirmation
1. Add Filter → **"Volume"**
2. Set to: **Greater than 500,000** (minimum liquidity)

## Step 4: Advanced Filters (Optional)

### Market Cap
- Add **"Market Capitalization"**
- Small to Mid-cap: **$50M to $10B** (more volatile, better for momentum)

### Average True Range (ATR)
- Add **"ATR (14)"**
- For price movement potential
- Look for ATR > 0.5 for stocks with decent volatility

### Sector
- Avoid or include specific sectors based on news/catalysts
- Technology, Healthcare, Biotech often have strong momentum plays

## Step 5: Sort and Organize Results

### Sorting Options
1. **By Change %**: See the biggest gainers first
2. **By Relative Volume**: See stocks with highest volume spikes
3. **By Volume**: See most liquid stocks

### Recommended Sort
- Primary: **Change % (Descending)** - Shows strongest movers
- Secondary: **Relative Volume (Descending)** - Shows unusual activity

## Step 6: Save Your Screener

1. Click **"Save Screen"** button (top right)
2. Name it: **"Ross Cameron Momentum - Daily"**
3. Save it to your account for daily use

## Example Screener Configuration

Here's a complete screener setup summary:

```
Market: US Stocks
Exchange: All

Filters:
├─ Price: $2.00 - $100.00
├─ Change % (Day): ≥ 3%
├─ Relative Volume: ≥ 2.0
├─ Volume: ≥ 500,000
├─ RSI (14): 50 - 80
├─ Price above EMA 9: Yes
├─ Price above EMA 20: Yes
├─ MACD Level: > 0
└─ Market Cap: $50M - $10B

Sort By: Change % (Descending)
```

## Step 7: Finding Catalysts (News)

TradingView doesn't automatically show news catalysts, so you'll need to:

1. **Check each stock manually** in the screener results
2. Click on a stock → Look for **News & Analysis** tab
3. Look for recent news (within 24 hours):
   - Earnings reports
   - FDA approvals
   - Partnerships/acquisitions
   - Product launches
   - Analyst upgrades

### External News Sources
- [Benzinga](https://www.benzinga.com/)
- [MarketWatch](https://www.marketwatch.com/)
- [Seeking Alpha](https://seekingalpha.com/)
- Twitter/X for real-time catalyst hunting

## Step 8: Using the Screener Effectively

### Best Times to Run Screener
- **Pre-market** (7:00 AM - 9:30 AM EST): Find gapping stocks
- **Market open** (9:30 AM - 10:30 AM EST): Catch opening momentum
- **Mid-day** (11:00 AM - 2:00 PM EST): Look for new setups

### Daily Workflow
1. Run screener at market open
2. Review top 10-20 results
3. Check for news catalysts on each
4. Add stocks to watchlist
5. Wait for pullback or consolidation
6. Enter on breakout with confirmation

### Red Flags to Avoid
- Low volume (< 500K shares traded)
- No clear catalyst or news
- Stock already up 50%+ (late to the move)
- Wide bid/ask spreads
- Stocks with recent reverse splits

## Step 9: Chart Setup for Screened Stocks

Once you find a stock, apply these indicators on the chart:

### Indicators to Add
1. **9 EMA** (Exponential Moving Average) - Blue
2. **20 EMA** - Red
3. **50 SMA** - Orange
4. **200 SMA** - Purple
5. **VWAP** (Volume Weighted Average Price) - Yellow
6. **MACD** (12, 26, 9) - Below chart
7. **RSI** (14) - Below chart
8. **Volume** bars - Below chart

### Entry Signals
- Price pulls back to 9 EMA or VWAP
- Volume spike on breakout
- MACD histogram turning green
- RSI > 50 and rising
- Price breaking above previous high/resistance

## Alternative: TradingView Screener Settings (Copy-Paste Ready)

If TradingView allows importing screener settings, use these:

**Fundamental**
- Market Cap: 50M - 10B USD

**Technical**
- Price: 2 - 100 USD
- Change %: ≥ 3
- Relative Volume: ≥ 2
- Volume: ≥ 500,000
- RSI: 50 - 80
- Price vs EMA9: Above
- Price vs EMA20: Above
- MACD: Positive

## Tips for Success

1. **Focus on 2-5 stocks daily**: Don't overtrade
2. **Wait for pullbacks**: Don't chase extended moves
3. **Use alerts**: Set price alerts on watchlist stocks
4. **Track your trades**: Journal every trade with entry/exit reasons
5. **Review daily**: What worked? What didn't?

## Common Issues & Solutions

### Issue: Too many results
**Solution**: Tighten filters
- Increase Change % to 5%
- Increase Relative Volume to 3x
- Add stricter price range ($5-$50)

### Issue: Too few results
**Solution**: Loosen filters
- Decrease Change % to 2%
- Decrease Relative Volume to 1.5x
- Expand price range ($1-$150)

### Issue: Stocks already too extended
**Solution**:
- Run screener earlier in the day
- Use watchlist alerts instead
- Focus on stocks up 3-10% (not 20%+)

## Next Steps

1. Run the screener daily for 1 week in paper trading
2. Track which setups work best
3. Refine filters based on your results
4. Gradually transition to live trading with small size

## Additional Resources

- [TradingView Screener Documentation](https://www.tradingview.com/support/solutions/43000481779-introduction-to-stock-screener/)
- [Ross Cameron's Warrior Trading YouTube](https://www.youtube.com/c/WarriorTrading)
- Custom Pine Script indicators: See `custom-indicators.pine` in this repository

---

**Remember**: This screener finds opportunities, but YOU make the trading decisions. Always verify catalysts, wait for proper entry setups, and manage risk appropriately.

# TradingView Screener - 5-Minute Setup

## Quick Setup Instructions (Follow in Order)

### Step 1: Open TradingView Screener
Go to: https://www.tradingview.com/screener/

Click **"Stock Screener"**

---

### Step 2: Add Filters (One-by-One)

Click **"+ Add Filter"** and configure each filter exactly as shown:

#### Filter 1: Price
```
Search: "Price"
Set: 2 to 100
```

#### Filter 2: Change %
```
Search: "Change %"
Set: Greater than or equal to 3
```

#### Filter 3: Relative Volume
```
Search: "Relative Volume"
Set: Greater than or equal to 2
```

#### Filter 4: Volume
```
Search: "Volume"
Set: Greater than or equal to 500000
```

#### Filter 5: RSI
```
Search: "RSI"
Set: 50 to 80
```

#### Filter 6: Price vs EMA 9
```
Search: "Price above EMA9"
OR search: "EMA 9" and set "Price above"
```

#### Filter 7: Price vs EMA 20
```
Search: "Price above EMA20"
OR search: "EMA 20" and set "Price above"
```

#### Filter 8: MACD
```
Search: "MACD Level"
Set: Greater than 0
```

#### Filter 9: Market Cap
```
Search: "Market Capitalization"
Set: 50000000 to 10000000000
(That's $50M to $10B)
```

---

### Step 3: Set Sorting
Click the **"Change %"** column header to sort by highest gainers first

---

### Step 4: Save Your Screener
1. Click **"Save Screen"** button (top right)
2. Name it: **"Ross Cameron Momentum"**
3. Click Save

---

## Even Faster: Use TradingView's Pre-Built Screeners

TradingView has some built-in screeners that are close to what we need:

### Option A: Start with "Top Gainers"
1. Go to Screener
2. Click **"Screener Type"** dropdown
3. Select **"Top Gainers"**
4. This gives you stocks already filtered by daily gain
5. Then just add the missing filters:
   - Relative Volume ≥ 2
   - RSI 50-80
   - Price above EMA 9
   - Price above EMA 20
   - MACD > 0

### Option B: Start with "Most Volatile"
1. Select **"Most Volatile"** screener
2. Add filters for:
   - Change % ≥ 3
   - Relative Volume ≥ 2
   - RSI 50-80
   - Price $2-$100

---

## Sharing Your Screener (Once Set Up)

After you set up the screener, you can:
1. Click **"Save Screen"**
2. Click the **"Share"** icon
3. TradingView generates a shareable link
4. You can access it from any device

---

## Alternative: Use TradingView Watchlist Alerts

If the screener is too manual, try this workflow:

### 1. Create a Watchlist
- Add stocks from your screener results
- Or add common momentum stocks (TSLA, AMD, NVDA, etc.)

### 2. Set Multi-Chart Layout
- View 4-6 stocks at once
- Apply your custom indicators to all

### 3. Set Alerts
On each stock, click **"Alerts"** and set:
```
Condition: Change % crosses above 3%
AND Relative Volume > 2
```

---

## Pro Tip: Save as Template

Once you configure one chart perfectly:
1. Click **"Chart Settings"** (gear icon)
2. Click **"Save Indicator Template"**
3. Name it: "Ross Cameron Setup"
4. Apply to any new chart with one click

---

## Mobile App

The TradingView mobile app allows you to:
- Access saved screeners
- View watchlists
- Get alerts on the go

Download: https://www.tradingview.com/mobile/

---

## Need Help?

If you get stuck on any filter:
1. Use TradingView's search bar - it auto-suggests
2. Check the full guide: `tradingview-screener-setup.md`
3. TradingView Support: https://www.tradingview.com/support/

---

**Estimated Setup Time**: 5-7 minutes (first time)

**Estimated Time After Saved**: Instant! Just load your saved screener.

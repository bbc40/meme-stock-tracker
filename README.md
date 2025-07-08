# Meme Stock Screener Dashboard

A simple real-time dashboard to track popular meme/YOLO stocks with key financial metrics including price, volume, market cap, short interest, shares issued/outstanding/float, and float percentage.

## Features

- Real-time data from Twelve Data API (stock price, volume, etc.)
- Share data (issued, outstanding, float) from Financial Modeling Prep API
- Filters for price and volume thresholds
- Highlights stocks with low float % (<20%)
- Sortable columns and CSV export
- Click on a stock row to open TradingView chart

## Setup

1. Clone or download this repository.

2. Replace the API keys in `index.html`:
   - Twelve Data API key: Replace `c092bc61884c41889163f8c4e884c908` with your own key.
   - Financial Modeling Prep API key: Replace `'demo'` with your own key.

3. Open `index.html` in a modern browser.

4. For continuous updates, the page refreshes data every 60 seconds.

## Usage

- Use the checkboxes to filter stocks by price > $5 and volume > 1 million.
- Click column headers to sort.
- Click a stock row to open its TradingView page.
- Export the current table data as CSV.

## Notes

- API free tiers may have rate limits.
- Customize the stock ticker list in the script as needed.

---

**Enjoy tracking your meme stocks! 🚀**

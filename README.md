# market-data

Daily adjusted prices (split- and dividend-adjusted, from Yahoo Finance, Stooq as a fallback) for SPY, QQQ, AAPL, MSFT, NVDA, GOOGL, AMZN, META, AMD, TSM and TSLA.

A GitHub Action (`.github/workflows/prices.yml`) refreshes `data/<TICKER>.csv` every weekday at 22:30 UTC, after the US close. Run it by hand from the Actions tab with **Run workflow**.

Used for backtesting and paper trading; no real trades.

# Crypto Data Manager

This Python project provides a convenient way to download, manage, and load OHLCV (Open-High-Low-Close-Volume) data for cryptocurrencies from various exchanges. It leverages the `ccxt` library for interacting with exchange APIs and `pandas` for data extraction.

## Key Features

- **Exchange Support:** Fetches data from Bitget and Binance (with easy extensibility to other exchanges).
- **Timeframe Flexibility:** Supports a wide range of timeframes (1m, 5m, 1h, 1d, etc.).
- **Data Downloading:** Downloads OHLCV data for a specified symbol, timeframe, and date range.
- **Data Loading:** Efficiently loads data from saved CSV files, allowing filtering by date range.
- **Data Storage:** Organizes downloaded data into a "data" folder in a structured format.
- **Robustness:** Includes input validation, exchange support checks, and informative error handling.

## Installation

1. **Get the Code:**
   - Download or clone this repository.
   - To clone do this (`git clone https://github.com/chumbacash/cryptodata.git`)

2. **Prerequisites:** Ensure you have the following:
   - Python (3.7 or higher)
   - `Virtual Environment` library (`python -m venv .venv`)
   - `Activate virtual env` library (`.venv/Scripts/activate`)
   - `Install Requirements` library (`pip install -r ../requirements.txt`)

3. **Happy coding by Chumbacash**



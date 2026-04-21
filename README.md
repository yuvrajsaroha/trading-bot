# Trading Bot - Binance Futures Testnet

## Setup

1. Clone repo
2. Install dependencies:
   pip install -r requirements.txt

3. Add API keys in .env file

## Run

### Market Order
python cli.py --symbol BTCUSDT --side BUY --type MARKET --quantity 0.01

### Limit Order
python cli.py --symbol BTCUSDT --side SELL --type LIMIT --quantity 0.01 --price 60000

## Logs

Check bot.log file

## Notes

- Uses Binance Futures Testnet
- Supports MARKET & LIMIT orders
- ⚠️ This is a CLI-based Python application and cannot be run in a browser.

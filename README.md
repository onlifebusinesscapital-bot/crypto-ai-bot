# Crypto AI Bot

Automated trading bot using n8n + Claude AI + GitHub as memory.

## Features
- Fetches BTC/USDT price from Binance every 15 minutes
- Analyzes data with Claude (or Kimi)
- Stores decisions in this repository (decision_log.json)
- Sends alerts via Telegram

## How to use
1. Import the `workflow_n8n.json` file into your n8n (Cloud or self-hosted)
2. Configure credentials: Anthropic API, GitHub token, Telegram bot
3. Activate the workflow

## Memory
The `decision_log.json` file contains the history of analyses: timestamp, price, signal (BUY/SELL/HOLD), and reasoning.

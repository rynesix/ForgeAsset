# Pumpswap Volume Bot

[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/vladmeeros/pumpswap-volume-bot)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

Pumpswap volume bot that makes endless buy and sell swaps to increase trading volume and promote your token at fast speed.

**Repository:** [https://github.com/vladmeeros/pumpswap-volume-bot](https://github.com/vladmeeros/pumpswap-volume-bot)

## Overview

This bot automates trading operations on Pumpswap to generate trading volume for your token. It performs continuous buy and sell operations to boost visibility and trading activity.

> **Note:** This script only shows the buy and sell feature as a demo.

## Updates

Since the Pumpswap contract IDL has been updated with the creator vault concept introduced, this script has been updated accordingly to work with the latest contract version.

## Test Transactions

Here are test transaction hashes demonstrating buy and sell operations:

- **Buy Transaction:** [View on Solscan](https://solscan.io/tx/EQaQHPRQVd3gjSRU6Apk7HnrB57oD4y45Gdj6QUW942FLQDMQku8LM7vWXW3bUiR5Fr7zdZaKL1dYx6fXqtvoGz)
- **Sell Transaction:** [View on Solscan](https://solscan.io/tx/EQaQHPRQVd3gjSRU6Apk7HnrB57oD4y45Gdj6QUW942FLQDMQku8LM7vWXW3bUiR5Fr7zdZaKL1dYx6fXqtvoGz)

## Screenshots

### Buy Process

![Screenshot_2](https://github.com/user-attachments/assets/d0e6b91b-132a-4bcc-9634-ff3813f084fb)

### Sell Process

![Screenshot_3](https://github.com/user-attachments/assets/a2c9e551-6443-435a-82e8-61c24eb54716)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/vladmeeros/pumpswap-volume-bot.git
cd pumpswap-volume-bot
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Configure your environment variables (create a `.env` file with your settings)

4. Run the bot:
```bash
npm start
```

## Technology Stack

- **TypeScript** - Primary development language
- **@coral-xyz/anchor** - Solana program framework
- **@solana/web3.js** - Solana blockchain interaction
- **@raydium-io/raydium-sdk** - Raydium SDK integration

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Disclaimer

This bot is for educational and demonstration purposes only. Use at your own risk.

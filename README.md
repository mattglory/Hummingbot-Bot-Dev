# Hummingbot-Bot-Dev

A professional Hummingbot-based trading bot implementation, showcasing Python skills, multi-exchange API integration, and real-time cross-exchange market making strategies, with relevance to Bitcoin development.

## Overview
This repository contains a custom trading bot built using Hummingbot, an open-source framework for cryptocurrency trading. The bot implements a *cross-exchange market making* strategy, integrating *Hyperliquid* (maker) and *Hyperliquid perpetuals* (taker) to execute trades based on real-time market data. Developed by Glory Mathew (mattglory), this project demonstrates expertise in Python programming, dual-exchange API handling, and automated trading systems, with plans to expand to Binance, Uniswap, and Coinbase Pro.

## Features
- Real-time cross-exchange market making between Hyperliquid and Hyperliquid perpetuals
- API integrations with Hyperliquid and Hyperliquid perpetuals
- Configurable order amount (10 units), spread (10 bps), and max order age (120 seconds)
- Slippage buffer (25 bps) for robust trading
- [Add other features, e.g., logging, if implemented]

## Getting Started
### Prerequisites
- Python 3.7+
- Hummingbot installed (follow [Hummingbot docs](https://docs.hummingbot.io/))
- API keys for Hyperliquid and Hyperliquid perpetuals

### Installation
1. Clone this repository: git clone https://github.com/mattglory/Hummingbot-Bot-Dev.git
2. Navigate to the directory: cd Hummingbot-Bot-Dev
3. Install dependencies: pip install -r requirements.txt (create this file with needed packages)
4. Configure your API keys in conf/config.yml
5. Run the bot: python strategy.py or use the conf_simple_xemm_1.yml configuration

## Usage
- Edit conf_simple_xemm_1.yml to adjust parameters (e.g., order amount, spread).
- Start the bot with Hummingbot using the configuration file.
- Monitor performance and logs (add log file path if implemented).

## Skills Demonstrated
- *Programming*: Python
- *Tools*: Hummingbot, Git, API integration (Hyperliquid, Hyperliquid perpetuals, with plans for Binance, Uniswap, Coinbase Pro)
- *Relevance*: Experience applicable to Bitcoin Core development (e.g., multi-system integration, real-time data)

## Why Bitcoin and Brink?
My Hummingbot work, especially this cross-exchange strategy, has honed my skills in managing multiple APIs and real-time systems—skills I’m eager to apply to Bitcoin Core’s open-source development. This project is a stepping stone toward contributing to Bitcoin’s protocol, and I’m excited to join the Brink Fellowship in London for mentorship. As of 12:46 AM BST, Sunday, August 03, 2025, I’m actively refining this for my application.

## Future Work
- Expand integrations to Binance, Uniswap, and Coinbase Pro
- Optimize cross-exchange strategy performance
- Explore Bitcoin Core contributions (e.g., testing, documentation)

## Contact
- *Name*: Glory Mathew
- *Email*: mattglory14@gmail.com
- *GitHub*: [mattglory](https://github.com/mattglory)

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
Inspired by the Hummingbot community, the decentralized vision of Bitcoin, and the Brink Fellowship opportunity.

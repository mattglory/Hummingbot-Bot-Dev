# Hummingbot-Bot-Dev

A professional Hummingbot-based trading bot implementation, showcasing Python skills, multi-exchange API integration, and real-time cross-exchange market making strategies, with relevance to Bitcoin and DeFi development.

## Overview
This repository contains a custom trading bot built using Hummingbot, an open-source framework for cryptocurrency trading. The bot implements a *cross-exchange market making* strategy, integrating *Hyperliquid* (maker) with the trading pair *ETH-USDC* and *Uniswap* (taker) with the trading pair *WBTC-USDC* to execute trades based on real-time market data. Developed by Glory Mathew (mattglory), this project demonstrates expertise in Python programming, dual-exchange API handling, and automated trading systems, with plans to expand to Binance, Hyperliquid perpetuals, and Coinbase Pro. The configuration is defined in conf_simple_xemm_1.yml.

## Features
- Real-time cross-exchange market making between Hyperliquid (ETH-USDC) and Uniswap (WBTC-USDC)
- API integrations with Hyperliquid and Uniswap
- Configurable order amount (10 units), spread (10 bps), and max order age (120 seconds)
- Slippage buffer (25 bps) for robust trading
- [Add other features, e.g., logging, if implemented]

## Configuration Details (conf_simple_xemm_1.yml)
- *Strategy*: Cross-exchange market making
- *Maker Exchange*: Hyperliquid (ETH-USDC)
- *Taker Exchange*: Uniswap (WBTC-USDC)
- *Order Amount*: 10 units
- *Spread*: 10 basis points (bps)
- *Minimum Spread*: 0 bps
- *Slippage Buffer*: 25 bps
- *Maximum Order Age*: 120 seconds
- Usage: Load this file in Hummingbot to run the strategy (e.g., hummingbot -c conf_simple_xemm_1.yml).

## Getting Started
### Prerequisites
- Python 3.7+
- Hummingbot installed (follow [Hummingbot docs](https://docs.hummingbot.io/))
- API keys for Hyperliquid (ETH-USDC) and Uniswap (WBTC-USDC)

### Installation
1. Clone this repository: git clone https://github.com/mattglory/Hummingbot-Bot-Dev.git
2. Navigate to the directory: cd Hummingbot-Bot-Dev
3. Install dependencies: pip install -r requirements.txt (create a requirements.txt file with at least requests==2.28.1)
4. Configure your API keys in conf/config.yml
5. Run the bot: Use conf_simple_xemm_1.yml with Hummingbot (e.g., hummingbot -c conf_simple_xemm_1.yml)

## Usage
- Edit conf_simple_xemm_1.yml to adjust parameters (e.g., order amount, spread) and ensure ETH-USDC (Hyperliquid) and WBTC-USDC (Uniswap) pairs are configured.
- Start the bot with Hummingbot using the configuration file.
- Monitor performance (add log file path if implemented).

## Skills Demonstrated
- *Programming*: Python
- *Tools*: Hummingbot, Git, API integration (Hyperliquid, Uniswap, with plans for Binance, Hyperliquid perpetuals, Coinbase Pro)
- *Relevance*: Experience applicable to Bitcoin Core (Brink Fellowship) and DeFi trading innovation (Paradigm Fellowship 2025)

## Why Bitcoin, DeFi, and Fellowships?
My Hummingbot work, especially this cross-exchange strategy with ETH-USDC (Hyperliquid) and WBTC-USDC (Uniswap) pairs, has honed my skills in managing multiple APIs and real-time systems—skills I’m eager to apply to Bitcoin Core’s open-source development (Brink Fellowship) and DeFi trading advancements (Paradigm Fellowship 2025). This project is a stepping stone toward contributing to Bitcoin’s protocol and exploring innovative trading solutions, and I’m excited to join mentorship programs in London (Brink) and beyond (Paradigm). As of 01:33 AM BST, Sunday, August 03, 2025, I’m actively refining this for my applications.

## Future Work
- Expand integrations to Binance, Hyperliquid perpetuals, and Coinbase Pro with USDC-based pairs
- Optimize cross-exchange strategy performance
- Explore Bitcoin Core contributions (e.g., testing, documentation) and DeFi enhancements

## Contact
- *Name*: Glory Mathew
- *Email*: mattglory14@gmail.com
- *GitHub*: [mattglory](https://github.com/mattglory)

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
Inspired by the Hummingbot community, the decentralized vision of Bitcoin, DeFi innovation, and the Brink and Paradigm Fellowship opportunities.

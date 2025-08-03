# Hummingbot-Bot-Dev

A professional Hummingbot-based trading bot showcasing advanced DeFi and crypto expertise, developed by Glory Mathew (mattglory) for open-source contribution and personal growth in blockchain technology.

## Overview
This repository hosts a custom trading bot built with Hummingbot, enhanced by the Hummingbot Gateway for multi-protocol DeFi integration. The bot executes a *cross-exchange market making strategy, linking **Hyperliquid* (maker, ETH-USDC) and *Uniswap* (taker, WBTC-USDC), and extends to *Meteora, **Raydium, and **Quickswap* via the Gateway. This project demonstrates Python proficiency, API integration across Ethereum, Solana, and Polygon, and practical experience with AMMs and liquidity provision. Configurations are managed in conf_advanced_xemm_1.yml.

## Features
- Cross-exchange market making between Hyperliquid (ETH-USDC) and Uniswap (WBTC-USDC)
- Hummingbot Gateway integration with Meteora, Raydium, and Quickswap for AMM trading
- Configurable settings: 10-unit orders, 10 bps spread, 120-second max order age
- 25 bps slippage buffer for robust execution
- Multi-chain support (Ethereum, Solana, Polygon)

## Configuration Details (conf_advanced_xemm_1.yml)
- *Strategy*: Cross-exchange market making with Gateway enhancements
- *Maker Exchange*: Hyperliquid (ETH-USDC)
- *Taker Exchange*: Uniswap (WBTC-USDC)
- *Additional DEXs*: Meteora, Raydium, Quickswap (via Gateway)
- *Order Amount*: 10 units
- *Spread*: 10 basis points (bps)
- *Minimum Spread*: 0 bps
- *Slippage Buffer*: 25 bps
- *Maximum Order Age*: 120 seconds
- Usage: Run with hummingbot -c conf_advanced_xemm_1.yml

## AMM Configuration
This project leverages the Hummingbot Gateway to integrate with the following AMM protocols, each configured for optimal liquidity provision and trading:
- *Uniswap (Ethereum)*: Configured with a 0.3% fee tier, using WBTC-USDC pair, with a custom liquidity delta of 5% to balance depth and cost.
- *Meteora (Solana)*: Set up with a 0.25% fee tier, targeting ETH-USDC, with a 10% position refresh interval for dynamic adjustments.
- *Raydium (Solana)*: Utilizes a 0.25% fee tier, paired with SOL-USDC, with a 15% inventory skew limit to manage risk.
- *Quickswap (Polygon)*: Configured with a 0.3% fee tier, using MATIC-USDC, with a 20-second order refresh time for responsiveness.
- These settings are defined in conf/gateway_amm_config.yml and can be adjusted via the Gateway interface or YAML edits.

## Getting Started
### Prerequisites
- Python 3.7+
- Hummingbot and Hummingbot Gateway installed (see [Hummingbot docs](https://docs.hummingbot.io/))
- API keys for Hyperliquid, Uniswap, and Gateway-supported DEXs

### Installation
1. Clone repository: git clone https://github.com/mattglory/Hummingbot-Bot-Dev.git
2. Navigate: cd Hummingbot-Bot-Dev
3. Install dependencies: pip install -r requirements.txt (create with requests==2.28.1)
4. Configure API keys: Edit conf/config.yml
5. Run bot: hummingbot -c conf_advanced_xemm_1.yml

## Usage
- Adjust conf_advanced_xemm_1.yml for parameters and DEX settings
- Configure AMM settings in conf/gateway_amm_config.yml for Uniswap, Meteora, Raydium, Quickswap
- Launch bot with Hummingbot using the config file
- Monitor performance (log file path to be added)

## Skills Demonstrated
- *Programming*: Python
- *Tools*: Hummingbot, Hummingbot Gateway, Git, API integration
- *Relevance*: Applicable to DeFi innovation, crypto market structures, and open-source development

## Project Motivation
This Hummingbot project, integrating Hyperliquid, Uniswap, Meteora, Raydium, and Quickswap via the Gateway, reflects my expertise in AMMs, cross-chain trading, and market-making. The use of WBTC-USDC connects to Bitcoin ecosystems, while multi-protocol AMM work supports broader DeFi advancements. As of 12:23 PM BST, Sunday, August 03, 2025, I’m refining this for potential collaboration and skill enhancement in the crypto space.

## Future Work
- Expand Gateway to additional DEXs (e.g., PancakeSwap)
- Develop MEV and arbitrage strategies
- Contribute to open-source crypto projects

## Contact
- *Name*: Glory Mathew
- *Email*: mattglory14@gmail.com
- *GitHub*: [mattglory](https://github.com/mattglory)

## License
Licensed under the [MIT License](LICENSE).

## Acknowledgments
Inspired by the Hummingbot community, crypto pioneers, and the broader blockchain ecosystem.

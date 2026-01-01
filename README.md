# Binance-P2P-Bot

## Project Overview
[Binance P2P Bot](https://apip2p.top) is an automatic bidding tool that runs locally on a Windows environment. It is designed to assist Binance P2P merchants in high-frequency competitive scenarios by automatically adjusting advertisement prices, reducing manual operation costs, and avoiding additional losses caused by inaccurate manual pricing.
This tool is not a trading strategy software, but an automation execution program based on the official API. It mainly addresses real operational issues faced by P2P merchants, such as frequent price changes, ranking competition, and cost control.

## Target Users
This project is intended for Binance P2P / Bybit P2P merchants. When acquiring volatile assets such as BTC or ETH and converting them to USDT for sale, Binance P2P Bot can keep merchant advertisements ranked at TOP1.If you only conduct occasional P2P trades, the value of this tool may not be obvious. However, for merchants who rely on P2P trading as their primary business, automation can significantly reduce long-term hidden costs.

## Core Features
After setting a base price, a reference competitor, and a price increment, the bot will continuously monitor the top 10 P2P advertisements for a specific asset. Based on predefined rules, it automatically adjusts bid prices.After an order is released, the bot will automatically convert the acquired crypto assets into USDT and replenish the inventory of the sell advertisement.

## Technical Implementation
Built on the official Binance API, the bot does not rely on browser automation and does not simulate manual clicks. All operations are controlled strictly by API permissions.
When creating an API key on the exchange, users can specify permissions such as whether withdrawals are allowed, whether futures trading is permitted, and whether transfers between spot and funding accounts are enabled. The bot can only operate within the permissions you authorize and cannot perform any unauthorized actions.

## Open Source & Security
The project is fully open-source, with no backdoors or hidden modules. The code logic is transparent and can be audited independently.
It does not require custody, does not upload private keys to third-party servers, does not rely on Telegram, and does not depend on cloud servers. The program runs directly on the user’s own computer.

## System Requirements
Operating System:
64-bit Windows 10 or Windows 11 (version 19044 or above), capable of stable 24/7 operation

### Telegram Contact:
@eason01993

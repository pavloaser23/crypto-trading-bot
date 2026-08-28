# Getting Started

This guide explains how to install **CryptoBot on Windows**, connect a cryptocurrency exchange or Web3 wallet, configure a trading strategy, and start automated trading.

## Installation

CryptoBot is distributed as a Windows application.

1. Download the latest `.zip` archive from the [Releases](https://github.com/pavloaser23/cryptobot/releases) page.

2. Extract the archive to a local folder.

3. Open the extracted folder.

4. Run the installer:

   `cryptobot-windows-x64-v1.0.exe`

5. Follow the installation steps.

6. Launch **CryptoBot** after the installation is complete.

Always download CryptoBot from the official repository or another trusted distribution source.

## First Launch

After starting CryptoBot:

1. Open **Settings → Connections**.
2. Choose an **Exchange** or **Wallet** connection.
3. Connect your account.
4. Select a trading strategy.
5. Configure the strategy parameters.
6. Configure your risk management settings.
7. Review the configuration.
8. Click **Start**.

For detailed connection instructions, see [Connections](connections.md).

## Automated Trading

Once the trading engine is started, CryptoBot can automatically monitor market data and execute trades according to the selected strategy.

Depending on the configuration, the trading engine can:

* Monitor cryptocurrency market data
* Generate trading signals
* Execute trades automatically
* Manage open positions
* Apply stop-loss and take-profit rules
* Apply trailing stops
* Record trading activity
* Track trading performance

No manual order placement is required while automated trading is running.

For more information, see [Automated Trading](automation.md).

## System Requirements

### Windows

* Windows 10 or Windows 11
* 64-bit system
* 4 GB RAM minimum
* 8 GB RAM recommended
* Approximately 435 MB of available disk space

### Network

A stable internet connection is required for live trading.

Low network latency can be beneficial for strategies that depend on timely market data and order execution.

Exchange connectivity may also depend on regional availability and the exchange's own network policies.

## Exchange & Wallet Accounts

CryptoBot can connect to supported centralized exchanges and Web3 wallets.

### Exchanges

Examples include:

* Binance
* Bybit
* OKX
* KuCoin
* Kraken
* Bitget
* Gate.io
* Bitfinex
* Coinbase

### Web3 Wallets

Examples include:

* MetaMask
* Trust Wallet
* Coinbase Wallet
* WalletConnect
* Phantom
* Rabby
* OKX Wallet

See [Connections](connections.md) for the complete list and connection instructions.

## API Permissions

When connecting a centralized exchange, create an API key with only the permissions required by CryptoBot.

**Recommended:**

* Enable the required trading permissions.
* Enable market-data access if required.
* Disable withdrawals.
* Do not grant unnecessary account permissions.

Never publish API credentials in the repository or store them in source code.

## Choosing a Trading Strategy

Before starting automated trading, make sure you understand the strategy you have selected.

CryptoBot can work with strategies based on:

* Technical indicators
* Trend following
* Momentum
* Scalping
* Arbitrage
* Machine learning

Strategy availability depends on the current version of the application.

If backtesting is available for your strategy, test it with historical market data before using real funds.

## Security

Keep your trading accounts and credentials secure.

* Never share exchange API secrets.
* Never share a wallet seed phrase or private key.
* Disable exchange withdrawal permissions.
* Do not run CryptoBot on a public or shared computer.
* Keep Windows and antivirus software up to date.
* Download releases only from trusted sources.
* Verify release files when checksums or signatures are provided.

If an API credential is exposed, revoke it immediately and create a new one.

## Windows Security Warnings

Windows or antivirus software may display a warning when running an executable downloaded from the internet, especially if the application is not widely recognized or signed.

Do not automatically bypass a security warning.

Before running the application:

1. Make sure the file was downloaded from a trusted CryptoBot release.
2. Check the release version.
3. Verify the file checksum or digital signature if one is provided.
4. Scan the file with your security software.
5. Only continue if you understand and trust the source.

## Troubleshooting

If CryptoBot does not start:

* Make sure you are using a 64-bit version of Windows.
* Extract the complete archive before running the installer.
* Check available disk space.
* Check Windows security or antivirus logs.
* Make sure the downloaded archive is complete.
* Download the latest release if the current version is outdated.

If an exchange connection fails, check your API permissions, credentials, network connection, and the exchange's current availability.

## Next Steps

Once CryptoBot is installed, continue with:

* [Quick Start](../QUICK_START.md) — install, connect, configure, and start CryptoBot
* [Connections](connections.md) — exchange and Web3 wallet connections
* [Automated Trading](automation.md) — how the automated trading engine works
* [FAQ](faq.md) — common questions about CryptoBot

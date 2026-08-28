# FAQ

Frequently asked questions about CryptoBot, automated cryptocurrency trading, exchange connections, Web3 wallets, trading strategies, and security.

## What is CryptoBot?

CryptoBot is an automated cryptocurrency trading application designed to execute trades according to configured trading strategies, market signals, and risk management settings.

It can be used for algorithmic trading, cryptocurrency market analysis, strategy testing, and automated trade execution.

## Is cryptocurrency trading automatic?

Yes. CryptoBot can automatically monitor market data, generate trading signals, execute trades, and manage positions after the trading engine has been started and configured.

The actual behavior depends on the selected strategy, configuration, market conditions, and connected trading account.

## Do I need an exchange API key?

If you connect a centralized cryptocurrency exchange, CryptoBot uses the exchange's API credentials to access the functionality required by the integration.

API permissions should be limited to what is necessary for trading.

**Withdrawal permissions should be disabled whenever they are not required.**

## Can I use CryptoBot without an exchange API key?

CryptoBot also supports Web3 wallet connections.

Whether an API key is required depends on the connection type and the functionality you are using.

See [Connections](connections.md) for the currently supported exchanges and wallets.

## Which cryptocurrency exchanges are supported?

CryptoBot currently supports:

* Binance
* Bybit
* OKX
* KuCoin
* Kraken
* Bitget
* Gate.io
* Bitfinex
* Coinbase

See [Connections](connections.md) for more information about exchange connections and API credentials.

## Which Web3 wallets are supported?

Supported Web3 wallets and wallet connectors include:

* MetaMask
* Trust Wallet
* Coinbase Wallet
* WalletConnect
* Phantom
* Rabby
* OKX Wallet

Wallet support may depend on the current CryptoBot version and integration.

## Can I connect multiple exchanges or wallets?

Only one connection type should be active at a time.

CryptoBot uses either an **exchange connection** or a **Web3 wallet connection** for the active trading workflow.

## Does CryptoBot support automated trading?

Yes. Automated trading is one of the main purposes of CryptoBot.

Once configured, the trading engine can monitor market data and execute trades according to the selected strategy and risk management settings.

See [Automated Trading](automation.md) for more information.

## What trading strategies are supported?

CryptoBot includes several types of trading strategies, including:

* Moving Average Crossover
* RSI
* MACD
* Bollinger Bands
* Scalping
* Arbitrage
* Trend following
* Momentum and breakout strategies
* Machine-learning-based strategies

The available strategies depend on the current implementation of the project.

## Can I create my own trading strategy?

CryptoBot is built around a modular strategy system that can be extended with custom trading logic.

Custom strategies can be used to experiment with different indicators, market conditions, entry and exit rules, and trading timeframes.

## Does CryptoBot support backtesting?

Yes. CryptoBot supports backtesting strategies against historical cryptocurrency market data.

Backtesting can help evaluate a strategy before using it with live trading.

Historical results do not guarantee future performance.

## Does CryptoBot use artificial intelligence?

CryptoBot includes experimental machine-learning approaches for cryptocurrency market analysis and trading strategy development.

Machine learning is not required for all trading strategies. Traditional technical-analysis and rule-based strategies can also be used.

## Where is my data stored?

CryptoBot is designed to keep application data locally.

The exact data stored by the application depends on the current version and configuration. Review the application's configuration and storage behavior before using it with sensitive information.

## Are my API keys safe?

API credentials should always be treated as sensitive information.

For exchange connections:

* Never share API keys or API secrets.
* Do not commit credentials to Git.
* Disable withdrawal permissions.
* Use only the permissions required by the application.
* Revoke an API key immediately if you believe it has been exposed.

## Does CryptoBot need my wallet seed phrase?

No wallet application should require you to provide your seed phrase or private key to connect a wallet.

Never enter or share a wallet seed phrase or private key with CryptoBot.

Web3 wallet connections should be authorized through the wallet interface.

## Can I stop automated trading?

Yes. The trading process can be stopped from the application.

Always review open positions and orders after stopping an automated trading system.

## Is CryptoBot profitable?

No software can guarantee profitable cryptocurrency trading.

Trading results depend on the strategy, market conditions, execution, fees, risk management, and many other factors.

Backtesting results should not be interpreted as a guarantee of future performance.

## Is CryptoBot safe to use with real money?

Automated cryptocurrency trading involves significant financial risk.

Before using real funds:

1. Understand the strategy you are using.
2. Test it with historical data.
3. Verify your risk settings.
4. Check exchange API permissions.
5. Disable withdrawal permissions.
6. Start with an amount you can afford to lose.

## Where can I start?

If you are new to CryptoBot, start with the [Quick Start](../QUICK_START.md) guide.

For exchange and wallet connections, see [Connections](connections.md).

For automated trading, see [Automated Trading](automation.md).

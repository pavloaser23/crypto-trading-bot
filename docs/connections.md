# Exchange & Wallet Connections

CryptoBot supports two types of account connections: **centralized cryptocurrency exchanges (CEX)** through API credentials and **Web3 wallets** through wallet authorization.

Choose the connection type based on the type of cryptocurrency trading you want to perform.

## Centralized Exchanges (CEX)

CryptoBot supports API-based connections to the following cryptocurrency exchanges:

* Binance
* Bybit
* OKX
* KuCoin
* Kraken
* Bitget
* Gate.io
* Bitfinex
* Coinbase

Exchange connections allow CryptoBot to access the required market data and, where supported, execute trades through the exchange API.

### Exchange API Connections

To connect a centralized exchange:

1. Open **CryptoBot**.
2. Go to **Settings → Connections**.
3. Select **Exchange**.
4. Choose your exchange.
5. Enter the required API credentials.
6. Confirm the connection.

API permissions should be limited to the functionality CryptoBot actually needs.

**Do not enable withdrawal permissions unless they are explicitly required and you fully understand the associated risks.**

## Web3 Wallets

CryptoBot also supports Web3 wallet connections for decentralized and on-chain applications.

Supported wallets and wallet connectors include:

* MetaMask
* Trust Wallet
* Coinbase Wallet
* WalletConnect
* Phantom
* Rabby Wallet
* OKX Wallet

Web3 wallets are connected through the wallet authorization interface.

### Connecting a Web3 Wallet

1. Open **CryptoBot**.
2. Go to **Settings → Connections**.
3. Select **Wallet**.
4. Choose the wallet or wallet connector.
5. Approve the connection request in your wallet.

CryptoBot does not require you to provide your wallet seed phrase or private key.

**Never enter or share a seed phrase or private key in CryptoBot.**

## Exchange vs Web3 Wallet

CryptoBot uses different connection methods depending on the type of trading integration.

| Connection  | Authentication       | Typical Use                    |
| ----------- | -------------------- | ------------------------------ |
| Exchange    | API key and secret   | Centralized exchange trading   |
| Web3 Wallet | Wallet authorization | Web3 and on-chain applications |

Only one connection type should be active at a time.

### Exchange Connection

Use an exchange connection when trading through a centralized cryptocurrency exchange.

The connection uses exchange API credentials and can provide access to market data and trading functionality supported by the integration.

### Web3 Wallet Connection

Use a wallet connection for Web3 applications and supported on-chain trading workflows.

The wallet remains under the user's control and transactions require the appropriate wallet authorization.

## API Key Security

Treat exchange API credentials as sensitive information.

Recommended settings:

* Enable only the permissions CryptoBot requires.
* Disable withdrawals.
* Never publish API keys in source code.
* Never commit API credentials to Git.
* Do not share API secrets with other users.
* Rotate credentials if they may have been exposed.
* Use separate API credentials for testing when possible.

## Wallet Security

Web3 wallets require additional care because transactions can interact directly with blockchain networks.

* Never share your seed phrase.
* Never share your private key.
* Check wallet connection requests carefully.
* Review transaction details before approving them.
* Disconnect wallets you no longer use.
* Only connect to applications you trust.

## Connection Workflow

The typical CryptoBot connection flow is:

```text
Open CryptoBot
      ↓
Settings → Connections
      ↓
Choose Exchange or Wallet
      ↓
Authenticate
      ↓
Verify connection
      ↓
Configure trading
```

After the connection is established, continue with the [Quick Start](../QUICK_START.md) guide to configure a strategy and start CryptoBot.

## Troubleshooting

If a connection does not work:

1. Verify that the selected exchange or wallet is correct.
2. Check your API credentials.
3. Verify API permissions.
4. Check your network connection.
5. Confirm that the exchange or wallet is supported by your current CryptoBot version.
6. Review the application logs for errors.
7. Reconnect the account if necessary.

If an API key has been exposed, revoke it immediately and create a new one.

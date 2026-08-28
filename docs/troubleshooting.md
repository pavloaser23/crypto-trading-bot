# Troubleshooting

This guide covers common CryptoBot problems, including application startup errors, exchange API connection issues, Web3 wallet connection problems, and trading bot logs.

If you are using CryptoBot for automated cryptocurrency trading, check the application status and logs before changing configuration or reinstalling the application.

## CryptoBot Does Not Start

If CryptoBot does not start or closes immediately:

1. Make sure you are using a supported version of Windows.
2. Verify that you extracted the complete release archive.
3. Check that the installation completed successfully.
4. Make sure there is enough free disk space.
5. Check Windows Security and antivirus notifications.
6. Try reinstalling the latest release.
7. Restart Windows and try launching CryptoBot again.

If the application requires elevated permissions for a specific operation, Windows may prompt you for administrator access.

Do not disable security software or bypass Windows warnings unless you understand why the application was blocked and have verified the source of the release.

## CryptoBot Crashes or Freezes

If CryptoBot starts but becomes unresponsive:

* Check the application logs.
* Check available system memory.
* Verify your network connection.
* Disconnect and reconnect the trading account.
* Check whether the problem occurs with a specific strategy.
* Restart CryptoBot.
* Make sure you are running the latest version.

If the problem happens only when a particular strategy is active, review its configuration and parameters.

## Exchange Connection Issues

If CryptoBot cannot connect to a cryptocurrency exchange:

### Check API Credentials

Verify that:

* The API key is correct.
* The API secret is correct.
* The credentials have not expired or been revoked.
* The selected exchange matches the API credentials.

### Check API Permissions

Make sure the API key has the permissions required by CryptoBot.

For security:

* Enable only required permissions.
* Disable withdrawal permissions.
* Never share your API secret.
* Revoke compromised API credentials immediately.

### Check Network Connectivity

A stable internet connection is required for exchange API communication and real-time market data.

Also check whether the exchange is experiencing an outage or restricting access from your region.

## Wallet Connection Issues

If a Web3 wallet does not connect:

1. Make sure the wallet is installed and available.
2. Confirm that you are using a supported wallet or wallet connector.
3. Check that the wallet is unlocked when required.
4. Review the connection request in the wallet.
5. Make sure you are connecting to the intended application.
6. Disconnect the wallet and try again.
7. Restart CryptoBot and reconnect.

Never provide a wallet seed phrase or private key to connect a wallet.

## Trading Is Not Starting

If CryptoBot is connected but does not execute trades, check:

* The trading engine is running.
* A strategy has been selected.
* The strategy is enabled.
* The selected market is available.
* Required market data is being received.
* Risk limits are not preventing the trade.
* The account has sufficient available balance.
* The exchange connection is active.
* The strategy conditions have actually generated a trading signal.

A strategy may remain inactive for some time if its entry conditions have not been met. This does not necessarily indicate an application error.

## Orders Are Not Executed

If a trading signal is generated but an order is not executed, check:

* Exchange connectivity
* API permissions
* Account balance
* Minimum order size
* Available trading pair
* Order parameters
* Market liquidity
* Trading fees
* Current market conditions
* Exchange API errors

Review the logs for the specific order and execution error.

## Wallet Transaction Issues

If a Web3 transaction fails or remains pending:

* Check the wallet for the current transaction status.
* Verify the selected network.
* Check the wallet's available balance.
* Make sure sufficient network fees are available.
* Review the transaction details before approving it.
* Check the relevant blockchain network status.

Do not repeatedly approve unknown or unexpected transactions.

## Logs

CryptoBot records application activity in the log file:

```text id="8f4k2m"
logs/cryptobot.log
```

When troubleshooting, check the log for:

* Startup errors
* Connection errors
* API responses
* Strategy errors
* Order execution errors
* Wallet connection errors
* Network errors

When reporting a problem, include the relevant error message and application version.

**Do not publish API keys, API secrets, private keys, seed phrases, or other credentials in logs, screenshots, or issue reports.**

## Before Reinstalling

Reinstalling should generally be a later troubleshooting step.

Before reinstalling:

1. Check the application logs.
2. Verify your configuration.
3. Check exchange or wallet connectivity.
4. Restart CryptoBot.
5. Make sure you are using the latest release.

If you reinstall, keep a backup of any configuration you need to preserve.

## Reporting a Bug

If you believe you have found a CryptoBot bug, provide:

* CryptoBot version
* Windows version
* Steps to reproduce the problem
* Expected behavior
* Actual behavior
* Relevant log output

Remove all sensitive credentials and personal information before submitting an issue.

## Still Having Problems?

If the issue persists, check the other documentation pages:

* [Getting Started](getting-started.md)
* [Quick Start](../QUICK_START.md)
* [Connections](connections.md)
* [Automated Trading](automation.md)
* [Risk Management](risk-management.md)
* [Trading Strategies](strategies.md)
* [FAQ](faq.md)

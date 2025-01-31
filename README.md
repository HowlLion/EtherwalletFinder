# Ethereum Wallet Finder

A Python-based tool to scan Ethereum wallet addresses, fetch their balances, and display the results in a beautified table format. This tool uses the Etherscan API to retrieve wallet balances and transaction data, and utilizes asynchronous operations for efficient scanning.

## Features

- **Fetch Ethereum Wallet Balances**: Retrieve ETH balances for multiple wallet addresses.
- **Transaction Scanning**: Identify and scan wallets involved in transactions (both sender and receiver).
- **Beautified Output**: Display wallet balances in a clear and structured table format using `tabulate`.
- **Asynchronous Operations**: Efficient wallet scanning and API calls using Python’s `asyncio` and `aiohttp`.

## Prerequisites

Before you begin, ensure you have the following installed on your local machine:

- **Python 3.x** (Python 3.7 or above recommended)
- **Etherscan API Key**: You need a valid Etherscan API key. You can get it from [Etherscan](https://etherscan.io/apis).

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/HowlLion/EtherwalletFinderr.git
cd EtherwalletFinder


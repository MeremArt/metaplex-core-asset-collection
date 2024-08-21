# Metaplex Core Asset and Collection Creation

This guide will help you import your wallet as a JSON file, create an asset, and a collection using Metaplex Core on the Solana Devnet. Make sure your wallet has Devnet SOL to cover transaction fees.

## Prerequisites

- Node.js and npm installed on your system.
- A wallet file in JSON format with sufficient Devnet SOL.
- Basic knowledge of Solana and the Metaplex protocol.

## Setup

### 1. Clone the Repository

```bash
git clone https://github.com/MeremArt/metaplex-core-asset-collection.git
cd metaplex-core-asset-collection
```

```bash
npm install

```

## Import Your Wallet

-Ensure your wallet is in the correct JSON format and located at src/wallet.json.

## Update the Code

-In the code, ensure your wallet is imported correctly:

```bash
import wallet from "./wallet.json";
```

## Run the Script

```bash
bun addAsset

```
# metaplex-core-asset-collection

# Sui Move Project Collection

This repository contains three independent Sui Move projects demonstrating different blockchain functionalities.

## Projects

### 1. NFT Creator
A module for creating and managing NFTs on Sui, featuring:
- Minting NFTs with customizable metadata
- Combining two NFTs into a new one
- Burning NFTs
- Withdrawal management for NFT sales

### 2. Pool Party
An Automated Market Maker (AMM) implementation featuring:
- Liquidity pool creation and management
- Token swapping with various mechanisms
- LP token minting/burning
- Constant product formula (x * y = k) implementation

### 3. Suiss Bank
A simplified lending protocol implementation featuring:
- Collateral deposits and withdrawals
- Borrowing and repayment functionality
- Health factor calculations
- Price feed integration

## Running Tests

1. Install Sui CLI if you haven't already:
```bash
cargo install --locked --git https://github.com/MystenLabs/sui.git --branch devnet sui
```

2. Navigate to any project directory and run tests:
```bash
sui move test
```

Each module contains comprehensive test coverage demonstrating the functionality.

## Note
These modules are for educational purposes and demonstrate core blockchain concepts in Sui Move. They should not be used in production without proper security audits and additional safeguards.

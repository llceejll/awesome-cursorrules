# Xian Smart Contracts

## Introduction
Xian is a modern blockchain platform that enables developers to write smart contracts as a restricted Python module. Validators compile that source to canonical Xian VM IR and execute the IR. The local test harness executes through Python.

## What Xian Can Be Used For

- **DeFi Applications**: Create decentralized finance applications including token exchanges, lending protocols, and yield farming platforms
- **NFTs and Digital Collectibles**: Develop NFT marketplaces and digital collectible platforms with ease
- **DAOs**: Build decentralized autonomous organizations with voting mechanisms and treasury management
- **Supply Chain Solutions**: Create transparent supply chain tracking systems
- **Identity Management**: Develop self-sovereign identity solutions
- **Gaming**: Build blockchain-based games with in-game economies

## Key Features

- **Restricted Python source**: Write contracts as a restricted Python module. Validators compile that source to canonical Xian VM IR
- **Event-Driven Architecture**: Use events to track state changes and trigger actions
- **Rich Standard Library**: Access cryptographic functions, hashing utilities, and more
- **Comprehensive Testing Framework**: Test contracts using familiar Python unittest patterns
- **State Management**: Simple yet powerful state management with Variables and Hashes

## Getting Started

To start developing on Xian:

1. Set up a development environment with Python 3.14
2. Install the contract runtime, linter, and testing client with `uv add xian-tech-contracting`. Imports use `contracting`
3. Create your first smart contract using the provided [templates](https://github.com/xian-technology/xian-contracts)
4. Test your contract with `ContractingClient` from `contracting.local`
5. Deploy reviewed source to the Xian network

## Learn More

For more information about Xian and smart contract development:

- [Official Xian Documentation](https://docs.xian.technology)
- [Xian Contracting](https://github.com/xian-technology/xian-contracting)
- [Telegram](https://t.me/xian_network)

## About This Cursor Rules File

This `.cursorrules` file provides guidance to Cursor AI when developing Xian smart contracts, ensuring best practices are followed for contract structure, state management, event handling, and testing.

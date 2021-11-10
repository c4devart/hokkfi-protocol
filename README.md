# Hokkfi Protocol v1

This repository contains the smart contracts source code and markets configuration for Hokkfi Protocol V1. The repository uses Hardhat as development enviroment for compilation, testing and deployment tasks.

## What is Hokkfi?

The hokkfi protocol is an innovative lending protocol that can return profits to both borrowers and lenders by utilizing 'the Use Right Delegated Interest Rate Structure'. The hokkfi protocol is a 100% DAO operated by smart contracts, and all processes such as loans, repayments, and risk management are processed without human intervention.

The hokkfi protocol has the functions to implement a loan with three characteristics: 1) interest free, 2) no maturity, and 3) leverage, and its structure is different from the general lending protocol. The biggest difference in terms of technology can be summarized in three ways: interest rate model, liquidity pool management, and risk management.

## Documentation

The documentation of Hokkfi V1 is in the following [Hokkfi V1 documentation](https://hokkfi-protocol-hokkfi.gitbook.io/hokkfi-protocol-1/) link. At the documentation you can learn more about the protocol.

## Setup

Follow the next steps to setup the repository:

- Install `node.js & npm` and Run `npm install`
- Create an enviroment file named `.env` and fill the next enviroment variables

```
# Mnemonic, only first address will be used
MNEMONIC=

# Add Infura provider keys, alchemy takes preference at the config level
INFURA_KEY=

# Optional Etherscan key, for automatize the verification of the contracts at Etherscan
ETHERSCAN_KEY=

```
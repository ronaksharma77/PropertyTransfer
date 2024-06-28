

# Real Estate Property Transfer Blockchain Project

Welcome to the Real Estate Property Transfer Blockchain Project! This project demonstrates the use of smart contracts to facilitate the transfer of real estate property from a seller to a buyer, with the involvement of a lender approver. The project is built using Solidity and deployed on the Ethereum blockchain using Hardhat. Testing is performed using Chai.Here we are considering a Real Estate Property as a NFT and  a transfer between a seller and a buyer. In case of down payment this process becomes more interesting with a Lender, Inspector and Appraiser.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Project Structure](#project-structure)
- [Contact](#contact)

## Introduction

This project is designed to facilitate the transfer of real estate property from a seller to a buyer using a decentralized approach. The process involves a lender approver and is managed through smart contracts written in Solidity. The project uses Hardhat for deployment and Chai for testing.

## Features

- **Smart Contract for Property Transfer**: Manages the transfer of property from seller to buyer.
- **Escrow Contract**: Ensures secure transactions between parties.
- **Automated Deployment**: Uses Hardhat for deploying contracts to the blockchain.
- **Testing Framework**: Utilizes ``chai`` association library for testing smart contracts.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed.
- Hardhat installed globally.
- A local Ethereum network or access to a testnet.
- Solidity extentions installed in your editor

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/ronaksharma77/PropertyTransfer.git
    cd PropertyTransfer
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

## Usage

1. Compile the contracts:
    ```sh
    npx hardhat compile
    ```

2. Deploy the contracts:
    ```sh
    npx hardhat run scripts/deploy.js --network <network_name>
    ```

3. Interact with the contracts using the Hardhat console:
    ```sh
    npx hardhat console --network <network_name>
    ```

## Testing

1. Run the tests:
    ```sh
    npx hardhat test
    ```

## Project Structure

- **contracts**: Contains Solidity smart contracts.
  - `Escrow.sol`: Manages escrow transactions.
  - `RealEstate.sol`: Manages the transfer of real estate property.

- **ignition/modules**: Deployment scripts.
- **test**: Contains test scripts written in JavaScript using ethers and chai.
- **hardhat.config.cjs**: Hardhat configuration file.
- **package.json**: Node.js dependencies and scripts.

## Contact

Ronak Sharma  
GitHub: [ronaksharma77](https://github.com/ronaksharma77)  
Email: [ronaksharma.rk77@gmail.com](mailto:ronaksharma.rk77@gmail.com)

---

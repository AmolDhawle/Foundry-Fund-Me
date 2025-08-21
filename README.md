# Initial Commit – Foundry Fund Me Project

## Overview

This project is a **Foundry-based implementation** of the _Fund Me_ smart contract, inspired by Patrick Collins’ course.  
It provides a decentralized funding mechanism where users can send ETH, and the contract owner can withdraw funds securely.

## Features

- Solidity smart contract (`FundMe.sol`) for decentralized funding.
- Deployment script (`DeployFundMe.s.sol`) using Foundry scripting.
- Interaction scripts (`Interactions.s.sol`) for funding and withdrawing.
- Unit tests and integration tests to validate functionality (`FundMeTestIntegration.t.sol`).
- Gas-efficient implementation using Solidity 0.8.30.

## Tech Stack

- **Solidity (0.8.30)**
- **Foundry (Forge, Cast, Anvil)**
- **Chainlink Price Feeds** (for USD conversions)
- **Hardhat/Remix inspiration** adapted to Foundry ecosystem

## Folder Structure

├── src
│ └── FundMe.sol
├── script
│ ├── DeployFundMe.s.sol
│ └── Interactions.s.sol
├── test
│ ├── FundMeTest.t.sol
│ └── FundMeTestIntegration.t.sol

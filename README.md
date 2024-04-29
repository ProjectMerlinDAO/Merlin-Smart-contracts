# Project Merlin: Crowdfunding DAO

Welcome to the official GitHub repository for Project Merlin, an innovative DAO and crowdfunding platform leveraging blockchain technology to foster democratic participation and transparent project financing. This platform is designed to enable users to actively participate in the project selection and funding processes through a 'Vote 2 Earn' mechanism and the use of NFTs.

## Overview

Project Merlin integrates blockchain technology to provide a decentralized platform where community members can vote on, fund, and benefit from a variety of projects in the fields of Web3 and GameFi. Our aim is to create a more accessible and fair environment for project financing and development.

## Features

- **Democratic Voting**: Utilizes a 'Vote 2 Earn' mechanism that empowers users to influence project governance.
- **NFT Roles**: Assigns specific roles and privileges in the DAO through NFTs.
- **Multi-Blockchain Support**: Operates across multiple blockchains including Ethereum, Polygon, Avax, and more.
- **Smart Contract Automation**: Manages fund distribution and project approvals through smart contracts to ensure transparency and security.
- **Community-Driven Funding**: Supports projects through community votes and decentralized funding mechanisms.
- **NFT (Non-Fungible Tokens)**: Deployed using an ERC721 standard, enabling the creation, sale, and trade of unique digital assets.
- **Token Sale**: Utilizes an ERC20 token interface for managing a token sale, including features such as setting a maximum cap, handling investments, and transferring tokens.

## Smart Contract Details

This repository contains all smart contracts used in Project Merlin. The contracts are built on Solidity and deployed on the Ethereum blockchain (EVM compatible).

### NFT Contract

- **ERC721 Standard**: For creating unique digital collectibles.
- **Metadata and Enumerable Extensions**: Supports metadata for NFTs and provides enumeration capabilities.
- **Ownership Management**: Includes functions for minting NFTs, transferring ownership, and querying NFT details.

### Token Sale Contract

- **ERC20 Interface**: Standard interface for the tokens used in the sale.
- **Pausable**: Sale can be paused and unpaused by the owner, adding a layer of control over the contract's operation.
- **Ownership Transfers**: Ownership of the token contract can be transferred to a new owner.

### Contracts Overview

- `DAO.sol`: Manages the core functionality of the DAO, including event creation, voting, and reward distribution.
- `MerlinToken.sol`: ERC-20 token contract for the platform's native token, Merlin (MRLN).
- `VotingContract.sol`: Handles all voting mechanisms and reward distributions.
- `NFTContract.sol`: Manages the minting and assignment of role-based NFTs.
- `FundingContract.sol`: Automates the project funding and grant distribution processes.

### Notes

For more information, contact us at info@projectmerlin.io or visit our [website](https://projectmerlin.io).

Thank you for supporting Project Merlin. Together, we're democratizing the future of project funding and governance!

## Getting Started

To get started with Project Merlin, clone this repository and install the necessary dependencies.

```bash
git clone [https://github.com/yourgithub/project-merlin.git](https://github.com/ProjectMerlinDAO/Merlin-Smart-contracts)
cd project-merlin
npm install

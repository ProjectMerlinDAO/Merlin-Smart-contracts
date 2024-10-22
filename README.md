# Project Merlin: Smart Contracts Repository

Welcome to the official repository for Project Merlin's Smart Contracts. Project Merlin is an all-inclusive decentralized platform providing everything needed to turn ideas into fully realized projects within the Web3 ecosystem. This repository contains the Solidity smart contracts that power the MerlinCap DAO, crowdfunding mechanisms, NFT-based governance, and token functionalities.

## Overview

Project Merlin is a multi-functional, decentralized platform that integrates several key services:  
- **MerlinCap DAO**: Community-driven crowdfunding platform.  
- **Merlin’s Guild**: A freelance marketplace.  
- **Excaliber**: On-chain platform for identity building and engagement.  
- **Avalon Launchpad**: IDO launchpad for early-stage projects.  

This repository includes all the necessary smart contracts required to facilitate these services, focusing on community engagement, funding, and decentralized governance.

## Features

- **Democratic Voting**: Through the 'Vote 2 Earn' mechanism, users influence project funding and governance.
- **NFT-Based Roles**: Specific roles and privileges within the DAO are assigned using NFTs, built on the ERC721 standard.
- **Multi-Blockchain Support**: Operates across Ethereum, Polygon, Avax, and other EVM-compatible blockchains.
- **Smart Contract Automation**: Transparent fund distribution and project approval via smart contracts.
- **Tokenomics and Vesting**: ERC20 tokenomics structure with vesting contracts for the MRLN token, handling token distribution and sale mechanisms.
  
## Smart Contract Overview

The contracts in this repository are primarily built using the Solidity language and deployed on Ethereum and other EVM-compatible networks.

### Key Contracts:

1. **DAO.sol**  
   Manages the core DAO functionalities, including event creation, voting, and reward distribution.
   
2. **MerlinToken.sol**  
   ERC20 token contract for the native MRLN token used within the platform.
   
3. **VotingContract.sol**  
   Handles all voting mechanisms and reward distribution for community governance.
   
4. **NFTContract.sol**  
   Manages the minting and assignment of role-based NFTs (ERC721) that grant users different privileges within the DAO.

5. **FundingContract.sol**  
   Automates the project funding, grant distribution, and ensures that the community's decisions are executed transparently.

## Tokenomics

MRLN Token has a total supply of 800,000,000. Below is the token allocation structure:

| Category    | % Allocation | Token Amount | Release Schedule (months) |
|-------------|--------------|--------------|---------------------------|
| Seed        | 2.50%        | 20,000,000   | 14                        |
| Private     | 2.50%        | 20,000,000   | 13                        |
| Strategic   | 2.00%        | 16,000,000   | 10                        |
| Public      | 5.00%        | 40,000,000   | 16                        |
| Airdrop     | 2.00%        | 16,000,000   | 31                        |
| Operations  | 9.00%        | 72,000,000   | 41                        |
| Marketing   | 6.00%        | 48,000,000   | 31                        |
| Grants      | 15.00%       | 120,000,000  | 42                        |
| Dev Team    | 12.00%       | 96,000,000   | 55                        |
| Treasury    | 30.00%       | 240,000,000  | 58                        |
| Liquidity   | 13.00%       | 104,000,000  | 19                        |
| Advisors    | 1.00%        | 8,000,000    | 14                        |

## Getting Started

To interact with the contracts in this repository, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/ProjectMerlinDAO/Merlin-Smart-contracts
cd Merlin-Smart-contracts
npm install
```

### 2. Compile Contracts

Use Hardhat to compile the contracts:

```bash
npx hardhat compile
```

### 3. Deploy Contracts

Deploy the smart contracts to a test or mainnet blockchain:
```bash
npx hardhat run scripts/deploy.js --network <network_name>
```

### Contract Interaction
Once the contracts are deployed, you can interact with them using the Hardhat console or scripts located in the scripts/ directory. Example script usage:
```bash
npx hardhat run scripts/interact.js --network <network_name>
```

## Learn More

For additional resources on how to use these contracts and their functionality, check out:

- [ERC20 Token Standard](https://eips.ethereum.org/EIPS/eip-20)
- [Vesting in Tokenomics](https://medium.com/vesting-guide)
- [Hardhat Documentation](https://hardhat.org/docs/)

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/ProjectMerlinDAO/MRLNToken/blob/main/LICENSE) file for details.

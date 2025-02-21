# Proof of Interaction

## Overview
Proof of Interaction (PoI) is a blockchain-based system designed to verify and reward user interactions within a decentralized ecosystem. By leveraging smart contracts, PoI ensures that engagement is recorded on-chain, promoting transparency and trust.

## Features
- **Decentralized Verification**: Interactions are recorded on the blockchain, ensuring transparency and immutability.
- **Smart Contract Based**: Secure and automated interaction tracking using Ethereum-based smart contracts.
- **Rewards Mechanism**: Participants can earn incentives based on their interactions.
- **Scalability**: Designed to be efficient and scalable for various use cases.
- **Security**: Ensures data integrity and prevents fraudulent interactions.

## Deployment Details
- **Deployed Address**: `0xA285acB73F7371F1d9BD65459719E6d9e7751Bbc`
- **Blockchain**: Edu Chain

## Getting Started
### Prerequisites
- Node.js
- Hardhat
- Metamask Wallet

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/proof-of-interaction.git
   cd proof-of-interaction
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Configure environment variables and network settings.

### Deploying the Contract
To deploy the smart contract on Edu Chain:
```sh
npx hardhat run scripts/deploy.js --network edu
```

### Interacting with the Contract
Use the frontend interface or scripts to interact with the deployed contract. Example:
```sh
npx hardhat console --network edu
> const poi = await ethers.getContractAt("ProofOfInteraction", "0xA285acB73F7371F1d9BD65459719E6d9e7751Bbc");
> await poi.recordInteraction("UserAddress");
```

## Contributing
Contributions are welcome! Feel free to submit issues and pull requests.

## License
This project is licensed under the MIT License.

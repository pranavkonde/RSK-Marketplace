# Marketplace dApp

A decentralized marketplace built with React and Ethereum smart contracts, allowing users to list, purchase, and transfer digital items on the blockchain.

## Features

- List items for sale with custom names and prices
- Purchase items using cryptocurrency
- Transfer item ownership between addresses
- View items owned by specific addresses
- Real-time interaction with Ethereum blockchain

## Smart Contract Features

- Secure item listing and purchasing
- Ownership tracking and transfer functionality
- Prevention of self-purchases by sellers
- Automatic price verification
- Ownership history tracking

## Prerequisites

- Node.js (v12 or higher)
- MetaMask or similar Web3 wallet
- Access to an Ethereum network (testnet or local network)

## Technology Stack

- React.js 18.3.1
- ethers.js 5.7.1
- Solidity ^0.8.0
- Create React App
- Web3 wallet integration

## Installation

1. Clone the repository
2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view the application in your browser.

## Smart Contract Deployment

The marketplace smart contract (`contract.sol`) needs to be deployed to an Ethereum network before the application can be used. Make sure you have:

1. Compiled the smart contract
2. Deployed it to your chosen network
3. Updated the contract address in your application configuration

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production
- `npm run eject` - Ejects from Create React App

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

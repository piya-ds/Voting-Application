# Decentralized Voting Application

This is a decentralized voting application implemented in solidity smart contract and ReactJS. 

All dependencies needed for an application are present in package.json.

```
npm install
```

Initially compile smart-contract using hardhat framework, then run and deploy application in any ethereum based test network(e.g. goerli , sepolia). I have used volta test network. 

```
npx hardhat compile
npx hardhat run --network volta scripts/deploy.js

```

Once the contract is deployed on test network. Copy the contract address and set all the required credentials like API_KEY(RPC endpoint) , private key(if you are using MetaMask), and contract address in the .env file. 


```
npm start

```


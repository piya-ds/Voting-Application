# Decentralized Voting Application

This is a decentralized voting application implemented in solidity smart contract and ReactJS. 

All the dependencies need to execute the application are mentioned in package.json

```
npm install
```

First compile smart contract using hardhat framework and then run and deploy it in any ethereum based test network(e.g. goerli , sepolia) I used volta test network 

```
npx hardhat compile
npx hardhat run --network volta scripts/deploy.js

```

Once the contract is deployed succesfully on test network. Copy the contract address and set all the required credentials like API_KEY(RPC endpoint) , private key(if you are using MetaMask), and contract address in the .env file. 


```
npm start

```


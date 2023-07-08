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


Following are the application screenshots,

![image](https://github.com/piya-ds/Voting-Application/assets/86950823/c07d4d2d-6c02-4d50-a6ac-cca004db0221)

![image](https://github.com/piya-ds/Voting-Application/assets/86950823/1866a23a-cd7e-410c-98fe-19beb4857f5b)

![image](https://github.com/piya-ds/Voting-Application/assets/86950823/48717d5b-fb70-47a2-9b6e-5c77f19da3f5)

![image](https://github.com/piya-ds/Voting-Application/assets/86950823/01a0e7cf-00ce-4c80-829c-ec08805eeb2e)





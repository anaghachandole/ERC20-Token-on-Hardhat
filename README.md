# ERC20-Tokens on Local Hardhat Network

## Description

In this project, we have created our own token, where in the contract: 
* Tekons can be minted only by the owner of the contract.
* The tokens can be burnt or transfered by anyone who holds them.

## Getting Started

Create a new Hardhat Javascript Project using
```
npx hardhat
```

### Installing

* You have to install dependencies in order to connect Remix

```
npm install -g @remix-project/remixd
```

### Executing program

* After setting up everthing let's deploy this contract on the local hardhat network and interact with the deployed contract using Remix
* Connect to Remix
```
remixd -s ./ --remix-ide https://remix.ethereum.org
```
* Now, start the local hardhat network
```
npx hardhat node
```
* Lastly, go to Remix IDE, in the envirnoment section select the Hardhat Provider. Deploy and interact with the contract.

## Help

* Make sure you install all the hardhat dependencies needed to avoid getting an error.
```
npm install @nomicfoundation/hardhat-toolbox      
```

## Authors

Om Tajne


## License

This project is licensed under the MIT License

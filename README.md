# Kickstart powered by smart contracts
Simple Kickstart project powered by Ethereum Solidity Smart Contract using React JS & Next JS

## Creating .env file
Before deploying the contract, remember to create a .env file in the project root folder with the following key=pairs

MNEMONIC=the-list-of-your-12-or-24-word

PROVIDER_URL=your-infura-url

NEXT_PUBLIC_FACTORY_CONTRACT_ADDRESS=your-deployed-factory-contract-addreess

## Before running our project please install all the dependencies
In your console inside your project root folder run:
npm i

## Running some test for our contract
Just execute from the root project "test"

## Deploying contract
From the project root folder, just run: node ethereum/deploy.js

The output will show something like this:
Attempting to deploy from account 0x1546c1A8dFdC6F9B579BA4D6e5e937724A234f64
Contract deployed to 0x5a0cE10C34fA2cA51E37FF382250bD85b2b2A129

* it can take a couple or more minutes to execute.

## Runnig our project
In your console inside your project root folder run:

npm run dev
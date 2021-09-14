# Healthblock
## HealthRecord Storing and sharing using Blockchain
## Tech stack Used Solidity,Ethureum,Reactjs,Web3js
### How to run the project
### Prerequites
### 1.Install ganache
### 2.setup a new project and add truffle-config.js to it.
### 3.setup metamask and add account from the free accounts given in ganache.
### 4.add port 7545 in truffle-config.

    ``` 

cd healthblock/healthblock
npm install
cd src
truffle migrate --reset
cd ..
npm start
```
### Currently Supporting Features
### Role Based Authentication i.e. Doctor and Patient
### Uploading of Report to ipfs and storing it's hash in blockchain
### Rendering Uploaded Reports of patient
### Grant Report Access to  Doctor
### Upload Prescription by Doctor to Patient


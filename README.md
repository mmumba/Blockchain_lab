# Blockchain_lab
experimental block chain

following the contract creation tutorial on:
https://medium.com/@mvmurthy/full-stack-hello-world-voting-ethereum-dapp-tutorial-part-1-40d2d0d807c2


Note that author used web3js Version 0.20.2. 
this is the version in Folder `hello_world_voting2' which works for 
this tutorial.

Folder hello_world_voting uses version web3js 1.0 (not working)

in hello_world_voting2 folder, be sure to run testrpc if you get an error displaying accounts: 

$web3.eth.accounts()


from: https://ethereum.stackexchange.com/questions/23719/invalid-json-rpc-response-undefined-when-running-web3-eth-accounts-node

Install web3 and testrpc packages: npm install ethereumjs-testrpc web3@0.20.1 In the same terminal window, run testrpc: node_modules/.bin/testrpc Open a NEW terminal window (with the first one still open and running), and run node :
```bash
  node_modules/.bin/testrpc 
```
in another terminal

```bash
 ~/hello_world_voting$ node
  Web3 = require('web3')
  web3 = new Web3(new Web3.providers.HttpProvider("http://localhost:8545"));
  web3.eth.accounts
```
should give you list of accounts.
 


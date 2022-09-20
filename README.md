# Building Backend for dApp with Truffle, Node.js, and Webpack

The goal of the project is to define a project structure to built a back-end for the dApp using node.js, truffle, and webpack. 
We will write a simple smart contract that will send some info to the blockchain and emit an event in the response of a successful transaction.

The back-end will perform two main functions:

- Publish transactions to the blockchain network
- Listen to the blockchain events

## Built With

- [Solidity](https://solidity.readthedocs.io/en/v0.6.12/)
- [Truffle](https://www.trufflesuite.com/)
- [Ganache](https://www.trufflesuite.com/ganache)
- [Node.js](https://nodejs.org/en/)
- [Webpack](https://webpack.js.org/)

## Installation

Install the `node.js` and `truffle` globally.

1. Install the code on your local system

   1. Fork this repository (click 'Fork' button in top right corner)
   2. Clone the forked repository on your local file system

   ```
   $ cd /path/to/install/location
   $ git clone https://github.com/zexoverz/dApp-NODEJS/
   ```

2. Change directory into the local clone of the repository

   ```
   $ cd dApp-NODEJS
   ```

3. Install dependencies

   ```
   $ npm install
   ```

### Deploy Smart Contract

    ```
    $ cd app && npm i
    $ npm run ganache
    $ npm run migrate
    ```
    
### Testing

    ```
    $ cd dApp-NODEJS
    $ cd app
    $ npm run test
    $ npm run coverage
    ```
    
 ### Result 
 
 ![alt text](https://github.com/zexoverz/dApp-NODEJS/blob/master/result/CoverageTestDApp.png)
 
 
 ![alt text](https://github.com/zexoverz/dApp-NODEJS/blob/master/result/gasReporterResult.png)


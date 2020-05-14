# FlightSurety Project Writeup
<hr>

FlightSurety is a sample application project for Udacity's Blockchain course.

## Install

This project folder contains the Smart Contract code in Solidity (using Truffle), test (also using Truffle), dApp scaffolding (using HTML, CSS, JS) and server app scaffolding.

To install, download or clone the repo, then:

`npm install` from the root folder of this project.

Create Ganache network having 35 accounts-
ganache-cli -m "<Mnemonic>" --gasLimit 300000000 --gasPrice 20000000000 -a 35


To build the project, run:

`truffle compile`.

### Deploy Client

To run truffle tests:

`truffle test ./test/flightSurety.js`

`truffle test ./test/oracles.js` 

*NB:*

- *Have 35 ganache accounts to run this test*
- *Start the server first and wait some few seconds to register all the oracles.*



To use the dapp, run:

`truffle migrate` 

`npm run dapp`

To view dapp:

`http://localhost:8000`

#### Deploy Server

On a seperate terminal, run

`npm run server` 
`truffle test ./test/oracles.js`

## Deploy

To build dapp for prod:
`npm run dapp:prod`



## Resources

* [How does Ethereum work anyway?](https://medium.com/@preethikasireddy/how-does-ethereum-work-anyway-22d1df506369)
* [BIP39 Mnemonic Generator](https://iancoleman.io/bip39/)
* [Truffle Framework](http://truffleframework.com/)
* [Ganache Local Blockchain](http://truffleframework.com/ganache/)
* [Remix Solidity IDE](https://remix.ethereum.org/)
* [Solidity Language Reference](http://solidity.readthedocs.io/en/v0.4.24/)
* [Ethereum Blockchain Explorer](https://etherscan.io/)
* [Web3Js Reference](https://github.com/ethereum/wiki/wiki/JavaScript-API)
























Requirements
Node.js
Truffle
Ganache (Cli)
Metamask (Browser Extension)
Getting the requirements
Download and install NodeJS

Download and install NodeJS from here.

Install truffle and ganache-cli using node packager manager (npm)

npm install -g truffle
npm install -g ganache-cli
Install metamask browser extension

Download and install metamask from here.

Configuring the project for development
Clone this repository


cd Voting-Test
Run local Ethereum blockchain

ganache-cli
Note: Do not close ganache-cli (the blockchain network needs to be running all the time)

Configure metamask on the browser with the following details

New RPC URL: http://127.0.0.1:8545 (use port: 7545 for ganache gui, update it in the file:truffle-config.js as well)

Chain ID: 1337

Import account(s) using private keys from ganache-cli to the metamask extension on the browser

Deploy smart contract to the (local) blockchain network (i.e ganache-cli)

# on the Voting-Test directory
truffle migrate
Note: Use truffle migrate --reset for re-deployments

Launch the development server (frontend)

cd client
npm install
npm start

Requirements
Node.js
Truffle
Ganache (Cli)
Metamask (Browser Extension)

npm install -g truffle
npm install -g ganache-cli
Install metamask browser extension

cd Voting-Test
Run local Ethereum blockchain

ganache-cli

RPC URL: http://127.0.0.1:8545 (use port: 7545 for ganache gui)

Chain ID: 1337

on the Voting-Test directory
truffle migrate
Note: Use truffle migrate --reset for re-deployments

Launch the development server (frontend)

cd client
npm install
npm start

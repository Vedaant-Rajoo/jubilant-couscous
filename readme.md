# Welcome to the Booking Dapp

[Link to my GitHub Account](https://github.com/Vedaant-Rajoo)

## This is a decentralized application to book meeting rooms using *Web3*, *Solidity* and the test accounts were provided by *Ganache*

 To start

`npm install`

And then initialize a ganache-server by running
Ganache is provided by truffle suite for free it helps to setup a free blockchain server with 10 accounts with 100 ETH each.
This is testnet ETH and only works on localhost only.
For test_networks Kovan, Ropsten check out infura it provides modules of blockchain on the testnet.
[Link to Infura](https://infura.io/)
`node_modules\.bin\ganache-cli`

Then run

`node deploy.js --contractPath=contracts/Booking.sol --contractName=Booking --contractInputParams=OrangeRoom,YellowRoom`

Copy the address to where the contarct has been deployed and change the address in line 22 of app.js

Just open *index.html* and you are good to go
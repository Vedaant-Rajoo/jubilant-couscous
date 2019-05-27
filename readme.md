# Welcome to the Booking Dapp

[Link to my GitHub Account](https://github.com/Vedaant-Rajoo)

## This is a decentralized application to book meeting rooms using *Web3*, *Solidity* and the test accounts were provided by *Ganache*

 To start

`npm install`

And then initiale a ganache-server by running

`node_modules\.bin/ganache-cli`

Then run

`node deploy.js --contractPath=contracts/Booking.sol --contractName=Booking --contractInputParams=OrangeRoom,YellowRoom`

Copy the address to where the contarct has been deployed and change the address in line 22 of app.js

Just open *index.html* and you are good to go
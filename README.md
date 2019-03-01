# Decentralized Star Notary Project

I built a CryptoStar Dapp on Ethereum that implemented all the tasks for the [Blockchain Developer Nanodegree Program Project 5](https://classroom.udacity.com/nanodegrees/nd1309/parts/2e478a90-310b-4703-aa20-efec12eb258c/modules/f615d662-ae4c-4634-ba85-9804b3a7c159/lessons/d2f7eb7c-0368-4f3f-9288-39069990a0e3/project).

## Project Rubric 

The project implementation is according to the [Project Rubric](https://review.udacity.com/#!/rubrics/2297/view).

## Project Specification

I used Truffle tool and OpenZeppelin library in this project.

* Truffle version: v5.0.5
* OpenZeppelin version: v2.1.2
* ERC-721 Token Name: "Awesome Udacity Token"
* ERC-721 Token Symbol: "AUT"
* “Token Address” on the Rinkeby Network: 0xdeA88e02EB6daA00cFef4C6836eA818D9F317c1f


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.


### Prerequisites

Installing Node and NPM is pretty straightforward using the installer package available from the [Node.js® web site](https://nodejs.org/en/).

Install Truffle: ```npm install -g truffle```

### Steps to set up the project

1. Clone the repository to your local computer.
2. Open the terminal and install the packages: `npm install`.
3. Run your application and test your endpoints refer to the "Running the tests" section.

## Running the project locally

Open the package-lock.json and verify that truffle-hdwallet-provider and openzeppelin-solidity dependencies are installed. If not you can always install it with the commands:
```
npm install --save truffle-hdwallet-provider
npm install --save openzeppelin-solidity
```

For starting the development console, run:
```
truffle develop
```

For compiling the contract, inside the development console, run:
```
compile
```

For migrating the contract to the locally running Ethereum network, inside the development console, run:
```
migrate --reset
```

For running unit tests the contract, inside the development console, run:
```
test
```

For running the Front End of the DAPP, open another terminal window and go inside the project directory, and run:
```
cd app
npm run dev
```

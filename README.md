# Fake_news_decentralised

A lot of fake news goes around being circulated in on the Internet these days. This news can be misleading, create false propaganda, disturb communal harmony, affect election results etc. Thus we have created a simple yet powerful solution using Ethereum based smart contracts to prevent propogation and consumption of fake news.
Voters will get incentive based on their participation in voting.For detailed information please refer the smart contract sol file (fake-news-sol.sol) . To see the number of current votes on a news article, people will need to pay a minimal amount for everytime they view the vote count. People can thus deicde by themselves whether the news article is fake or not with the help of the number of votes on an article.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Node packet manager (npm) and nodejs must be installed. 

Web3 package must be installed in the project folder.
```
$npm install web3
```

Metamask extention must be added to the browser. 

### Installing

Download the zip file for the project or clone the repository. 

In the project folder run npm start.
```
$npm start
```
This should start the live server and open the website on browser. 

If errors due to missing packages or modules occur delete the 'node_modules' directory and remove the package name from the package.json file and delete the package-lock.json file.

Then install npm in the project directory.
```
$npm install
```

## Built With

* [ReactJs](https://reactjs.org/) - A JavaScript library for building user interfaces.
* [Solidity](https://solidity.readthedocs.io/en/v0.5.3/) - An object-oriented, high-level language for implementing smart contracts.
* [Ethereum](https://www.ethereum.org/) - Blockchain app platform.


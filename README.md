# Mint NFT

Basic NFT(ERC721) contract deployed to Ethereum Rinkeby testnet. 
Minted an nft by submitting mint transaction to the contract. 
- based on the ethereum.org tutorial https://ethereum.org/en/developers/tutorials/how-to-write-and-deploy-an-nft/

## Table of Contents
1. Introduction 
2. Technologies

## Introduction
This is a basic NFT (ERC721) contract that was deployed to the Ethereum Rinkeby testnet. 
The smart contract is developed with Hardhat, OpenZepellin, and Solidity. 
The deployment of the smart contract is written in Javascript and uses Alchemy to communicate with an Ethereum node. 
The metadata json file as well as the image source included in the json file is pinned to IPFS using Pinata.

## Technologies
@nomicfoundation/hardhat-toolbox: ^1.0.2
@nomiclabs/hardhat-ethers: ^2.1.0,
ethers: ^5.6.9,
hardhat: ^2.10.0
@alch/alchemy-web3: ^1.4.6,
@openzeppelin/contracts": ^4.7.0,
dotenv: ^16.0.1

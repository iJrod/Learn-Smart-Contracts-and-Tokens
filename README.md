### About

- A new repo collating various resources for learning about smart contracts, tokens, crypto, blockchain etc.
- Inspired by wanting to help those in the [Rebels](https://rebels.art/) project
- Jump to [Contents](#contents)

### Initial Basics
#### What is Solidity?
[Solidity](https://docs.soliditylang.org/en/v0.8.11/#) - a programming language created in 2014 by a chap named Gavid Wood. The language is turing complete, high level, and object-oriented and is used for interacting with the [Ethereum Virtual Machine (EVM)](https://ethereum.org/en/developers/docs/evm/). Developers can utilise the language to implement and interact with smart contracts.
> A **smart contract** is a program that governs behaviour on a blockchain. Smart contracts are executed as code and power the Ethereum ecosystem.

### What would I use a smart contract for?
There are many use cases for using smart contracts, below are three common ones. You may well be familiar with NFTs:
1) Non-fungible Tokens (NFT)
2) Decentralised Finance (DeFi)
3) Digital Identity

### Okay. But, I need some more understanding of the basics
Understanding this new wave of technology can be overwelming, even to those who are already highly technical in other fields with specialisms. You're not too late to start learning, in fact, you'll be ahead of the curve. To begin with, take a look at the below:

1) Familiarise yourself with the basics of blockchain and understand the fundamentals of what it is and how it works. The more you study and understand this part, the better your understanding will be for everything else. 
2) Read the whitepapers from [Bitcoin](https://bitcoin.org/en/bitcoin-paper) and [Ethereum](https://ethereum.org/en/whitepaper/)
3) Use free resources such as YouTube to research blockchain, smart contracts, etherium, and bitcoin. Vitalik Buterin (co-founder of Ethereum) presented a talk at DEVCON1 on understanding the Ethereum Blockchain Protocol. I recommend watching it [here](https://www.youtube.com/watch?v=gjwr-7PgpN8) (38:17).
4) Start with the 101's. I recommend taking a look through the contents of [101 Lessons](#basic-101-lessons). Possibly focus on [ERC20](#erc20) to begin with and then the [ERC721](#erc721) protocol.
5) Take a look at the contens of [CryptoZombies](#cryptozombies). I have separated it into two categories - Beginner and Advanced.
6) Read some pre-existing smart contracts using Etherscan. See my section on [Analysing Smart Contracts](#analysing-smart-contracts)


# Contents
- [101 Lessons](#basic-101-lessons)
  - [Solidity](#solidity)
  - [Signatures](#signatures)
  - [ERC721](#erc721)
  - [ERC20](#erc20)
    - [ERC20-101](#erc20-101)
    - [ERC20-102](#erc20-102)
  - [AMM (uniswap)](#amm-uniswap)
  - [AVVE (lending)](#avve-lending)
- [Blockchain DApps Development](#dapps-development)
  - [CryptoZombies](#cryptozombies) 
    - [Beginner / Refresher](#recommended-lessons-beginner--refresher) 
    - [Intermediate / Advanced](#recommended-lessons-intermediate--advanced)
- [buildspace - Web3 Developer Community](#web3-developer-community)
  - [About](#about-buildspace)
  - [Get Started](#get-started)
  - [Projects](#list-of-projects)
- [Analysing Smart Contracts](#analysing-smart-contracts)
  - [Why analyse](#why-analyse)
  - [How to analyse Smart Contracts](#how-to-analyse-smart-contracts)
- [Learn Solidity](#learn-solidity) 
  - [Do I need to be a developer?](#do-i-need-to-be-a-developer)
  - [HelloWorld](#hello-world)
  - [Simple Solidity Examples](#simple-solidity-examples)
  - [Remix IDE](#remix-ide)

# Basic 101 Lessons

## Solidity
[This is an automated workshop that will on using Solidity Smart contracts. It is **aimed at developers who are not familiar with Solidity, or smart contracts**.](https://github.com/l-henri/solidity-101)

## Signatures
[This is an automated workshop that will guide you into learning out to use Ethereum signatures in smart contracts, and in meta transactions. It is **aimed at developpers that are familiar with Solidity**.](https://github.com/l-henri/signatures-101)

## ERC721
[This is an automated workshop that will explain how to deploy an ERC721 token, and customize it to perform specific functions. It is **aimed at developpers that have never written code in Solidity, but who understand its syntax**.](https://github.com/l-henri/erc721-101)

## ERC20
### ERC20 101
[This is an automated workshop that will explain how to deploy and ERC20 token, and customize it to perform specific functions. It is **aimed at developpers that have never written code in Solidity, but who understand its syntax**.](https://github.com/l-henri/erc20-101)

### ERC20 102
[This is an automated workshop that will dive deeper into managing ERC20 tokens. Specifically we will look at patterns using approve() and transferFrom(). It is **aimed at developers used to interacting with and writing smart contracts**.](https://github.com/l-henri/erc20-102)

## AMM (uniswap)
[This is an automated workshop that will guide you into using Uniswap and doing a simple integration in a smart contract. It is **aimed at developpers that are familiar with Solidity and ERC20**](https://github.com/l-henri/amm-101)

## AVVE (lending)
[This is an automated workshop that will guide you into using AAVE and doing a simple integration in a smart contract. It is **aimed at developpers that are familiar with Solidity and ERC20**](https://github.com/l-henri/lending-101)

# DApps Development

## CryptoZombies
CryptoZombies is an interactive school that teaches you all things technical about blockchains. Learn to make smart contracts in Solidity by making your own crypto-collectibles game.
https://cryptozombies.io/

### Recommended Lessons (Beginner / Refresher):
- [How to build a game on Ethereum](https://cryptozombies.io/en/lesson/1)
- [Make the initial game multiplayer](https://cryptozombies.io/en/lesson/2)
- [Advanced Solidity concepts](https://cryptozombies.io/en/lesson/3)
- [Introduce a battle and payable functions to the game](https://cryptozombies.io/en/lesson/4)
- [Allow the game to have tradeables](https://cryptozombies.io/en/lesson/5)
- [Build a frontend for the DApp with Web3.js](https://cryptozombies.io/en/lesson/6)

### Recommended Lessons (Intermediate / Advanced):
- [Lesson 10 - Deploying DApps with Truffle](https://cryptozombies.io/en/lesson/10)
- [Lesson 11 - Testing Smart Contracts with Truffle](https://cryptozombies.io/en/lesson/11)
- [Lesson 14 - How to Build an Oracle](https://cryptozombies.io/en/lesson/14)
- [Lesson 15 - How to build an Oracle - Part 2](https://cryptozombies.io/en/lesson/15)
- [Lesson 16 - How to Build an Oracle - Part 3](https://cryptozombies.io/en/lesson/16)

# Web3 Developer Community
https://buildspace.so/
## About buildspace
Learn by making stuff! Buildspace courses focus on making stuff, not sitting in front of hours of recorded videos. Once you enrol into one of the projects, you will get access to more hanells in the Discord and you'll be able to speak with others doing the same projects as you - in the same cohort. 

Best of all, buildspace **is free.**

## Get started
1) Join the Discord [here](https://discord.gg/Au4JGH32yE) - don't be put off by the minimal channels, that will change soon.
2) Visit [here](https://app.buildspace.so/) to register using your email address
3) Once registered and verified, you can see the Projects dashboard [here](https://app.buildspace.so/home). You don't need to complete the profile, but you can do.
4) Select a project such as [Build a Web3 App with Solidity + Ethereum Smart Contracts](https://app.buildspace.so/projects/CO02cf0f1c-f996-4f50-9669-cf945ca3fb0b)
5) You will then be able to link your Discord account to your buildspace account
6) You will then need to connect your ETH Wallet. I use MetaMask and created a new wallet specificly for this
7) Some projects will require you to wait until the live event, some allow you to start early. Enjoy!

## List of Projects
- [Build a Web3 App with Solidity + Ethereum Smart Contracts](https://app.buildspace.so/projects/CO02cf0f1c-f996-4f50-9669-cf945ca3fb0b)
- [Mint your own NFT collection and ship a Web3 app to show them off](https://app.buildspace.so/projects/CO961ddb5f-f428-4608-9949-a9a2f461eb3f)
- [Create your own mini turn-based NFT browser game](https://app.buildspace.so/projects/CO5cc2751b-e878-41c4-99fa-a614dc910ee9)
- [Build a Web3 app on Solana with React and Rust](https://app.buildspace.so/projects/CObd6d35ce-3394-4bd8-977e-cbee82ae07a3)
- [Ship your own custom NFT collection on Solana w/ Metaplex in a weekend](https://app.buildspace.so/projects/CO77556be5-25e9-49dd-a799-91a2fc29520e)
- [Build your own DAO with just Javascript in a weekend](https://app.buildspace.so/projects/COb520aae3-7925-42f4-a5e7-eaf718933766)
- [Build your own domain service on a Polygon L2 in a weekend](https://app.buildspace.so/projects/CO1f8c72fd-67a3-4f99-90b8-79879c5da1eb)

# Analysing Smart Contracts
## Why analyse
A great way of learning about smart contracts, to further strengthen your knowledge in how they work, is to read and study pre-existing smart contracts.
## How to analyse Smart Contracts
These are some simple steps to get you started:
1) https://etherscan.io/
2) Enter your search details. For example, I am searching on the token: Matic
3) Select the 'Contract' tab from the table view
4) From the current view, you can read the basic contract for the token. Each section is a function that you can expand to read:
![image](https://user-images.githubusercontent.com/26026416/152656016-6920e55a-aca5-4b63-8479-2f9d49a9d949.png)
5) Using the decimals and totalSupply sections, I can read that Matic is a token with 18 decimals and a total supply of 10,000,000,000 tokens - click the hyperlinked total to convert to Ether (1).
6) For some tokens, you may have fields such as Governance (not in Matic's case). Governance will usually have an address that is hyperlinked, allowing you to click to read a specific section of a tokens governance contract.
7) Research different tokens and start understanding the different contracts. You'll learn a lot!

# Learn Solidity
## Do I need to be a developer?
No, you do not need prior developer experience to get started with Solidity. As long as you have the passion and determination to learn, you will achieve it. 1-hour is 4% of your day, and if you do that daily you're already improving and learning something fantastically new.

## HelloWorld
```
pragma solidity ^0.8.10;

contract HelloWorld {
    string public greet = "Hello World!";
}
```
**pragma** defines the compiler version of solidity, it will always be at the top of the file.

## Simple Solidity Examples
Further up I referenced [Solidity](#solidity) under the [101 Lessons](#basic-101-lessons). It would be good to have a quick look through there, see if you understand anything and then put it to the side to work on later.

I do first recommend that you take a look at [Solidity by Example](https://solidity-by-example.org/) which provides you an introduction to Solidity with simple examples - using compiler v0.8.10. Even better, there are [YouTube Videos](https://www.youtube.com/playlist?list=PLO5VPQH6OWdVQwpQfw9rZ67O6Pjfo6q-p) explaining the examples. So you can read, watch, and learn at the same time!

The creator, Smart Contract Engineer, has _three_ **free** challenges [here](https://www.smartcontract.engineer/challenges): Hello World; Value Types; and Function. If you wish to do the other 57+ challenges then you will need to subscribe for $60 - giving you 1-year access. I believe you will be able to practice without subscribing to a platform like this, I mention it due to some people preferring the extra guardrails.

## Remix IDE
Remix IDE is an open source web and desktop application. Remix is used for the entire journey of contract development as well as act as a playground for learning and teaching Ethereum and it helps you write Solidity contracts straight from the browser.
- [Remix IDE](https://remix.ethereum.org/)
- [Remix docs](https://remix-ide.readthedocs.io/en/latest/)

If you wish to download Remix for offline use, you can obtain it from [GitHub](https://github.com/ethereum/remix-project). You can opt to run it with [NPM](https://github.com/ethereum/remix-project#setup) or [Docker](https://github.com/ethereum/remix-project#docker).

# THE KASEICOIN TOKEN 
## An ERC20 Fungible Token Project

![21-4-application-image](https://user-images.githubusercontent.com/80144026/131082836-93881e05-7f6d-489b-a807-fa20b07292d3.png)

___

## BACKGROUND

Imagine...After waiting for years and passing several tests,I was selected by the Martian Aerospace Agency to be part of the first human colony on Mars. As a prominent fintech professional, I will lead a project to develop a monetary system for the new Mars colony. I have decided to base this new monetary system on blockchain technology, and to define a new cryptocurrency called KaseiCoin. (“Kasei” means “Mars” in Japanese.)

KaseiCoin will be a fungible token that is ERC-20 compliant and will be launched in a crowdsale that will allow people who are moving to Mars to convert their earthling money to KaseiCoin.

## What I am Creating

I will create a fungible token that is ERC-20 compliant and that will be minted by using a Crowdsale contract from the OpenZeppelin Solidity library.

The crowdsale contract that you create will manage the entire crowdsale process, allowing users to send ether to the contract and in return receive KSC, or KaseiCoin tokens. Your contract will mint the tokens automatically and distribute them to buyers in one transaction.


## DEMO



https://user-images.githubusercontent.com/80144026/131086231-b6eab740-0092-4432-bba2-59b33488896f.mov



### Smart Contract creation and deployment in REMIX IDE

<img width="1792" alt="Screen Shot 2021-08-26 at 11 03 45 PM" src="https://user-images.githubusercontent.com/80144026/131085079-7cc6c3ca-571a-4423-8cfd-4ef45060bd18.png">


### Testing Functionalities of Remix, Ganache and Metamask

<img width="318" alt="Screen Shot 2021-08-26 at 10 35 39 PM" src="https://user-images.githubusercontent.com/80144026/131086305-cf01ab84-9127-46db-ae80-7c7aa0a74c3a.png">

<img width="705" alt="Screen Shot 2021-08-26 at 10 36 14 PM" src="https://user-images.githubusercontent.com/80144026/131086315-7e67f33b-12ce-46dc-adfa-790193d48476.png">

<img width="1727" alt="Screen Shot 2021-08-26 at 10 59 03 PM" src="https://user-images.githubusercontent.com/80144026/131086330-8474bf47-930b-4a71-b38e-2ef3bfadede5.png">

<img width="312" alt="Screen Shot 2021-08-27 at 12 06 44 AM" src="https://user-images.githubusercontent.com/80144026/131086864-c8909674-3677-4d42-9fc6-2b00f0735823.png">

<img width="314" alt="Screen Shot 2021-08-26 at 11 14 55 PM" src="https://user-images.githubusercontent.com/80144026/131086371-bb06bcce-9bde-4d40-aabf-857497559494.png">

<img width="341" alt="Screen Shot 2021-08-26 at 11 14 45 PM" src="https://user-images.githubusercontent.com/80144026/131086377-7d6110a7-62f5-40cb-82e9-7ee4094c47f6.png">

<img width="1194" alt="Screen Shot 2021-08-26 at 11 13 49 PM" src="https://user-images.githubusercontent.com/80144026/131086385-a7a1ca52-6c98-4a8d-8f18-130bca291ec6.png">





---

## Technologies

* This project is written in Solidity version ^0.5.0 within the REMIX IDE environment 
* Google Chrome Browser
* Ganache, download here: https://www.trufflesuite.com/ganache
* Metamask, download here: https://metamask.io
___

### Imports


* KaseinCoin.sol

import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/ERC20.sol";
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/ERC20Detailed.sol";
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/ERC20Mintable.sol";

* KaseinCoinCrowdsale.sol

import "./KaseiCoin.sol";
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/Crowdsale.sol";
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/emission/MintedCrowdsale.sol";

---

## Installation Guide

Clone to your repo and upload to Remix, Solidity.


___

## License 
 
MIT

# Module_21_Challenge

# KaseiCoin Crowdsale

---

## Introduction:

The premise of this project is that after waiting for years and passing several tests I have been selected by the Martian Aerospace Agency to be part of the first human colony on Mars. As a prominent fintech professional, I was chosen to lead a project to develop a monetary system for the new Mars colony. I have decided to base this new monetary system on blockchain technology, and to define a new cryptocurrency called KaseiCoin. (“Kasei” means “Mars” in Japanese.)

KaseiCoin will be a fungible token that is ERC-20 compliant. I will launch a crowdsale that will allow people who are moving to Mars to convert their earthling money to KaseiCoin, minting the token by using a Crowdsale contract from the OpenZeppelin Solidity library. The crowdsale contract that I create will manage the entire crowdsale process, allowing users to send ether to the contract and in return receive KAI, or KaseiCoin tokens. My contract will mint the tokens automatically and distribute them to buyers in one transaction.

---

## Technologies

This project leverages python 3.7 and Solidity.

---

## Installation Guide

Before running the application first install the following dependencies:

```python
  pip install mkdocs
```

---

## Usage

To use the KaseiCoin Crowdsale Contract:

Clone the Module_21_Challenge repository from GitHub:

'git clone https://github.com/jpweldon/Module_21_Challenge.git'

Review KaseiCoin.sol, KaseiCoinCrowdsale.sol, and the screenshots included in the Evaluation Evidence section of this README. The screenshots included in the Evaluation Evidence section of this README are also included in the Evaluation_Evidence folder.

Open the KaseiCoin.sol and KaseiCoinCrowdsale.sol files in the Remix IDE at (https://remix.ethereum.org/#optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.7+commit.e28d00a7.js).

Compile the KaseiCoin.sol smart contract.

Compile the KaseiCoinCrowdsale.sol smart contract.

Navigate to the “Deploy & Run Transactions” pane, and then make sure that “JavaScript VM” is selected as the environment.

Click the Deploy button to deploy the smart contracts.

---

## Evaluation Evidence

The screenshots of my work from each subsection of the Challenge assignment are included. The screenshots are also included in the Evaluation_Evidence folder.

Screenshot following creation and compilation of the KaseiCoin Token Contract:

![ScreenShot_Create_the_KaseiCoin_Token_Contract](https://user-images.githubusercontent.com/85202691/141718477-fa70a1a1-ad36-4550-a613-68195498e3a6.png)

Screenshot following creation and compilation of the KaseiCoin Crowdsale Contract:

![ScreenShot_Create_the_KaseiCoin_Crowdsale_Contract](https://user-images.githubusercontent.com/85202691/141718515-f9b850cb-1bd0-42d4-a70b-fee59b700d9f.png)

Screenshot following creation and compilation of the KaseiCoin Deployer Contract:

![ScreenShot_Create_the_KaseiCoin_Deployer_Contract](https://user-images.githubusercontent.com/85202691/141718525-0cdb52e7-878c-4109-b506-f1820a5e6e39.png)

---

## Contributors

John P Weldon

Email: johnpweldon01@gmail.com

[LinkedIn:] (www.linkedin.com/in/john-weldon-333b0695)

---

## License

MIT

---
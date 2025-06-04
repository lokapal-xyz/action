---
date: '2025-03-09T16:43:23-03:00'
draft: false
title: 'Part 1 – The Core Structure of ENS DAO'
---

## ENS DAO Basics

For readers who want to explore ENS DAO in full detail, the [**ENS DAO Basics**](https://basics.ensdao.org/) website is an excellent official resource. Here, we offer a condensed overview to give you a clear and accessible starting point.

Let's start with a brief rundown of the main aspects of ENS:

- ENS stands for **"Ethereum Name Service"**. 
- It's a decentralized naming protocol.
- It runs on the Ethereum blockchain.
- ENS domain names are human-readable (e.g., **vitalik.eth**).
- You can link your wallet address to an ENS domain.
- You can integrate regular DNS domain names with .eth names.

Here are some key facts about ENS governance and organization:

- ENS was founded in 2017 by Nick Johnson.
- As of 2025, over 3.5m .eth ENS names have been registered.
- ENS is governed by the ENS DAO.
- The ENS DAO is represented in the real world by the ENS Foundation

ENS names are **human-readable**, which enhances account usability. Instead of working with a long hexadecimal address, users can share their ENS name (e.g., satoshi.eth), preventing mishandling. ENS already has many applications, but its potential is far from exhausted. As both user adoption and institutional adoption increase, new use cases may emerge.

---

## ENS Token

The $ENS token is a governance token used to govern key components of the ENS protocol. Here are some of its key aspects:

- The $ENS token was launched on November 8, 2021, alongside the ENS DAO.
- $ENS is an ERC-20 token on the Ethereum blockchain. 
- Holders of $ENS can delegate tokens to **Delegates**. 
- Delegates use delegated $ENS tokens to submit and vote on proposals.
- Proposals can implement changes to the ENS protocol and spending from the DAO’s treasury. 
- A total of 100m $ENS tokens were minted.
- Each token representing a single vote in the DAO.
- $ENS tokens can be purchased on centralized and decentralized exchanges. 

The initial $ENS distribution consisted of:

- 25% (25m $ENS) to core contributors, ecosystem partners, and community members. 
- 25% (25m $ENS) to be claimed as an airdrop by previously owned addresses.
- 50% (50m $ENS) to the DAO’s treasury, with a set release schedule.

The ENS DAO can mint more tokens once per year, according to a "2% max" rule. If the DAO passes a proposal to increase its total supply, it has to wait at least 365 days for its next minting window.

---

## ENS DAO Contracts

These are the most relevant ENS DAO contracts:

- [**wallet.ensdao.eth**](https://etherscan.io/address/0xfe89cc7abb2c4183683ab71653c4cdc9b02d44b7): the ENS DAO treasury.
- [**token.ensdao.eth**](https://etherscan.io/address/0xc18360217d8f7ab5e7c516566761ea12ce7f9d72): the $ENS token contract. 
- [**governor.ensdao.eth**](https://etherscan.io/address/0x323a76393544d5ecca80cd6ef2a560c6a395b7e3): the proposal management contract.
- [**tokenlock.ensdao.eth**](https://etherscan.io/address/0xd7a029db2585553978190db5e85ec724aa4df23f): the token lock contract. This contract originally retained 45% of the total supply of $ENS, unlocking them over a 4-year span.

---

## ENS Registration and Protocol Revenue

The ENS protocol generates revenue from the registration of **".eth"** ENS names. Here are some key aspects:

- .eth names can be registered on app.ens.domains and other third-party registration platforms.
- Registration revenue goes to smart contracts that are controlled by the ENS DAO. 
- The price for registering a .eth name varies depending on the length of characters (less characters = higher prices).
- Names can be registered for any amount of time into the future.
- Once names expire, registrants have a 90 day grace period to extend ENS names registration.
- Once the grace period expires, a name enters a temporary premium auction over 21 days.
- By the end of the 21 days, the name is available to register at the normal registration fee.

---

## ENS Foundation

The ENS Foundation is a Cayman Island incorporated foundation that represents the ENS DAO in the real world:

- The ENS Foundation is a non-profit, and has no shareholders.
- The ENS Foundation has three directors: [**Nick Johnson**](https://twitter.com/nicksdjohnson), [**Kevin Gaspar**](https://twitter.com/ValidatorEth) and [**Alex Van de Sande**](https://twitter.com/avsa).
- Directors are in charge of the day-to-day running of the foundation.
- The ENS Foundation has one supervisor, in charge of monitoring directors' performance. 
- Directors handle operational costs, which they are later reimbursed from the DAO.
- The ENS DAO (known internally as "The Council") holds administrative control over the Foundation.
- The DAO may instruct the directors to take action on behalf of the Foundation.

---

## ENS DAO Constitution

The goals and intentions of the ENS DAO are set out in the ENS DAO Constitution. The Constitution contains five articles:

- *Article 1* – Name ownership shall not be infringed
- *Article 2* – Fees are primarily an incentive mechanism
- *Article 3* – Income funds ENS and other public goods
- *Article 4* – ENS integrates with the global namespace
- *Article 5* – Amendments to this Constitution by majority vote

The full ENS DAO Constitution is available [**here**](https://ensdao.eth.limo/constitution.pdf).

---

## ENS Endowment 

The Endowment’s goal is to ensure the long-term viability of ENS by ensuring it can meet its ongoing financial obligations despite internal and external volatility. The goal is to set aside a substantial amount of the DAO’s treasury and incoming revenue from registration fees. 

To achieve this goal, the DAO will need to diversify and invest its treasury and future registration fees to create a sustainable funding source. Doing so will allow the DAO to continue to operate and fund the ongoing development of ENS, irrespective of market conditions.

- The endowment fund manager is [**Karpatkey**](https://twitter.com/karpatkey). 
- The Endowment was initiated on March 7, 2023. 
- It was funded with an initial amount of 16,000 ETH. 
- The endowment wallet is controlled by the DAO and managed by Karpatkey. 

---

## ENS DAO Security Council

In the case of a proposal threatening the ENS DAO, a designated Security Council can intervene. The council is not allowed to submit proposals or amend them. A 4-of-8 Safe multi-sig has authorization to act only in emergencies such as:

- Attacks on the DAO treasury.
- Governance attacks due to low voter participation.
- Proposals in misalignment with the ENS Constitution, either intentionally or not.

---

On the next article, we'll explore ENS DAO voting mechanisms, proposals creation, working groups, and more.

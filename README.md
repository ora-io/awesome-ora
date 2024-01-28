# 🌈 Awesome Hyper Oracle

## 📑 Table of Contents

- [🌈 Awesome Hyper Oracle](#-awesome-hyper-oracle)
  - [📑 Table of Contents](#-table-of-contents)
  - [🌍 Overview](#-overview)
  - [🔮 zkOracle Ecosystem](#-zkoracle-ecosystem)
  - [🗺️ zkGraph Ecosystem](#️-zkgraph-ecosystem)
    - [General](#general)
    - [DeFi \& DEX \& MEV](#defi--dex--mev)
    - [Onchain API Oracle](#onchain-api-oracle)
    - [NFT](#nft)
    - [Proof of X](#proof-of-x)
    - [Libraries \& Utils](#libraries--utils)
    - [Security](#security)
    - [Others](#others)
  - [💡 Project Ideas](#-project-ideas)
  - [📜 ERC-6150 \& ERC-7007](#-erc-6150--erc-7007)
  - [🔧 Other Contribution by Hyper Oracle](#-other-contribution-by-hyper-oracle)
    - [World Supercomputer](#world-supercomputer)
  - [Improvement Proposals](#improvement-proposals)
    - [Open Source Libraries](#open-source-libraries)
    - [Open Grant Contribution](#open-grant-contribution)

## 🌍 Overview

This list focuses on the work related to the Hyper Oracle ecosystem.

This includes the [zkOracle](https://ethresear.ch/t/defining-zkoracle-for-ethereum/15131) ecosystem, the [zkGraph](https://docs.hyperoracle.io/zkgraph/introduction) ecosystem, the ERC ecosystem co-authored by Hyper Oracle, and other Hyper Oracle contributions.

Developers can leverage zkOracle's historical data access, and zkGraph's programmable zkVM-powered trustless compute to build decentralized application with more data and more compute.

## 🔮 zkOracle Ecosystem

_A Collection of Projects Using Hyper Oracle zkOracle._

- [zkAMM](https://github.com/Defi-3/zkAMM-contracts): A zkOracle-based automated market maker that is fully scalable with unlimited computation resources.
- [dETF](https://github.com/Defi-3/dETF-Contract): A zkOracle-based fully onchain and decentralized ETF protocol.
- [Unic](https://twitter.com/viaprize/status/1711312453219524638): A decentralized identity platform, using zkOracle for onchain ML.
- [ZKredible](https://twitter.com/viaprize/status/1711312450405159377): A privacy-preserving and censorship-resistant credit record evaluation system, using zkOracle for onchain aggregation of zkML.
- [zkKYC](https://github.com/hyperoracle/zkKYC-story-hackathon): A zkOracle-based hook that brings offchain kyc data to onchain Story Protocol. This project was [developed during Story Protocol Alpha Hackathon and won second place](https://twitter.com/StoryProtocol/status/1734259414591512932).

## 🗺️ zkGraph Ecosystem

_A List of zkGraphs Built by Hyper Oracle and Community._

### General

- [zkGraph Examples](https://github.com/hyperoracle/zkgraph-cli/tree/main/packages/create-zkgraph/templates): A list of zkGraphs, including Uniswap Price Calculation, zkAutomation-based zkGraph, and multi-address based zkGraph. This is the implementation by Hyper Oracle.
- [zkUsecases](https://www.hyperoracle.io/app/cases): A list of zkGraphs, including SeaPort Trading Activity, and USDT Transfer Volume Per Block. This is displayed on Hyper Oracle's [use case page](https://www.hyperoracle.io/app/cases).

### DeFi & DEX & MEV

- [Marine](https://github.com/hyperoracle/marine): A zkGraph as liquidation protocol on Compound Protocol. This is tracking 15+ addresses, and 90+ events at the same time.
- [zkToken](https://github.com/hyperoracle/zkToken): A zkGraph as ERC20 token monitor. This monitors whether there is any selling or pumping behavior in the whale account, and then issue an alert signal.
- [Dex Vigil](https://github.com/issa-me-sush/dex-vigil-zkgraph): A zkGraph that detects anomalous trading behavior and possibly prevent exploits.
- [Cross-chain Asset Transfer](https://github.com/issa-me-sush/cross-chain-asset-transfer): An example zkGraph implementation of cross-chain asset / token / credit transfer system.
- [MEV Detection](https://github.com/guha-rahul/Proof-of-Sandwiched): A PoC zkGraph that proves a user's behavior such as `Swap` has been harmed by an MEV bot.
- [BTC 2 ETH](https://github.com/Mingzhe-W/zkgraph/tree/main/Btc2EthConversionRate): A zkGraph that calculates for BTC to ETH conversion rate.
- [zkInsurance](https://github.com/Mingzhe-W/zkgraph/tree/main/zkInsurrance): A zkGraph that auto-generates proofs for claiming insurance.
- [zkSafeMixer](https://github.com/YolaYing/ZK-Tornado-Cash): A zkGraph that warns downstream contracts if there's blacklisted address's fund in the mixer.

### Onchain API Oracle

- [Onchain Price Oracle](https://github.com/YolaYing/Onchain-Price-Oracle): A zkGraph that implements TWAP oracle.

### NFT

- [BAYC Hacked](https://github.com/arjanjohan/zkgraph-hacked-bayc): A zkGraph that tracks hacked BAYC by transfer event.
- [Free Mints](https://github.com/arjanjohan/zkgraph-track-free-mints): A zkGraph that monitors free mints of NFT.
- [Proof of OG of Azuki NFT](https://github.com/guha-rahul/Proof-of-OG-of-Azuki-NFT): A zkGraph that proves the OG mint of Azuki NFT.
- [Proof of Mint](https://github.com/Gathin23/Proof-of-Mint-zkgraph): A zkGraph that tracks all the address that has minted DOP token on sepolia.

### Proof of X

- [Proof of Pool](https://github.com/agxmbhir/proof-of-pool): A zkGraph that tracks newly created Uniswap v3 pools.
- [Proof of Bridge](https://github.com/agxmbhir/proof-of-bridge): A PoC of cross-chain bridge uses a zkGraph to bridge tokens from sepolia to goerli with zkp.
- [Proof of Whale](https://github.com/Thirumurugan7/Proof-Of-Whale): A zkGraph that verifies if a wallet is a big player even if your funds or assets are compromised, as the whale status is confirmed by the address that initiated the event, not the recipient.
- [Proof of Blacklist](https://github.com/varun-doshi/Proof-of-Blacklist-zkGraph): A zkGraph for tracking new blacklisted address of USDT.
- [Proof of Ownership](https://github.com/varun-doshi/Proof-of-Ownership-zkGraph): A zkGraph that accesses historical ownership change of the Azuki NFT collection.
- [Proof Of Membership](https://github.com/HAPPYS1NGH/dd-member-zkgraph): A zkGraph that proves an address is a member of Developer DAO.
- [Proof of Approved by rupam-04](https://github.com/rupam-04/proof-of-approved): A zkGraph that accesses historical approved amount of token.
- [Proof of Approved by udhaykumarbala](https://github.com/udhaykumarbala/proof-of-approval): A zkGraph that accesses historical approved amount of token.
- [Proof of Whale](https://github.com/Thirumurugan7/Proof-Of-Whale): A zkGraph that checks for a special "isWhale" event.
- [Proof of New Player](https://github.com/Thirumurugan7/Proof-of-new-player): A zkGraph that checks for "NewPlayer" event.

### Libraries & Utils

- [zkGraph String Utils](https://github.com/udhaykumarbala/zkgraph-stringutils): A zkGraph that helps offload the string operation to offchain and gives the mechanism to prove the offline calculated values.
- [zkGraph Math Utils](https://github.com/Gathin23/Math-zkgraph): A zkGraph that helps offload Math operations offchain and gives the mechanism to prove the offline calculated values.

### Security

- [Secure Watcher](https://github.com/HAPPYS1NGH/secure-watcher-zkgraph): A zkGraph that watches for activities which are similar to compromise of Private Key.

### Others

- [Decentralized Moderation](https://github.com/issa-me-sush/decentralized-content-moderation): Content moderation system based on zkGraph for a decentralized social network or any kind of customized DAO or decentralized network/ecosystem.


## 💡 Project Ideas

_Ideas to Build with zkOracle or zkGraph._

| Idea                                       | Value of Hyper Oracle                                                   | Difficulty | Additional Note                                                                                                                                          |
|--------------------------------------------|-------------------------------------------------------------------------|------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Dashboard for NFT Marketplaces             | Access Historical Trading Data of Blur, Looksrare, CryptoPunks, Memswap | 💥          |                                                                                                                                                          |
| Onchain DefiLlama                          | Access Historical Data of AAVE, Compound, Morpho                        | 💥          | Performs calculations on protocol inflow and outflow, TVL, protocol revenue, protocol health ratio, protocol yield for user.                             |
| Onchain L2BEAT                             | Access Historical Data of L2's contract on L1, and Trustless Compute    | 💥          | Calculate TVL (Canonical, External, Native) of L2; Calculate TPS (via L2 blocks settled on L1) of L2.                                                    |
| zkGraphs for ERCs                          | Access Historical Data of Standardized ERCs, and Trustless Compute      | 🔥          | Build zkGraphs for standards such as ERC-20 (maybe also weird ERC-20s) and ERC-721.                                                                      |
| Onchain Price Oracle                       | Trustless Compute of Pricing                                            | 💥          | Build price oracles like TWMP (time-weighted median price), or even something like [UTXOracle](https://utxo.live/oracle/).                               |
| zkGraphs as Public Goods Libraries         | Trustless Compute of Algorithms                                         | 💥          | Build libraries such as [onchain](https://github.com/emo-eth/onchain) with zkGraph.                                                                      |
| Traditional Oracle Services                | Trustless Compute, and Automation                                       | 🌋          | Build VRF (Verifiable Random Function), VDF (Verifiable Delay Functions), FSS (Fair Sequencing Service).                                                 |
| Automation Apps                            | Trustless Compute, and Automation                                       | 🔥          | Implement auto-renewal of ENS, automated strategies, onchain liquidator keepers for DeFi protocols...                                                    |
| DeFi Protocols Remastered                  | Trustless Compute of DeFi Logic, and Automation                         | 🌋          | Use zkGraphs to reimplement protocols like AAVE, Curve, Uniswap v3, or v4.                                                                               |
| Experiemental Games                        | Trustless Compute of Game Logic                                         | 💥          | Implement games like etherquake and GameOfLife instead of pure onchain Solidity.                                                                         |
| Proof of Voting Power                      | Access Historical `checkpoints`, and Trustless Compute                  | 🔥          |                                                                                                                                                          |
| Proof of Whale                             | Access Historical `balances` and Trustless Compute                      | 🔥          |                                                                                                                                                          |
| Proof of Vesting                           | Access Historical Data of ERC-20                                        | 💥          | Query historical data of a token’s vesting status, and determine if the vesting schedule is performed in a correct way.                                  |
| Proof of Ownership                         | Access Historical `ownerships` of ERC-721                               | 🔥          |                                                                                                                                                          |
| Proof of Mint                              | Access Historical `startTimestamp` and Trustless Compute                | 🔥          |                                                                                                                                                          |
| Proof of Credit                            | Access Historical Data of DeFi and Trustless Compute                    | 🔥          |                                                                                                                                                          |
| Proof of Degen                             | Access Trading History of User and Trustless Compute                    | 🔥          | Similar to [DegenScore](https://degenscore.com/), build an onchain verifiable one to determine if an account has enough risk tolerance ability.          |
| Proof of Liveness                          | Access Historical Batch Commit Activity of L2 and Trustless Compute     | 💥          | Get all the historical data and analyze which L1 blocks have no `commitBatch` or `finalizeBatchWithProof` events to know if the rollup has any downtime. |
| Proof of OG                                | Access Historical Data of User on NFT, Contract Interactions            | 🔥          |                                                                                                                                                          |
| Proof of Sandwiched                        | Access Historical `Swap` Event of User and Trustless Compute            | 🔥          | Prove that a user's behavior such as `Swap` has been harmed by an MEV bot, and thus compensate the account.                                              |
| Vault for Arbing Withdrawals on L2 bridges | Trustless Compute of Arbing, and Automation                             | 🌋          | Automated arbitrage through optimistic L2 bridges.                                                                                                       |
| Very Low Gas DEX                           | Trustless Compute of Aggrgating, and Automation                         | 💥          | Aggregate tiny trades, for a cheaper DEX.                                                                                                                |
| L2 – L2 transfer using Proof of Burn       | Trustless Compute of Transfer, and Automation                           | 🌋          | User burns tokens on L2 A, and posts the proof of burn on L2 B for bridging.                                                                             |
| Automated Risk Scoring of Pools            | Access Historical Data, Trustless Compute, and Automation               | 🌋          | A combination of credit score of an account, and bad debt scoring of a pool.                                                                             |
| Better Wallets                             | Trustless Compute as Intent-solver, and Automation                      | 🌋          |                                                                                                                                                          |
| zkOracle with Uniswap Hooks                | Trustless Compute of Offchain Logic                                     | 💥          | Use `beforeX` hook to verify the zkp from zkOracle.                                                                                                      |
| Dark Forest Rank                           | Trustless Compute of Blockchain World Ranking                           | 💥          | Analyze full history and operations of a contract or account to generate a ranking of all contracts and accounts (value, trade profit, MEV profit).      |

*: Difficulty levels are from Eazy (🔥) -> Normal (💥) -> Advanced (🌋).

Read more from Hyper Oracle's idea posts: [1](https://mirror.xyz/hyperoracleblog.eth/Tik3nBI9mw05Ql_aHKZqm4hNxfxaEQdDAKn7JKcx0xQ), [2](https://mirror.xyz/hyperoracleblog.eth/AG3tFPgesKw4d0VnwPIYjjoOzVSoc3R4chKcyY4s0ks).

## 📜 [ERC-6150](https://eips.ethereum.org/EIPS/eip-6150) & [ERC-7007](https://eips.ethereum.org/EIPS/eip-7007)

_Protocols Adopts Standards Contributed by Hyper Oracle._

- [ZenetikNFT](https://ethglobal.com/showcase/zenetiknft-1ph5r): A ERC-7007 based AIGC-NFT project. This utilizes genetic AI to breed new NFT images.
- [7007.studio](https://twitter.com/7007_studio): A ERC-7007 based platform offering on-chain AIGC generation services and monetizing of AI Models.

## 🔧 Other Contribution by Hyper Oracle

_Hyper Oracle's Contribution to General Web3, Blockchain, and Crypto Space._

### World Supercomputer

- [Litepaper as Co-initiator](https://review.stanfordblockchain.xyz/p/towards-world-supercomputer)
- [WSC Summit 2023](https://hackmd.io/@EEEZ5333/World-Supercomputer-Summit-2023-Recap)
- [WSC Community Day @Token2049](https://hackmd.io/@EEEZ5333/World-Supercomputer-Token2049-Recap)

## Improvement Proposals

- [Ethereum/ERC-6150](https://eips.ethereum.org/EIPS/eip-6150)
- [Ethereum/ERC-7007](https://eips.ethereum.org/EIPS/eip-7007)
- [Celestia/CIP-5](https://github.com/celestiaorg/CIPs/blob/main/cips/cip-5.md)

### Open Source Libraries

- [create-zkgraph](https://www.npmjs.com/package/create-zkgraph)
- [zkgraph-api](https://www.npmjs.com/package/@hyperoracle/zkgraph-api)
- [zkgraph-lib](https://www.npmjs.com/package/@hyperoracle/zkgraph-lib)
- [zkgraph-cli](https://www.npmjs.com/package/@hyperoracle/zkgraph-cli)

### Open Grant Contribution

- [Ethereum Foundation KZG Ceremony Grant](https://blog.ethereum.org/2022/12/15/kzg-ceremony-grants-round)/[Halo2-based KZG Ceremony Client](https://mirror.xyz/hyperoracleblog.eth/vPwYqWWmsWW5JPqlOjk9fMo7Ba72D40Ph9SyjthEZDE)
- [Compound Grant](https://www.comp.xyz/t/compound-grants-program-lessons-and-next-steps/2264)/[Marine](https://github.com/hyperoracle/Marine)

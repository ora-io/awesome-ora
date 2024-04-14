# ⃝ Awesome ORA

## 📑 Table of Contents

- [ ⃝ Awesome ORA](#-awesome-ora)
  - [📑 Table of Contents](#-table-of-contents)
  - [🌍 Overview](#-overview)
  - [🤖 AI Oracle Ecosystem](#-ai-oracle-ecosystem)
    - [General](#general)
    - [AIGC-NFT (ERC-7007)](#aigc-nft-erc-7007)
  - [🔮 ZK Oracle CLE Ecosystem](#-zk-oracle-cle-ecosystem)
    - [General](#general-1)
    - [DeFi \& DEX \& MEV](#defi--dex--mev)
    - [Onchain API Oracle](#onchain-api-oracle)
    - [NFT](#nft)
    - [Game](#game)
    - [Proof of X](#proof-of-x)
    - [Libraries \& Utils](#libraries--utils)
    - [Security](#security)
    - [Others](#others)
  - [💡 Project Ideas](#-project-ideas)
    - [AI Oracle](#ai-oracle-ideas)
    - [zkOracle](#zkoracle-ideas)
  - [🔧 Other Contribution by ORA](#-other-contribution-by-ora)
    - [World Supercomputer](#world-supercomputer)
  - [Improvement Proposals](#improvement-proposals)
    - [Open Source Libraries](#open-source-libraries)
    - [Open Grant Contribution](#open-grant-contribution)

## 🌍 Overview

This list focuses on the work related to the ORA ecosystem.

This includes the [AI Oracle (OAO, Onchain AI Oracle)](https://mirror.xyz/orablog.eth/qLBIR_yxmpFJ4dg5p5Sn8Wz46aQDTG1jCW8myeE7zZ8) and [zkOracle](https://ethresear.ch/t/defining-zkoracle-for-ethereum/15131) ecosystem, the ERC ecosystem co-authored by ORA, and other ORA contributions.

## 🤖 AI Oracle Ecosystem

_A Collection of Projects Built on AI Oracle._

### CLEs (Models)

- Grok: A generative artificial intelligence chatbot developed by xAI, based on a large language model.
- LlaMA 2: A state-of-the-art large language model for coding.
- Stable Diffusion: A deep learning, text-to-image model released in 2022 based on diffusion techniques.

### Example

- [Prompt](https://github.com/ora-io/OAO/blob/main/contracts/Prompt.sol): A simple smart contract that uses OAO for LLM responses.
- [SimplePrompt](https://github.com/ora-io/OAO/blob/main/contracts/SimplePrompt.sol): A simpler, event-only and gas-efficient smart contract that uses OAO for LLM responses.

### General

- [Humm Protocol](https://twitter.com/hummprotocol): An AI-based protocol for AI ownership and monetization.
- [AI Intent Engine](https://github.com/LiRiu/oaoie): An intent engine with OAO, leveraging onchain LlaMA2 to solve user intent in natural language into onchain actions (send, and swap). Also a fork called [COCOA](https://github.com/ailuropodaWu/ethtaipei2024) for cross-chain usage [built during ETHTaipei](https://taikai.network/ethtaipei/hackathons/hackathon-2024/projects/clu4wseee0knky5017s517lk3/idea).
- [Grok vs Llama](https://github.com/socathie/grok-vs-llama): An Onchain AI vs Onchain AI project. In this project, LlaMA2 monitors whether Grok is in a Glitch state (related: [AI Mirror Test](https://twitter.com/joshwhiton/status/1770870738863415500)), and if so, the user who initiated the AI request is rewarded with a bounty for finding Grok's "weakness". [Built during ETHTaipei](https://taikai.network/ethtaipei/hackathons/hackathon-2024/projects/clu3sufsj0imuw201g0peq4s1/idea).

### DeFi

- [AI NFT Bot](https://github.com/cong2480/AI_NFT_bot): A pricing engine for NFT assited with onchain AI. [Built during ETHDenver](https://devpost.com/software/llm-assisted-valuation-based-nft-trading-bot).

### AIGC-NFT

- [7007](https://twitter.com/lab7007): An ERC-7007 based platform offering on-chain AIGC generation services and monetizing of AI Models.
- [Onchain AI NFT](https://github.com/varun-doshi/Onchain-AI-NFT): An onchain AI NFT project utilizing AI Oracle's Stable Diffusion to generate image NFT directly onchain. Complete tutorial [here](https://medium.com/@varun-doshi/bring-ai-on-chain-with-ora-protocol-b7a034d24182).
- [OAOLimerick](https://github.com/Tokenseller-Leezi/OAOLimerick): A onchain AI Limerick NFT using AI Oracle's LlaMA2 for generating poet NFT directly onchain.
- [Graviola NFT](https://github.com/el-tumero/graviola): An onchain NFT collection with minimalistic portraits of fictional characters. [Built during ETHDenver](https://devpost.com/software/awdawdawdw).
- [ABC-ORA](https://github.com/Gathin23/abc-ora): An ERC-7007 based AIGC music NFT project, using AI Oracle's LLM to generate music notes and mint the piece into NFT. [Built during ETHTaipei](https://devpost.com/software/abc-ora).
- [PS 6](https://github.com/flyinglimao/ETHTaipei2024): An AI-generated story NFT protocol. [Built during ETHTaipei](https://taikai.network/ethtaipei/hackathons/hackathon-2024/projects/clu2t3rkl0hsuwc016f2dzes3/idea).

### Security

- [InsORAnce](https://github.com/ethTaipei2024/insORAnce): An insurance protocol for DeFi that utilizes AI Oracle for evaluating insurance rules and conditions, and zkAutomation for automated hacking detection. [Build during ETHTaipei](https://taikai.network/ethtaipei/hackathons/hackathon-2024/projects/clu3x7hrz0ioyw201x5jhtvkq/idea).
- [AGI (Artificial Guarding Intelligence)](https://github.com/LiRiu/OAOPause): A prototype of circuit breaker for smart contract based on AI-powered simulation of protocol security. [Build during ETHTaipei](https://taikai.network/ethtaipei/hackathons/hackathon-2024/projects/clu4sf7s30k0cwc019pwduzgj/idea).

### Infrastructure

- [gonnx](https://github.com/alan890104/mlgo): A framework for converting ONNX to MLGO for better opML developer experience and AI Oracle model integration. [Build during ETHTaipei](https://taikai.network/ethtaipei/hackathons/hackathon-2024/projects/clu4iw0yc0jnawc01egwdglx8/idea).

## 🔮 ZK Oracle CLE Ecosystem

_A List of CLEs Built on ZK Oracle._

### General

- [CLE Examples](https://github.com/ora-io/cle/tree/main/templates): A list of CLEs, including Uniswap Price Calculation, zkAutomation-based CLE, and multi-address based CLE. This is the implementation by ORA.
- [zkUsecases](https://github.com/LiRiu/zkUsecases/tree/norman/example): A list of CLEs, including SeaPort Trading Activity, and USDT Transfer Volume Per Block.
- [zkAMM](https://github.com/Defi-3/zkAMM-contracts): A zkOracle-based automated market maker that is fully scalable with unlimited computation resources.
- [dETF](https://github.com/Defi-3/dETF-Contract): A zkOracle-based fully onchain and decentralized ETF protocol.
- [Unic](https://twitter.com/viaprize/status/1711312453219524638): A decentralized identity platform, using zkOracle for onchain ML.
- [ZKredible](https://twitter.com/viaprize/status/1711312450405159377): A privacy-preserving and censorship-resistant credit record evaluation system, using zkOracle for onchain aggregation of zkML.
- [zkKYC](https://github.com/ora-io/zkKYC-story-hackathon): A zkOracle-based hook that brings offchain kyc data to onchain Story Protocol. This project was [developed during Story Protocol Alpha Hackathon and won second place](https://twitter.com/StoryProtocol/status/1734259414591512932).

### DeFi & DEX & MEV

- [Marine](https://github.com/ora-io/marine): A CLE as liquidation protocol on Compound Protocol. This is tracking 15+ addresses, and 90+ events at the same time.
- [zkToken](https://github.com/ora-io/zkToken): A CLE as ERC-20 token monitor. This monitors whether there is any selling or pumping behavior in the whale account, and then issue an alert signal.
- [Dex Vigil](https://github.com/issa-me-sush/dex-vigil-zkgraph): A CLE that detects anomalous trading behavior and possibly prevent exploits.
- [Cross-chain Asset Transfer](https://github.com/issa-me-sush/cross-chain-asset-transfer): An example CLE implementation of cross-chain asset / token / credit transfer system.
- [MEV Detection](https://github.com/guha-rahul/Proof-of-Sandwiched): A PoC CLE that proves a user's behavior such as `Swap` has been harmed by an MEV bot.
- [BTC 2 ETH](https://github.com/Mingzhe-W/zkgraph/tree/main/Btc2EthConversionRate): A CLE that calculates for BTC to ETH conversion rate.
- [zkInsurance](https://github.com/Mingzhe-W/zkgraph/tree/main/zkInsurrance): A CLE that auto-generates proofs for claiming insurance.
- [zkSafeMixer](https://github.com/YolaYing/ZK-Tornado-Cash): A CLE that warns downstream contracts if there's blacklisted address's fund in the mixer.
- [Kubera](https://github.com/Kubera-ETHTaipei): A CLE that implements verifiable on-chain credit score system. [Built during ETHTaipei](https://taikai.network/ethtaipei/hackathons/hackathon-2024/projects/clu4lm9k60kbcy501rxfdylu4/idea).

### Onchain API Oracle

- [Onchain Price Oracle](https://github.com/YolaYing/Onchain-Price-Oracle): A CLE that implements TWAP oracle.

### NFT

- [BAYC Hacked](https://github.com/arjanjohan/zkgraph-hacked-bayc): A CLE that tracks hacked BAYC by transfer event.
- [Free Mints](https://github.com/arjanjohan/zkgraph-track-free-mints): A CLE that monitors free mints of NFT.
- [Proof of OG of Azuki NFT](https://github.com/guha-rahul/Proof-of-OG-of-Azuki-NFT): A CLE that proves the OG mint of Azuki NFT.
- [Proof of Mint](https://github.com/Gathin23/Proof-of-Mint-zkgraph): A CLE that tracks all the address that has minted DOP token on sepolia.

### Game

- [ZKLife](https://github.com/YolaYing/ZKLife/tree/main?tab=readme-ov-file): A [full game](https://devfolio.co/projects/zklifezkenhanced-onchain-ai-gaming-d74f) that implements Conway's Game of Life with multiplayer mode and gaming AI.
- [Game Of Life](https://github.com/Mingzhe-W/gameOfLife): A game that implements Conway's Game of Life with game logic computed in zkOracle.

### Proof of X

- [Proof of Pool](https://github.com/agxmbhir/proof-of-pool): A CLE that tracks newly created Uniswap v3 pools.
- [Proof of Bridge](https://github.com/agxmbhir/proof-of-bridge): A PoC of cross-chain bridge uses a CLE to bridge tokens from sepolia to goerli with zkp.
- [Proof of Whale](https://github.com/Thirumurugan7/Proof-Of-Whale): A CLE that verifies if a wallet is a big player even if your funds or assets are compromised, as the whale status is confirmed by the address that initiated the event, not the recipient.
- [Proof of Blacklist](https://github.com/varun-doshi/Proof-of-Blacklist-zkGraph): A CLE for tracking new blacklisted address of USDT.
- [Proof of Ownership](https://github.com/varun-doshi/Proof-of-Ownership-zkGraph): A CLE that accesses historical ownership change of the Azuki NFT collection.
- [Proof Of Membership](https://github.com/HAPPYS1NGH/dd-member-zkgraph): A CLE that proves an address is a member of Developer DAO.
- [Proof of Approved by rupam-04](https://github.com/rupam-04/proof-of-approved): A CLE that accesses historical approved amount of token.
- [Proof of Approved by udhaykumarbala](https://github.com/udhaykumarbala/proof-of-approval): A CLE that accesses historical approved amount of token.
- [Proof of Whale](https://github.com/Thirumurugan7/Proof-Of-Whale): A CLE that checks for a special "isWhale" event.
- [Proof of New Player](https://github.com/Thirumurugan7/Proof-of-new-player): A CLE that checks for "NewPlayer" event.

### Libraries & Utils

- [zkGraph String Utils](https://github.com/udhaykumarbala/zkgraph-stringutils): A CLE that helps offload the string operation to offchain and gives the mechanism to prove the offline calculated values.
- [zkGraph Math Utils](https://github.com/Gathin23/Math-zkgraph): A CLE that helps offload Math operations offchain and gives the mechanism to prove the offline calculated values.

### Security

- [Secure Watcher](https://github.com/HAPPYS1NGH/secure-watcher-zkgraph): A CLE that watches for activities which are similar to compromise of Private Key.

### Others

- [Decentralized Moderation](https://github.com/issa-me-sush/decentralized-content-moderation): Content moderation system based on CLE for a decentralized social network or any kind of customized DAO or decentralized network/ecosystem.

## 💡 Project Ideas

_Ideas to Build with AI Oracle or zkOracle._

### AI Oracle Ideas

| Idea                                  | Model in ORA OAO (+ Other Tech Stack)                                |
|---------------------------------------|----------------------------------------------------------------------|
| Predictor and Analyzer                | Any                                                                  |
| Asset Pricing                         | Financial Models                                                     |
| Simulation                            | LLM or Application-Specific Models                                   |
| Credit/Risk Analyzer                  | LLM or Financial Models                                              |
| Sentiment Analysis                    | LLM or Application-Specific Models                                   |
| Judge of Anything based on Rules*     | LLM                                                                  |
| Trading Bot Wif MEV                   | Financial Models (+ Flashbots SUAVE stack)                           |
| Aggregator                            | Financial Models                                                     |
| "Point Guard"                         | Financial Models                                                     |
| Copy-trading                          | Financial Models                                                     |
| AIGC-NFT (Pure, Loot-style, Remixing) | Text2Image or Text2Video Models (+ Prompt Engineering / Fine-tuning) |
| AI as Game Moderator                  | LLM or Application-Specific Models                                   |
| AI as Governor                        | LLM or Application-Specific Models                                   |
| AI as NPC                             | LLM or Application-Specific Models                                   |
| AI as Opponent                        | LLM or Application-Specific Models                                   |
| AI as Counterparty                    | LLM or Application-Specific Models                                   |
| Agent for Whale's Governance          | LLM or Application-Specific Models                                   |
| Content Moderator                     | LLM                                                                  |
| Code Generator                        | LLM                                                                  |
| Security Gadget                       | LLM or Application-Specific Models                                   |
| Bring Your Own Model                  | / (+ Use opML to Integrate New Models into OAO)                      |
| Rebuild Everything                    | Any (+ Rebuild All Protocols with AI)                                |

Read more from ORA's idea posts on AI Oracle: [1](https://mirror.xyz/orablog.eth/WhcZyqKeFjcvkKskedBbv8Jrzt5WEmL5JYuUte3NO3w).

*: Based on [InsORAnce](https://github.com/ethTaipei2024/insORAnce) idea, LLM can be a judge / verifier of anything. In InsORAnce, LLM judges if insurance should be payed out based on a protocol's hack (truth) and given rules defining a hack (pre-made template / rule). Actually, the truth and pre-made rule can also be: any onchain events (og wallet moves ETH), and even offchain event. So that the InsORAnce idea can be expanded to insurance for anything onchain + offchain.

### zkOracle Ideas

| Idea                                       | Value of ORA                                                   | Difficulty | Additional Note                                                                                                                                          |
|--------------------------------------------|-------------------------------------------------------------------------|-------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Dashboard for NFT Marketplaces             | Access Historical Trading Data of Blur, Looksrare, CryptoPunks, Memswap | 💥          |                                                                                                                                                          |
| Onchain DefiLlama                          | Access Historical Data of AAVE, Compound, Morpho                        | 💥          | Performs calculations on protocol inflow and outflow, TVL, protocol revenue, protocol health ratio, protocol yield for user.                             |
| Onchain L2BEAT                             | Access Historical Data of L2's contract on L1, and Trustless Compute    | 💥          | Calculate TVL (Canonical, External, Native) of L2; Calculate TPS (via L2 blocks settled on L1) of L2.                                                    |
| CLEs for ERCs                              | Access Historical Data of Standardized ERCs, and Trustless Compute      | 🔥          | Build CLEs for standards such as ERC-20 (maybe also weird ERC-20s) and ERC-721.                                                                          |
| Onchain Price Oracle                       | Trustless Compute of Pricing                                            | 💥          | Build price oracles like TWMP (time-weighted median price), or even something like [UTXOracle](https://utxo.live/oracle/).                               |
| CLEs as Public Goods Libraries             | Trustless Compute of Algorithms                                         | 💥          | Build libraries such as [onchain](https://github.com/emo-eth/onchain) with CLE.                                                                          |
| Traditional Oracle Services                | Trustless Compute, and Automation                                       | 🌋          | Build VRF (Verifiable Random Function), VDF (Verifiable Delay Functions), FSS (Fair Sequencing Service).                                                 |
| Automation Apps                            | Trustless Compute, and Automation                                       | 🔥          | Implement auto-renewal of ENS, automated strategies, onchain liquidator keepers for DeFi protocols...                                                    |
| DeFi Protocols Remastered                  | Trustless Compute of DeFi Logic, and Automation                         | 🌋          | Use CLEs to reimplement protocols like AAVE, Curve, Uniswap v3, or v4.                                                                                   |
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

Read more from ORA's idea posts on zkOracle: [1](https://mirror.xyz/hyperoracleblog.eth/Tik3nBI9mw05Ql_aHKZqm4hNxfxaEQdDAKn7JKcx0xQ), [2](https://mirror.xyz/hyperoracleblog.eth/AG3tFPgesKw4d0VnwPIYjjoOzVSoc3R4chKcyY4s0ks).

## 🔧 Other Contribution by ORA

_ORA's Contribution to General Web3, Blockchain, and Crypto Space._

### Researches & Development

- [zkML: keras2circom](https://github.com/ora-io/keras2circom)
- [opML: Optimistic Machine Learning](https://arxiv.org/abs/2401.17555)
- [opp/ai: Optimistic Privacy-Preserving AI on Blockchain](https://arxiv.org/abs/2402.15006)
- [IMO: Initial Model Offering](https://mirror.xyz/orablog.eth/xYMD27tN23ppbKCluB9faytF_W6M1hKXTuKcfkm3D50)

### World Supercomputer

- [Litepaper as Co-initiator](https://review.stanfordblockchain.xyz/p/towards-world-supercomputer)
- [WSC Summit 2023](https://hackmd.io/@EEEZ5333/World-Supercomputer-Summit-2023-Recap)
- [WSC Community Day @Token2049](https://hackmd.io/@EEEZ5333/World-Supercomputer-Token2049-Recap)

## Improvement Proposals

- [Ethereum/ERC-6150](https://eips.ethereum.org/EIPS/eip-6150)
- [Ethereum/ERC-7007](https://eips.ethereum.org/EIPS/eip-7007), and ecosystem ([ZenetikNFT](https://ethglobal.com/showcase/zenetiknft-1ph5r) and [AIME](https://taikai.network/ethtaipei/hackathons/hackathon-2024/projects/clu46p1ai0j1owc01k3ivvjm4/idea))
- [Celestia/CIP-5](https://github.com/celestiaorg/CIPs/blob/main/cips/cip-5.md)

### Open Source Libraries

- [create-cle](https://www.npmjs.com/package/create-cle)
- [cle-api](https://www.npmjs.com/package/@ora-io/cle-api)
- [cle-lib](https://www.npmjs.com/package/@ora-io/cle-lib)
- [cle-cli](https://www.npmjs.com/package/@ora-io/cle-cli)

### Open Grant Contribution

- [Ethereum Foundation KZG Ceremony Grant](https://blog.ethereum.org/2022/12/15/kzg-ceremony-grants-round)/[Halo2-based KZG Ceremony Client](https://mirror.xyz/hyperoracleblog.eth/vPwYqWWmsWW5JPqlOjk9fMo7Ba72D40Ph9SyjthEZDE)
- [Compound Grant](https://www.comp.xyz/t/compound-grants-program-lessons-and-next-steps/2264)/[Marine](https://github.com/hyperoracle/Marine)

# ⃝ Awesome ORA

## 🌍 Overview
ORA is Ethereum's Trustless AI that enables AI on the blockchain.

This list focuses on the work related to the ORA ecosystem.

This includes the [AI Oracle (OAO, Onchain AI Oracle)](https://mirror.xyz/orablog.eth/qLBIR_yxmpFJ4dg5p5Sn8Wz46aQDTG1jCW8myeE7zZ8) ecosystem, the ERC ecosystem co-authored by ORA, ZK Oracle ecosystem and other ORA contributions.

## 🤖 AI Oracle Ecosystem

_A Collection of Projects Built on Onchain AI Oracle (OAO)._

### Models

- LlaMA 3: A state-of-the-art large language model for coding.
- Stable Diffusion: A deep learning, text-to-image model released in 2022 based on diffusion techniques.
- OpenLM: A performative language modeling (LM) repository, aimed to facilitate research on medium sized LMs.
- OpenLM Chat and Score: Fine-tuned models based on OpenLM.
- ~Grok: A generative artificial intelligence chatbot developed by xAI, based on a large language model.~

### Examples

- [Prompt](https://github.com/ora-io/OAO/blob/main/contracts/Prompt.sol): A simple smart contract that uses OAO for LLM responses.
- [SimplePrompt](https://github.com/ora-io/OAO/blob/main/contracts/SimplePrompt.sol): A simpler, event-only and gas-efficient smart contract that uses OAO for LLM responses.

### Tutorials

- [Interaction with OAO](https://docs.ora.io/doc/oao-onchain-ai-oracle/develop-guide/tutorials/interaction-with-oao-tutorial): Build AI DApp powered by OAO. See also video tutorial [here](https://www.youtube.com/watch?v=8fcJbeKN1uM).
- [Integration with OAO](https://docs.ora.io/doc/oao-onchain-ai-oracle/develop-guide/tutorials/integration-into-oao-tutorial): Integrate your AI model into opML and OAO.

### Dashboard
- [ORA OAO Dashboard by ORA](https://dune.com/ora_io/oao): A Dune dashboard for OAO request number by chain, OAO revenue, OAO callback gas, OAO request number by model.
- [ORA Staking Dashboard by Hashed](https://dune.com/hashed_official/ora): A Dune dashboard for ORA Staking stats.
- [ORA Staking Number of Unique Stakers query](https://dune.com/queries/4112681/6924085): A Dune query for number of unique ORA Staking users.

### General

- [ChatOLM](https://chatolm.com/): A decentralized, onchain, censorship-resistant, verifiable, and permissionless AI chatbot powered by onchain AI.
- [Humm Protocol](https://twitter.com/hummprotocol): An AI-based protocol for AI ownership and monetization.
- [AI Intent Engine](https://github.com/LiRiu/oaoie): An intent engine with OAO, leveraging onchain LlaMA2 to solve user intent in natural language into onchain actions (send, and swap). Also a fork called [COCOA](https://github.com/ailuropodaWu/ethtaipei2024) for cross-chain usage [built during ETHTaipei](https://taikai.network/ethtaipei/hackathons/hackathon-2024/projects/clu4wseee0knky5017s517lk3/idea).
- [Grok vs Llama](https://github.com/socathie/grok-vs-llama): An Onchain AI vs Onchain AI project. In this project, LlaMA2 monitors whether Grok is in a Glitch state (related: [AI Mirror Test](https://twitter.com/joshwhiton/status/1770870738863415500)), and if so, the user who initiated the AI request is rewarded with a bounty for finding Grok's "weakness". [Built during ETHTaipei](https://taikai.network/ethtaipei/hackathons/hackathon-2024/projects/clu3sufsj0imuw201g0peq4s1/idea).
- [OAOFrame](https://github.com/liriu/OAOFrame): A Farcaster Frame with fortune-telling powered by Onchain AI.

### DeFi

- [Lending Zone](https://taikai.network/ethbelgrade/hackathons/eth-belgrade-hackathon-2024/projects/clwx0zyac0481y101y13fssjg/idea): A protocol for borrowing with NFTs as collateral and earning yield by lending assets, powered by AI valuations of NFTs.
- [AI NFT Bot](https://github.com/cong2480/AI_NFT_bot): A pricing engine for NFT assisted with onchain AI. [Built during ETHDenver](https://devpost.com/software/llm-assisted-valuation-based-nft-trading-bot).

### AIGC-NFT

- [7007](https://twitter.com/lab7007): An ERC-7007 based platform offering on-chain AIGC generation services and monetizing of AI Models.
- [Onchain AI NFT](https://github.com/varun-doshi/Onchain-AI-NFT): An onchain AI NFT project utilizing AI Oracle's Stable Diffusion to generate image NFT directly onchain. Complete tutorial [here](https://medium.com/@varun-doshi/bring-ai-on-chain-with-ora-protocol-b7a034d24182).
- [OAOLimerick](https://github.com/Tokenseller-Leezi/OAOLimerick): An onchain AI Limerick NFT using AI Oracle's LlaMA2 for generating poet NFT directly onchain.
- [Graviola NFT](https://github.com/el-tumero/graviola): An onchain NFT collection with minimalistic portraits of fictional characters. [Built during ETHDenver](https://devpost.com/software/awdawdawdw).
- [ABC-ORA](https://github.com/Gathin23/abc-ora): An ERC-7007 based AIGC music NFT project, using AI Oracle's LLM to generate music notes and mint the piece into NFT. [Built during ETHTaipei](https://devpost.com/software/abc-ora).
- [PS 6](https://github.com/flyinglimao/ETHTaipei2024): An AI-generated story NFT protocol. [Built during ETHTaipei](https://taikai.network/ethtaipei/hackathons/hackathon-2024/projects/clu2t3rkl0hsuwc016f2dzes3/idea).

### Security

- [InsORAnce](https://github.com/ethTaipei2024/insORAnce): An insurance protocol for DeFi that utilizes AI Oracle for evaluating insurance rules and conditions, and zkAutomation for automated hacking detection. [Build during ETHTaipei](https://taikai.network/ethtaipei/hackathons/hackathon-2024/projects/clu3x7hrz0ioyw201x5jhtvkq/idea).
- [AGI (Artificial Guarding Intelligence)](https://github.com/LiRiu/OAOPause): A prototype of circuit breaker for smart contract based on AI-powered simulation of protocol security. [Build during ETHTaipei](https://taikai.network/ethtaipei/hackathons/hackathon-2024/projects/clu4sf7s30k0cwc019pwduzgj/idea).

### Infrastructure

- [gonnx](https://github.com/alan890104/mlgo): A framework for converting ONNX to MLGO for better opML developer experience and AI Oracle model integration. [Build during ETHTaipei](https://taikai.network/ethtaipei/hackathons/hackathon-2024/projects/clu4iw0yc0jnawc01egwdglx8/idea).


## 💡 Project Ideas

_Ideas to Build with AI Oracle or zkOracle._

### ai/fi Ideas

ai/fi = AI + DeFi.

ai/fi is the fusion of AI (verifiable AI inference provided by Onchain AI Oracle) and DeFi.

The strategy to transform DeFi into ai/fi is simple: "identify the computationally intensive part of any DeFi protocol and replace it with AI."

| Idea          | Implementation                           | Existing DeFi Protocols to Add AI |
|---------------|------------------------------------------|-----------------------------------|
| AI Aggregator | Aggregation with Best Swap Rate with AI  | 1inch, Paraswap                   |
| AI AMM (0)    | Dynamic Market Making Curves with AI     | Uniswap v3                        |
| AI AMM (1)    | CowSwap, but with AI as Order Filler     | Uniswap v3                        |
| AI Yield      | Yield Optimization with AI               | Convex, Yearn                     |
| AI Lending    | Lending of Any Asset with AI             | Aave, Compound                    |
| AI Stablecoin | Stablecoin backed by Arbitrary Asset     | MakerDAO                          |
| AI Governance*| AI Proposal Initiation, Review, Explainer| Any Protocol with Governance      |
| AI DAO        | AI-based DAO Management and Enforcement  | Any Protocol with DAO             |
| ...           |                                          |                                   |

Read more from ai/fi idea posts: [1](https://mirror.xyz/orablog.eth/cYDQZHGGRHJEZ8_3Ju9D7lIgjjweQmO8u_C-ueYMFhU), [2](https://mirror.xyz/orablog.eth/tHHeXtvl__w8qJiYo6Uu0Iac964Wm0hoVfiL-VDf-Nw).

*: See [recursive_llm_organization](https://github.com/marcgraczyk/recursive_llm_organization).

### AI Oracle Ideas

| Idea                                        | Model in ORA OAO (+ Other Tech Stack)                                |
|---------------------------------------------|----------------------------------------------------------------------|
| [System Prompt](https://github.com/LouisShark/chatgpt_system_prompt) Powered AI Model           | Any              |
| Chat / GPTs with OAO                        | LLM                                                                  |
| Specific Agents (Fortune Teller, AI GF...)  | LLM                                                                  |
| "Community Notes" with Onchain AI           | LLM                                                                  |
| Predictor and Analyzer                      | Any                                                                  |
| Asset Pricing                               | Financial Models                                                     |
| Simulation                                  | LLM or Application-Specific Models                                   |
| Credit/Risk Analyzer                        | LLM or Financial Models                                              |
| Sentiment Analysis                          | LLM or Application-Specific Models                                   |
| Judge of Anything based on Rules*           | LLM                                                                  |
| Trading Bot Wif MEV                         | Financial Models (+ Flashbots SUAVE stack)                           |
| Aggregator                                  | Financial Models                                                     |
| "Point Guard"                               | Financial Models                                                     |
| Copy-trading                                | Financial Models                                                     |
| AIGC-NFT (Pure, Loot-style, Remixing)       | Text2Image or Text2Video Models (+ Prompt Engineering / Fine-tuning) |
| AI as Game Moderator                        | LLM or Application-Specific Models                                   |
| AI as Governor                              | LLM or Application-Specific Models                                   |
| AI as NPC                                   | LLM or Application-Specific Models                                   |
| AI as Opponent                              | LLM or Application-Specific Models                                   |
| AI as Counterparty                          | LLM or Application-Specific Models                                   |
| Agent for Whale's Governance                | LLM or Application-Specific Models                                   |
| Content Moderator                           | LLM                                                                  |
| Code Generator                              | LLM                                                                  |
| Security Gadget                             | LLM or Application-Specific Models                                   |
| Bring Your Own Model                        | / (+ Use opML to Integrate New Models into OAO)                      |
| Rebuild Everything                          | Any (+ Rebuild All Protocols with AI)                                |

Read more from ORA's idea posts on AI Oracle: [1](https://mirror.xyz/orablog.eth/WhcZyqKeFjcvkKskedBbv8Jrzt5WEmL5JYuUte3NO3w).

*: Based on [InsORAnce](https://github.com/ethTaipei2024/insORAnce) idea, LLM can be a judge / verifier of anything. In InsORAnce, LLM judges if insurance should be paid out based on a protocol's hack (truth) and given rules defining a hack (pre-made template / rule). Actually, the truth and pre-made rule can also be: any onchain events (og wallet moves ETH), and even offchain event. So that the InsORAnce idea can be expanded to insurance for anything onchain + offchain.

### Infra Ideas

| Infra Ideas        | Details                                                                                         |
|--------------------|-------------------------------------------------------------------------------------------------|
| Paymaster for OAO  | OAO fees are in $ETH. A paymaster can enable users to pay with $USDT to improve OAO's adoption. |
| Dashboard for OAO  | Data analysis or "mempool" dashboard* for OAO.                                                  |
| Interop for OAO    | Explore how OAO result from chain A can be used in chain B.                                     |
| Optimized OAO      | Optimize OAO contract with Assembly, or other novel smart contract languages.                   |
| Fast Finalized OAO | Explore how DApp with OAO's optimistic mechanism can be finalized faster with architecture like [this](https://ethresear.ch/t/why-wait-a-week-fast-finality-optimistic-rollups/18868) |
| Scaffold-OAO       | Adapt Scaffold-Eth for OAO, so that devs can one-click initialize OAO AI DApp.                  |

*: Existing [data analysis dashboard for OAO by Gathin](https://dune.com/gathin/oao). Mempool dashboard can be similar to [Ethernow](https://www.ethernow.xyz/mempool/all), but only showing OAO-related transactions.

## ERC Ecosystem co-authored by ORA
### ERC-7007
ERC-7007 is Verifiable AI-Generated Content Token, co-authored by [@ORAProtocol](https://x.com/OraProtocol) team.

- An ERC-721 extension that enables verifiable AI-generated content tokens using Zero-Knowledge (zkML) and Optimistic (opML) Machine Learning techniques.


For more details check official [EIP post](https://eips.ethereum.org/EIPS/eip-7007).

---

### ERC-7641
ERC-7641 is Intrinsic RevShare Token, authored by [@ORAProtocol](https://x.com/OraProtocol) team.

- An ERC-20 extension that integrates a revenue-sharing mechanism, ensuring tokens intrinsically represent a share of a communal revenue pool.

For more details check official [EIP post](https://ethereum-magicians.org/t/erc-intrinsic-revshare-token/18999).

---

### ERC-6150
ERC-6150 is a standard for Hierarchical NFTs, co-authored by [@ORAProtocol](https://x.com/OraProtocol) team.

- An ERC-721 extension for multi-layer filesystem-like hierarchical NFTs.

For more details check official [EIP post](https://eips.ethereum.org/EIPS/eip-6150).

## 🤖 ZK Oracle Ecosystem
For info about zk oracle ecosystem read [zk-oracle](./zk-oracle/zk-oracle.md) page. 

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

### Open Grant Contribution

- [Ethereum Foundation KZG Ceremony Grant](https://blog.ethereum.org/2022/12/15/kzg-ceremony-grants-round)/[Halo2-based KZG Ceremony Client](https://mirror.xyz/hyperoracleblog.eth/vPwYqWWmsWW5JPqlOjk9fMo7Ba72D40Ph9SyjthEZDE)
- [Compound Grant](https://www.comp.xyz/t/compound-grants-program-lessons-and-next-steps/2264)/[Marine](https://github.com/hyperoracle/Marine)

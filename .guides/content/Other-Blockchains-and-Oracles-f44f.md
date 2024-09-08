# BTF-05 \- Other Blockchains and Oracles

## Learning Objectives

LO1: Define layer 2s and other blockchains  
LO2: Describe oracle concepts and their importance in connecting blockchains and the world’s data sources  
LO3: Define interoperability  
LO4: Summarize use cases for blockchain, oracles, and interoperability

# Layer 2s and Other Blockchains

## EVM Compatibility

EVM, or Ethereum Virtual Machine, compatibility refers to the ability of a blockchain network to support the same tools, languages, and standards as Ethereum, allowing it to run [smart contracts](https://chain.link/education/smart-contracts) and decentralized applications (dApps) designed for Ethereum. EVM compatibility is a critical feature for many developers, allowing them to leverage their existing knowledge and tools to build on these networks. 

## Layer 2s and Side Chains

The Ethereum network has powerful security features. However, the security and permanence of the Ethereum network comes with tradeoffs in speed, transaction throughput, and scalability. These constraints can limit the development potential of decentralized applications and impact the end-user experience.  

To solve these challenges, alongside EVM compatibility, several scaling solutions have emerged to offer enhanced speed and lower cost on the Ethereum blockchain. 

### Layer 2s

In the Ethereum context, a [Layer-2](https://chain.link/education-hub/what-is-layer-2) (L2) solution is another framework or protocol built on top of the Ethereum blockchain (Layer-1) to improve its scalability, efficiency, and speed. It is not a separate blockchain in the traditional sense.

Layer-2 solutions handle transactions outside the main Ethereum chain (Layer-1) but still rely on Ethereum's security and decentralization. They are designed to work directly with the Ethereum blockchain and are not independent blockchains with their own consensus mechanisms.

Examples include State Channels and Rollups.

### State Channels

State channels allow users to perform multiple offchain transactions while only recording the final state on the Ethereum blockchain. This approach reduces the need for numerous onchain transactions.

State Channels examples:[Celer Network](https://celer.network/), [Raiden Network](https://raiden.network/)

### Layer-2 Rollups

Layer-2 rollups are of two types: 

* Optimistic rollups  
* ZK-Rollups 

Both are “true layer-2 solutions," meaning they can execute a large volume of transactions at high speeds and low costs while verifying this bundle of transactions on layer-1. 

With Optimistic rollups, we “optimistically assume” that transactions executed on the rollup are authentic and accurate. Unless challenged as fraudulent, these transactions get “rolled up” and submitted to layer-1. These rollups are “optimistic” because these bundles of transactions are considered “innocent until proven guilty.” Fraudulent transactions must be established by fraud proofs that challenge the validity of the transactions. Such a challenge must be submitted within seven days of the transaction. 

Optimistic Rollups examples: [Arbitrum](https://arbitrum.io/), [Base](https://www.base.org/), [Celo](https://celo.org/), [Optimism](https://www.optimism.io/)

ZK-Rollups uses [zero-knowledge proofs](https://chain.link/education/zero-knowledge-proof-zkp) to bundle transactions and submit a proof of validity to Ethereum, ensuring scalability and security.

ZK-Rollups examples: [Loopring](https://loopring.org/), [zkSync](https://zksync.io/)

### Side Chains

Side chains are blockchains that run parallel to Ethereum. They have their own consensus mechanisms and security models and are connected to Ethereum via bridges.

Side chains examples: [Gnosis](https://www.gnosis.io/), [Polygon](https://polygon.technology/)

### Other Options

Plasma chains are smaller blockchains that run alongside the Ethereum mainnet. They allow for offchain transactions and periodic summary submission to the mainnet. 

Validium is similar to [ZK-Rollups](https://chain.link/education-hub/zero-knowledge-rollup), using zero-knowledge proofs for transaction validation. However, it stores the data offchain, which can lead to greater scalability at the cost of decentralization.

## Blockchains EVM Compatible

Here’s a list of some popular EVM-compatible blockchains:

* [Binance Smart Chain (BSC)](https://www.bnbchain.org/)  
* [Fantom](https://fantom.foundation/)  
* [Moonbeam](https://moonbeam.network/)

## Overview of Other Popular Blockchains Besides Ethereum

Here’s a list of some popular blockchains besides Ethereum:

* [Avalanche](https://www.avax.network/)  
* [Polkadot](https://polkadot.com/)  
* [Solana](https://solana.com/)

# Oracle Concepts and Its Importance in Connecting Blockchains With Each Other and the World

## Oracles Concepts and Their Importance in Smart Contracts

[Oracles](https://chain.link/education/blockchain-oracles) are services that provide external data to blockchain-based smart contracts, enabling them to interact with information outside the blockchain.

Since blockchains, by design, cannot access offchain data, smart contracts are limited in their application, particularly in areas that require real-time or external information. Oracles solve this issue as middleware, facilitating secure and reliable communication between onchain and offchain environments. 

## Chainlink Services: Different Types of Oracles and Their Purpose

However, integrating oracles introduces security, reliability, and decentralization challenges. Chainlink, a leading solution in this space, addresses these challenges through decentralized oracle networks (DONs) that ensure data integrity and reliability by employing open-source technology, cryptography, decentralization, data signing, and reputation systems. The effective implementation of oracles is vital for enabling smart contracts to interact with the external world without losing the underlying security guarantees of the blockchain they run on. This unlocks their full potential across various industries. 

Chainlink provides numerous oracle services, such as: 

1. [Cross-Chain Interoperability Protocol (CCIP)](https://docs.chain.link/ccip): A Global standard for building secure cross-chain decentralized applications.  
2. [Data Feeds](https://docs.chain.link/data-feeds): Decentralized and high-quality data for DeFi, sports, weather, and more can be consumed in smart contracts onchain.  
3. [Data Streams](https://docs.chain.link/data-streams): Secure and reliable high-frequency, low-latency market data for ultra-fast derivatives products that can be consumed offchain and cryptographically verified onchain.  
4. [Functions](https://docs.chain.link/chainlink-functions): “Serverless” developer platform that can fetch data from any API and run custom, user-supplied code.  
5. [Automation](https://docs.chain.link/chainlink-automation): Reliable, high-performance, decentralized automation for smart contracts.  
6. [VRF](https://docs.chain.link/vrf): Verifiable, tamper-proof random number generator for blockchain gaming,NFTs, and more.

# 

# Interoperability

## Understanding the Concept of Interoperability Within the Blockchain Space

Blockchain interoperability standards are essential for the Web3 ecosystem and traditional systems that need to interact with different blockchains. These standards are the foundation for building blockchain abstraction layers, allowing traditional backends and dApps to interact with any blockchain network through a single middleware solution. Without blockchain interoperability standards, Web2 systems and dApps would need to build separate in-house implementations for each cross-chain interaction that they want to use, which is a time-consuming, resource-intensive, and complex process.

## Introducing CCIP: Chainlink Cross-Chain Interoperability Protocol

Chainlink CCIP is a blockchain interoperability protocol that enables developers to build secure applications that transfer tokens, messages (data), or both tokens and messages across chains using a standardized set of interfaces.

Given the inherent risks of cross-chain interoperability, CCIP features defense-in-depth security and is powered by Chainlink's industry-standard oracle networks. These networks have a proven track record of securing tens of billions of dollars and enabling over $15 trillion in onchain transaction value.

CCIP provides several key security benefits:

### Multiple Independent Nodes Run by Independent Key Holders

In CCIP, multiple nodes operate independently, each managed by separate key holders. Key holders are entities or individuals responsible for managing private keys that authorize transactions on the network. The independence of these critical holders is crucial because it prevents any single point of failure or centralized control, reducing the risk of collusion or malicious activity. CCIP ensures a more secure and decentralized network by distributing control across multiple independent parties.

### Separation of Responsibilities

There are distinct sets of node operators, and they don’t share responsibilities between the transactional DONs and the Risk Management Network.

Three separate decentralized oracle networks (DONs): 

1. Committing DON   
2. Executing DON for cross-chain transactions’ execution and validation  
3. RMN (Risk Management Network) is used for 2FA validation and executing and verifying every cross-chain transaction

### The Level-Five Interoperability Standard

CCIP provides Web3 projects with native [level-five cross-chain security](https://blog.chain.link/five-levels-cross-chain-security/) that can rapidly adapt to new risks or attacks in cross-chain messaging.

# Use Cases for Blockchain, Oracles, and Interoperability

## Blockchain Use Cases

Blockchain technology revolutionizes various industries by providing decentralized, transparent, and secure infrastructure. Below are several use cases of blockchain technology, highlighting its versatility and impact:

### Cryptocurrencies

**Bitcoin**: One of the original use cases of blockchain technology, allowing for decentralized digital currency transactions without intermediaries like banks.

**Altcoins**: Various other cryptocurrencies that offer alternative digital currency solutions, some with additional features like smart contracts (Ethereum).

### Decentralized Applications (dApps) 

Blockchain enables the creation of decentralized applications that operate without a central authority. In DeFi, dApps facilitate various financial services, including lending, borrowing, trading, and asset management. 

These applications benefit from blockchain’s security, transparency, and tamper-resistance, allowing users to interact directly with financial protocols without relying on traditional intermediaries.

### [Digital Identity](https://chain.link/education-hub/blockchain-identity)

**Self-Sovereign Identity**: Blockchains can give users control over their personal data, allowing them to manage and share their identity information securely. Projects like uPort and Sovrin focus on decentralized identity solutions.

**Verification and Authentication**: Blockchains can streamline the verification of credentials (e.g., academic degrees, certifications) and reduce fraud by providing a tamper-proof record of qualifications.

### [Decentralized Finance (DeFi)](https://chain.link/education/defi)

**Lending and Borrowing**: Platforms like Aave and Compound enable users to lend and borrow cryptocurrencies without intermediaries, using smart contracts to manage transactions.

**Decentralized Exchanges (DEXs)**: Platforms like Uniswap and SushiSwap allow users to trade cryptocurrencies directly with each other without a centralized exchange.

**Stablecoins**: Cryptocurrencies like USDT and USDC are pegged to fiat currencies and offer a stable value for transactions and savings in the DeFi ecosystem.

### Tokenization and Asset Management

Blockchains enables the [tokenization of real-world assets](https://chain.link/education/asset-tokenization) such as real estate, commodities, and intellectual property.   
These tokens can be traded, collateralized, or utilized within DeFi protocols, unlocking liquidity and enabling fractional ownership.   
It democratizes access to investment opportunities and creates new markets for traditionally illiquid assets.

### Supply Chain and Custody Management

Blockchain enables end-to-end supply chain visibility, allowing participants to track product origin, movement, and authenticity, providing transparency and traceability.   
Blockchains can be used to verify the authenticity of goods, particularly in industries like pharmaceuticals, luxury goods, and electronics.

This extends to custody management in the context of DeFi and digital assets, ensuring secure and transparent tracking of asset ownership and transfers.   
Blockchain is particularly valuable in logistics, manufacturing, and finance, where the secure and transparent movement of goods and assets is critical.

### Governance and DAOs

Blockchain enables decentralized governance through smart contracts, where stakeholders can participate in decision-making. [Decentralized Autonomous Organizations (DAOs)](https://blog.chain.link/daos/) exemplify this, allowing communities to govern projects, allocate resources, and vote on main issues without relying on centralized authorities. This decentralized governance model democratizes control and aligns stakeholders' interests with the project's success.

## Oracle Use Cases

Smart contract developers use oracles to build more advanced decentralized applications across broader blockchain use cases. While there are potentially infinite possibilities, the use cases with the most widespread adoption are below.

### Decentralized Finance (DeFi)

DeFi is a massive Blockchain use case, and a large portion of the DeFi ecosystem requires price oracles so that smart contracts can access financial data about assets and markets.   
Decentralized money markets use price oracles to determine users’ borrowing capacity and check if users’ positions are undercollateralized and subject to liquidation. Similarly, synthetic asset platforms use price oracles to peg the value of tokens to real-world assets, and [automated market makers (AMMs)](https://chain.link/education-hub/what-is-an-automated-market-maker-amm) use price oracles to help concentrate liquidity at the current market price to improve capital efficiency.

* **Price Feeds**: Oracles provide accurate and real-time price data for cryptocurrencies, fiat currencies, commodities, and other financial assets. This data is crucial for DeFi applications like lending platforms (e.g., Aave, Compound), decentralized exchanges (e.g., Uniswap, Sushiswap), and derivatives markets (e.g., Synthetix).  
* **Lending and Borrowing**: Oracles ensure that collateral is accurately valued in real-time, enabling platforms to calculate interest rates, trigger liquidations, and manage risk.  
* **Stablecoins**: For stablecoins like DAI, oracles provide the price data necessary to maintain the peg to a fiat currency, ensuring stability.

### Gaming and NFTs

Oracles also enable non-financial use cases for smart contracts, such as dynamic NFTs that can change in appearance, value, or distribution based on external events like the time of day or the weather. 

Additionally, compute oracles can generate verifiable random numbers for projects, which can be used to assign randomized traits to NFTs or select lucky winners in high-demand NFT drops. 

Onchain gaming applications also use verifiable randomness to create more engaging and unpredictable gameplay experiences, such as the appearance of random loot boxes or randomized matchmaking during a tournament.

### Insurance

[Insurance](https://blog.chain.link/blockchain-insurance/) smart contracts use input oracles to verify the occurrence of insurable events during claims processing, opening up access to physical sensors, web APIs, satellite imagery, and legal data. Output oracles can also provide insurance smart contracts with a way to make payouts on claims using other blockchains or traditional payment networks.

* [Parametric Insurance](https://blog.chain.link/parametric-insurance-smart-contract/): Oracles can trigger automatic payouts based on predefined conditions. For example, suppose a specific weather event occurs (e.g., rainfall above a certain level, such as hurricane landfall). In that case, the oracle provides this data to the smart contract, which then automatically pays out claims without needing a traditional process.  
* [Crop Insurance](https://chain.link/techtalks/arbol-parametric-insurance): Farmers can use blockchain-based insurance where oracles provide data on weather conditions, crop yields, or other factors. If the oracle reports a drought or flood, the insurance smart contract can automatically compensate the farmer.

### Enterprise

[Cross-chain](https://chain.link/education/cross-chain) oracles offer enterprises a secure blockchain middleware that allows them to connect their backend systems to any blockchain network. In doing so, [enterprise systems](https://blog.chain.link/chainlink-enterprise-blockchain-middleware/) can read/write to any blockchain and perform complex logic on deploying assets and data across chains and with counterparties using the same oracle network. Institutions can quickly join blockchains in high demand by their counterparties and swiftly create support for smart contract services their users want without spending time and development resources integrating with each blockchain.

### Sustainability Incentivization

Hybrid smart contracts are advancing [environmental sustainability](https://chain.link/use-cases/climate-markets) by creating better incentives to partake in green practices through advanced verification techniques around the true impact of green initiatives. Oracles are a critical tool for supplying smart contracts with environmental data from sensor readings, satellite imagery, and advanced ML computation, allowing smart contracts to dispense rewards to people practicing reforestation or engaging in conscious consumption. Oracles are also supporting many new forms of carbon credits to offset the impacts of climate change.

## Interoperability Use Cases

[Interoperability](https://chain.link/education-hub/blockchain-interoperability) between multiple blockchains helps assets to flow between networks.    
For example, token swaps involve submitting a token on a source chain and receiving a different token on a destination chain. Cross-chain token swaps are generally made possible by atomic swap protocols and/or cross-chain automated market makers (AMMs), which maintain separate liquidity pools on each blockchain to facilitate the swap. 

Some of the notable use cases of blockchain interoperability are: 

### Cross-Chain Asset Transfers

Users can transfer assets (e.g., tokens, cryptocurrencies) from one blockchain to another without requiring a centralized exchange. For example, Bitcoin (BTC) could be moved to Ethereum as a wrapped token (WBTC) for use in Ethereum-based decentralized finance (DeFi) applications.

### Token Swaps

Interoperability allows users to exchange tokens across different blockchains. For example, a user might swap Ethereum (ETH) for Binance Coin (BNB) using a cross-chain automated market maker (AMM) that maintains liquidity on both Ethereum and Binance Smart Chain, facilitating smooth and secure token exchanges.

### [Cross-Chain NFTs](https://chain.link/education-hub/cross-chain-nft)

Non-fungible tokens (NFTs) can be moved or used across different blockchain networks, enabling broader markets, greater liquidity, and more extensive use cases for digital assets.

### Cross-Chain Governance

DAOs (Decentralized Autonomous Organizations) can implement governance across multiple blockchains. For instance, a vote passed on a DAO in the Ethereum network could automatically initiate changes in a connected protocol on another blockchain, ensuring coordinated governance actions across platforms.

### Programmable Token Bridges

[Programmable token bridges](https://blog.chain.link/ccip-programmable-token-transfers/) combine token bridging with arbitrary messaging. As soon as the tokens are delivered to the destination chain from the source chain, a contract call can be executed. This happens in a single transaction, enabling richer cross-chain functionality, such as staking, swapping, or depositing tokens into a smart contract on the destination chain as part of completing the bridge function.

### Enterprise Blockchain Integration

Enterprises that use different private or permissioned blockchains can interact with public or other enterprise blockchains, enabling broader integration and data sharing across various platforms.

# The End


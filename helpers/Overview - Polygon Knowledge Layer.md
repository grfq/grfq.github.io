# Overview - Polygon Knowledge Layer

The Polygon Proof-of-Stake (PoS) network is a scalable blockchain solution designed to enhance Ethereum's ecosystem by addressing its throughput limitations. As an EVM-compatible sidechain, it enables faster transactions and significantly reduced gas fees while maintaining Ethereum's security framework.

## Dual Layer Architecture

Polygon PoS employs a dual-layer infrastructure to optimize performance and security:

### Heimdall Layer
The consensus layer comprises proof-of-stake nodes that:
- Monitor staking contracts on Ethereum mainnet
- Bridge events between chains
- Submit network checkpoints to Ethereum
The updated Heimdall layer now leverages CometBFT for improved consensus mechanisms.

### Bor Layer
The execution layer consists of block-producing nodes managed by Heimdall validators. It primarily uses Go Ethereum (Geth) but also supports Erigon for enhanced flexibility.

👉 [Explore blockchain technologies](https://bit.ly/okx-bonus)

## Transaction Lifecycle

Understanding the operational workflow enhances user trust:

1. **User initiates transaction** through smart contracts on Polygon PoS
2. **Validation by checkpoint nodes** ensures data integrity
3. **Checkpoint creation** occurs every ~30 minutes
4. **Core contract verification** on Ethereum confirms validity
5. **State updates** execute final changes
6. **Asset transfer** option enables cross-chain movement
7. **Cycle restarts** for new transactions

### FAQ: Why are checkpoints important?
Checkpoint verification secures the network through cryptographic proofs, especially crucial for cross-chain operations. For L2-to-L2 transfers, finality occurs almost instantly.

## Core Contracts on Ethereum

As Polygon PoS's foundation, Ethereum hosts critical smart contracts that:
- Anchor Polygon's state
- Manage cross-chain asset transfers
- Maintain the **exit queue** system for secure fund withdrawal

This integration ensures Polygon inherits Ethereum's security while offering enhanced scalability.

👉 [Learn about cross-chain security](https://bit.ly/okx-bonus)

### FAQ: How does the exit queue work?
The exit queue system enables seamless asset movement between Polygon and Ethereum. Users can transfer funds back to Ethereum mainnet without compromising security or data integrity.

## Public Checkpoint Nodes

These validators perform two essential functions:
1. **Transaction validation** against Polygon's current state
2. **Checkpoint submission** via Merkle roots to Ethereum contracts

They serve as critical intermediaries, ensuring data consistency between the chains through cryptographic proofs.

## Upcoming Developments

Polygon PoS is evolving from its sidechain origins into a **ZK-powered validium** solution. Key upgrades include:
- Integration of Polygon zkEVM's execution environment
- Implementation of dedicated data availability layers
- Interoperability with other ZK-based L2s through Agglayer

This transition will position Polygon PoS as foundational infrastructure for decentralized applications while maintaining compatibility with Ethereum's expanding layer-2 ecosystem.

### FAQ: What are the benefits of ZK technology?
Zero-knowledge proofs will enhance security and efficiency by enabling validity proofs for transactions, reducing data storage requirements while maintaining trustless verification.

## Network Evolution

Originally launched as Matic Network in 2020, Polygon PoS has continually evolved through community-driven proposals. The upcoming ZK-based architecture will offer:
- Improved transaction throughput
- Lower operational costs
- Enhanced cross-chain interoperability via Agglayer
- Better developer tooling and ecosystem integration

This strategic evolution aligns with Ethereum's vision for a multi-layered scaling future, where Polygon PoS serves as both a standalone solution and interoperability hub.

### FAQ: How will developers benefit from these upgrades?
Developers gain access to ZK-powered features like faster finality and lower costs, while maintaining EVM compatibility. The Agglayer integration also simplifies cross-chain dApp development.

👉 [Discover blockchain development tools](https://bit.ly/okx-bonus)
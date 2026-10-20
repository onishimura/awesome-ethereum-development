# Awesome Ethereum Development [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated list of Ethereum development resources

## Contents
- [Frameworks](#frameworks)
- [Libraries](#libraries)
- [Clients](#clients)
- [Tools](#tools)
- [Security](#security)
- [Testing and Devnets](#testing-and-devnets)
- [Network Upgrades & EIPs](#network-upgrades--eips)
- [L2 and Account Abstraction](#l2-and-account-abstraction)
- [Data and Indexing](#data-and-indexing)
- [Testnets](#testnets)
- [Tutorials](#tutorials)
- [IPFS](#ipfs)
- [Practices](#practices)
- [Courses](#courses)
- [Community](#community)
- [Snippets](#snippets)
- [Other lists](#other-lists)
- [General](#general)

## Frameworks
- [Ape](https://github.com/ApeWorX/ape) - Python framework for compiling, testing, deploying, and interacting with smart contracts.
- [Foundry](https://github.com/foundry-rs/foundry) - Rust-based toolkit (Forge/Cast/Anvil/Chisel) for building, testing, fuzzing, and deploying Solidity contracts.
- [Hardhat](https://github.com/NomicFoundation/hardhat) - Ethereum development environment with TypeScript tests, native Solidity tests, multichain simulation, and built-in coverage.
- [OpenZeppelin](https://github.com/OpenZeppelin/openzeppelin-contracts) - Library of secure smart contracts for Ethereum and other EVM chains.
- [Scaffold-ETH 2](https://github.com/scaffold-eth/scaffold-eth-2) - Open-source toolkit for building decentralized applications on Ethereum.

## Libraries
- [Alloy](https://github.com/alloy-rs/alloy) - High-performance, well-tested Ethereum Rust library with full EVM support.
- [ethers.js v6](https://github.com/ethers-io/ethers.js) - Complete Ethereum library with providers, signers, contracts, and ENS support.
- [Ox](https://github.com/wevm/ox) - Lightweight, modular Ethereum development library focused on low-level primitives.
- [Revm](https://github.com/bluealloy/revm) - Rust Ethereum Virtual Machine implementation focused on simplicity and performance.
- [Solady](https://github.com/Vectorized/solady) - Gas-optimized Solidity library with tokens, auth, proxies, and utilities.
- [viem](https://viem.sh) - Lightweight, modular TypeScript Ethereum library with native BigInt and type inference.
- [wagmi](https://wagmi.sh) - React hooks for Ethereum built on viem, with wallet connectors and chain management.
- [web3.py](https://github.com/ApeWorX/web3.py) - Python library for interacting with Ethereum.

## Clients

### Execution Clients
- [Besu](https://github.com/besu-eth/besu) - Java/JVM execution client, Apache-licensed, enterprise-focused.
- [Erigon](https://github.com/erigontech/erigon) - Go execution client with staged sync and efficient archive storage.
- [Geth](https://github.com/ethereum/go-ethereum) - Official Go implementation of the Ethereum protocol.
- [Nethermind](https://github.com/NethermindEth/nethermind) - C#/.NET execution client with strong plugin and metrics support.
- [Reth](https://github.com/paradigmxyz/reth) - Rust execution client focused on modularity and performance.

### Consensus Clients
- [Lighthouse](https://github.com/sigp/lighthouse) - Rust consensus client by Sigma Prime.
- [Lodestar](https://github.com/ChainSafe/lodestar) - TypeScript consensus client by ChainSafe, browser-friendly and research-oriented.
- [Nimbus](https://github.com/status-im/nimbus-eth2) - Nim consensus client, lightweight and resource-efficient.
- [Prysm](https://github.com/OffchainLabs/prysm) - Go consensus client developed by Offchain Labs.
- [Teku](https://github.com/Consensys-Incorporated/teku) - Java consensus client by ConsenSys.

## Tools
- [Remix](https://remix.ethereum.org/) - Browser-based IDE for writing, testing, and deploying smart contracts.

## Security
- [Aderyn](https://github.com/Cyfrin/aderyn) - Rust-based Solidity static analyzer for identifying vulnerabilities.
- [Building Secure Contracts](https://github.com/crytic/building-secure-contracts) - Guidelines and training material for writing secure smart contracts.
- [Certora Prover](https://github.com/Certora/CertoraProver) - Formal verification tool for smart contracts.
- [Common issues](https://medium.com/@sbeyer_31150/ethereum-smart-contract-security-73b0ede73fa8) - Overview of smart contract security vulnerabilities.
- [Echidna](https://github.com/crytic/echidna) - Property-based fuzzer for Ethereum smart contracts.
- [Kontrol](https://github.com/runtimeverification/kontrol) - Formal verification tool for Ethereum smart contracts using K framework.
- [Medusa](https://github.com/crytic/medusa) - Parallel smart-contract fuzzer built on Geth with coverage-guided exploration.
- [OpenZeppelin Monitor](https://github.com/OpenZeppelin/openzeppelin-monitor) - Monitor smart contract events, functions, and transactions.
- [safe-tx-hashes-util](https://github.com/pcaversaccio/safe-tx-hashes-util) - Verify Safe transaction and message hashes before signing.
- [Slither](https://github.com/crytic/slither) - Static analyzer for Solidity with vulnerability detectors and Python API.
- [Storage Exploits](https://medium.com/@sbeyer_31150/storage-allocation-exploits-in-ethereum-smart-contracts-16c2aa312743) - Storage allocation exploits in smart contracts.

## Testing and Devnets
- [ethereum-package](https://github.com/ethpandaops/ethereum-package) - Kurtosis package for spinning up local Ethereum testnets.
- [execution-specs](https://github.com/ethereum/execution-specs) - Python execution specs and test framework for Ethereum.
- [Wake](https://github.com/Ackee-Blockchain/wake) - Python-based development and testing framework for Solidity.

## Network Upgrades & EIPs
- [Dencun/EIP-4844](https://blog.ethereum.org/2024/02/27/dencun-mainnet-announcement) - Blob transactions ([EIP-4844](https://eips.ethereum.org/EIPS/eip-4844)) for reduced L2 data costs (March 2024).
- [ERC-4337](https://ercs.ethereum.org/ERCS/erc-4337) - Account abstraction standard enabling smart contract wallets.
- [Forkcast](https://forkcast.org) - Tool for tracking and analyzing Ethereum network upgrades.
- [Fusaka/PeerDAS](https://ethereum.org/roadmap/fusaka/) - Peer data availability sampling ([EIP-7594](https://eips.ethereum.org/EIPS/eip-7594)) for L2 scaling (December 2025).
- [Pectra/EIP-7702](https://ethereum.org/roadmap/pectra/) - EOA account code delegation ([EIP-7702](https://eips.ethereum.org/EIPS/eip-7702)) (May 2025).
- [Shapella](https://blog.ethereum.org/2023/03/28/shapella-mainnet-announcement) - Staking withdrawals enabled (April 2023).
- [The Merge](https://ethereum.org/roadmap/merge/) - Transition from PoW to PoS (September 2022).

## L2 and Account Abstraction
- [Alto](https://github.com/pimlicolabs/alto) - TypeScript implementation of an ERC-4337 bundler.
- [Arbitrum Orbit](https://docs.arbitrum.io/launch-arbitrum-chain/overview/introduction) - Framework for building customizable L2/L3 chains on Arbitrum.
- [OP Stack](https://github.com/ethereum-optimism/optimism) - Modular framework for building Optimism-based rollups.
- [ZK Stack](https://docs.zksync.io/zk-stack) - Framework for building sovereign ZK chains on zkSync.

## Data and Indexing
- [Blockscout](https://github.com/blockscout/blockscout) - Open-source Blockchain explorer for Ethereum networks.
- [Ponder](https://github.com/ponder-sh/ponder) - Backend framework for Blockchain applications.
- [rindexer](https://github.com/joshstevens19/rindexer) - Ethereum indexer written in Rust.
- [Xatu](https://github.com/ethpandaops/xatu) - Ethereum network monitoring and data collection tool.

## Testnets
- [Hoodi](https://blog.ethereum.org/2025/03/18/hoodi-holesky) - Current testnet for validator and protocol upgrade testing.
- [Sepolia](https://ethereum.org/developers/docs/networks/) - Recommended testnet for application and smart contract development.

## Tutorials
- [B9lab Academy](https://academy.b9lab.com/) - Ethereum development courses.
- [CryptoZombies](https://cryptozombies.io/) - Interactive code school for learning Solidity.
- [Hello World (3 parts)](https://medium.com/@mvmurthy/full-stack-hello-world-voting-ethereum-dapp-tutorial-part-1-40d2d0d807c2) - Full stack voting dApp tutorial.
- [What the Func](https://www.youtube.com/channel/UC0Wu-J4_SoFOYVKA8JRuRRg/videos) - Video tutorials on Ethereum development.

## IPFS
- [An introduction to IPFS](https://medium.com/@ConsenSys/an-introduction-to-ipfs-9bba4860abd0) - Introduction to the InterPlanetary File System.
- [IPFS Documentation](https://docs.ipfs.tech/) - Official IPFS documentation and guides.

## Practices
- [Consensys Smart Contract Best Practices](https://diligence.security/best-practices/) - Comprehensive guide for smart contract security.

## Courses
- [Reddit: Ethereum courses that are actually worth it](https://www.reddit.com/r/ethdev/comments/7yfwzq/solidityethereum_courses_that_are_actually_worth/) - Community-recommended Ethereum courses.

## Community
- [/r/ethdev](https://www.reddit.com/r/ethdev/) - Ethereum development subreddit.

## Snippets
- [Private deploy (TokenMarket)](https://gist.github.com/hsinhoyeh/a6065d0c6620ed420600cfbb095323ac) - Private deployment script.

## Other lists
- [bekatom/awesome-ethereum](https://github.com/bekatom/awesome-ethereum) - Another curated list of Ethereum resources.

## General
- [Understanding ERC-20 token contracts](https://medium.com/@jgm.orinoco/understanding-erc-20-token-contracts-a809a7310aa5) - Guide to ERC-20 tokens.

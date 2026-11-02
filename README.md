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
- [ethrex](https://github.com/lambdaclass/ethrex) - Rust execution client by LambdaClass.
- [Geth](https://github.com/ethereum/go-ethereum) - Official Go implementation of the Ethereum protocol.
- [Nethermind](https://github.com/NethermindEth/nethermind) - C#/.NET execution client with strong plugin and metrics support.
- [Reth](https://github.com/paradigmxyz/reth) - Rust execution client focused on modularity and performance.

### Consensus Clients
- [Grandine](https://github.com/grandinetech/grandine) - Rust consensus client.
- [Lighthouse](https://github.com/sigp/lighthouse) - Rust consensus client by Sigma Prime.
- [Lodestar](https://github.com/ChainSafe/lodestar) - TypeScript consensus client by ChainSafe, browser-friendly and research-oriented.
- [Nimbus](https://github.com/status-im/nimbus-eth2) - Nim consensus client, lightweight and resource-efficient.
- [Prysm](https://github.com/OffchainLabs/prysm) - Go consensus client developed by Offchain Labs.
- [Teku](https://github.com/Consensys-Incorporated/teku) - Java consensus client by ConsenSys.

## Tools
- [evm.codes](https://www.evm.codes/) - Interactive EVM opcode and precompile reference with per-fork gas costs and a playground.
- [Remix](https://remix.ethereum.org/) - Browser-based IDE for writing, testing, and deploying smart contracts.
- [Solhint](https://github.com/protofire/solhint) - Linter for Solidity with security and style rules.
- [Solidity](https://github.com/argotorg/solidity) - Compiler and language for Ethereum smart contracts (v0.8.38, October 22, 2026).
- [Sourcify](https://github.com/argotorg/sourcify) - Open-source contract verification and metadata service (server 4.2.0, October 2026).
- [Vyper](https://github.com/vyperlang/vyper) - Pythonic smart contract language and compiler.

## Security
- [Aderyn](https://github.com/Cyfrin/aderyn) - Rust-based Solidity static analyzer for identifying vulnerabilities.
- [Building Secure Contracts](https://github.com/crytic/building-secure-contracts) - Guidelines and training material for writing secure smart contracts.
- [Certora Prover](https://github.com/Certora/CertoraProver) - Formal verification tool for smart contracts.
- [Echidna](https://github.com/crytic/echidna) - Property-based fuzzer for Ethereum smart contracts.
- [Heimdall](https://github.com/Jon-Becker/heimdall-rs) - EVM bytecode toolkit for decompiling, disassembling, and decoding unverified contracts and calldata.
- [Kontrol](https://github.com/runtimeverification/kontrol) - Formal verification tool for Ethereum smart contracts using K framework.
- [Medusa](https://github.com/crytic/medusa) - Parallel smart-contract fuzzer built on Geth with coverage-guided exploration.
- [OpenZeppelin Monitor](https://github.com/OpenZeppelin/openzeppelin-monitor) - Monitor smart contract events, functions, and transactions.
- [OWASP Smart Contract Top 10](https://scs.owasp.org/sctop10/) - Annually updated ranking of the most critical smart contract vulnerabilities, with prevention guidance.
- [safe-tx-hashes-util](https://github.com/pcaversaccio/safe-tx-hashes-util) - Verify Safe transaction and message hashes before signing.
- [Slither](https://github.com/crytic/slither) - Static analyzer for Solidity with vulnerability detectors and Python API.
- [Solidity Security Considerations](https://docs.soliditylang.org/en/latest/security-considerations.html) - Official Solidity documentation on common pitfalls such as reentrancy, gas limits, and tx.origin.

## Testing and Devnets
- [ethereum-package](https://github.com/ethpandaops/ethereum-package) - Kurtosis package for spinning up local Ethereum testnets.
- [execution-specs](https://github.com/ethereum/execution-specs) - Python execution specs and test framework for Ethereum.
- [Wake](https://github.com/Ackee-Blockchain/wake) - Python-based development and testing framework for Solidity.

## Network Upgrades & EIPs
- [Dencun/EIP-4844](https://blog.ethereum.org/2024/02/27/dencun-mainnet-announcement) - Blob transactions ([EIP-4844](https://eips.ethereum.org/EIPS/eip-4844)) for reduced L2 data costs (March 2024).
- [ERC-4337](https://ercs.ethereum.org/ERCS/erc-4337) - Account abstraction standard enabling smart contract wallets.
- [Forkcast](https://forkcast.org) - Tool for tracking and analyzing Ethereum network upgrades.
- [Fusaka/PeerDAS](https://ethereum.org/roadmap/fusaka/) - Peer data availability sampling ([EIP-7594](https://eips.ethereum.org/EIPS/eip-7594)) for L2 scaling (December 2025).
- [Glamsterdam](https://ethereum.org/roadmap/glamsterdam/) - ePBS ([EIP-7732](https://eips.ethereum.org/EIPS/eip-7732)) and block-level access lists ([EIP-7928](https://eips.ethereum.org/EIPS/eip-7928)); live on Sepolia since October 6, 2026 (Hoodi postponed, mainnet not scheduled).
- [Pectra/EIP-7702](https://ethereum.org/roadmap/pectra/) - EOA account code delegation ([EIP-7702](https://eips.ethereum.org/EIPS/eip-7702)) (May 2025).
- [Shapella](https://blog.ethereum.org/2023/03/28/shapella-mainnet-announcement) - Staking withdrawals enabled (April 2023).
- [The Merge](https://ethereum.org/roadmap/merge/) - Transition from PoW to PoS (September 2022).

## L2 and Account Abstraction
- [Alto](https://github.com/pimlicolabs/alto) - TypeScript implementation of an ERC-4337 bundler.
- [Arbitrum Orbit](https://docs.arbitrum.io/launch-arbitrum-chain/overview/introduction) - Framework for building customizable L2/L3 chains on Arbitrum.
- [OP Stack](https://github.com/ethereum-optimism/optimism) - Modular framework for building Optimism-based rollups.
- [Safe Smart Account](https://github.com/safe-fndn/safe-smart-account) - Audited multisig smart account contracts that underpin Safe wallets.
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
- [CryptoZombies](https://cryptozombies.io/) - Interactive code school for learning Solidity.
- [ethereum.org Developer Tutorials](https://ethereum.org/developers/tutorials/) - Maintained, tagged collection of Ethereum development tutorials.
- [What the Func](https://www.youtube.com/channel/UC0Wu-J4_SoFOYVKA8JRuRRg/videos) - Video tutorials on Ethereum development.

## IPFS
- [Helia](https://github.com/ipfs/helia) - TypeScript implementation of IPFS for browsers and Node.js.
- [IPFS Documentation](https://docs.ipfs.tech/) - Official IPFS documentation and guides.

## Practices
- [Consensys Smart Contract Best Practices](https://consensysdiligence.github.io/smart-contract-best-practices/) - Comprehensive guide for smart contract security.

## Courses
- [Speedrun Ethereum](https://speedrunethereum.com/) - Hands-on Solidity challenges built on Scaffold-ETH 2, from tokens to DEXs, oracles, and ZK voting.

## Community
- [/r/ethdev](https://www.reddit.com/r/ethdev/) - Ethereum development subreddit.

## Other lists
- [bekatom/awesome-ethereum](https://github.com/bekatom/awesome-ethereum) - Another curated list of Ethereum resources.

## General
- [ERC-20 Token Standard](https://ethereum.org/developers/docs/standards/tokens/erc-20/) - Official ethereum.org guide to the ERC-20 token interface.

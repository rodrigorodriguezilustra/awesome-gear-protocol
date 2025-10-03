# Awesome Gear Protocol [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of code and content from the [Gear Protocol](https://github.com/gear-tech/gear) and [Vara Network](https://vara.network) community.
>
> Gear Protocol is an actor‑model smart‑program runtime that powers the **Vara** L1 network. Programs run in WebAssembly, use async message passing, and support fork‑less upgrades, enabling fast, parallelizable dApps.

## Contents
- [Overview](#overview)
- [Gear-Powered Networks](#gear-powered-networks)
- [Whitepapers \& Books](#whitepapers--books)
- [Tutorials](#tutorials)
- [Community](#community)
- [Code](#code)
  - [Standards](#standards)
  - [Frameworks](#frameworks)
  - [Examples](#examples)
- [Tools](#tools)
- [IDEs](#ides)
- [Wallets](#wallets)
- [SDKs](#sdks)
  - [Rust SDKs](#rust-sdks)
  - [TypeScript / JS SDKs](#typescript--js-sdks)
  - [React](#react)
- [Papers](#papers)
- [Videos](#videos)
- [Blog Posts](#blog-posts)
- [Security](#security)

## Overview
- [Vara Docs Portal](https://wiki.vara.network/docs/welcome) - Official documentation hub for building on Vara and Gear.
- [Getting started in 5 minutes](https://wiki.vara.network/docs/getting-started-in-5-minutes) - Write, compile, and deploy your first program.
- [Gear core repo](https://github.com/gear-tech/gear) - Node, runtime, core crates, CLI, and examples.

## Gear-Powered Networks
- [Vara mainnet explorer](https://vara.subscan.io/) - Subscan for Vara blocks, extrinsics, accounts, and events.
- [Network activity](https://vara.network/network) - Live stats, top programs, and finalized blocks.

## Whitepapers & Books
- [Gear Protocol Whitepaper](https://whitepaper.gear.foundation/) - Architecture, properties, and interfaces.
- [Gear.exe Whitepaper](https://gear-tech.io/gear-exe/whitepaper/technical/components) - Off‑chain P2P compute layer design for WebAssembly programs.
- [Technology overview](https://wiki.vara.network/docs/about/technology) - Actor model, persistent memory, and WebAssembly execution.

## Tutorials
- [Build on Vara](https://wiki.vara.network/docs/build) - Developer guide index for programs and tooling.
- [Sails‑JS overview](https://wiki.vara.network/docs/sails-js) - How to use sails‑js to interact with Sails applications.
- [Sails Hello World](https://github.com/Vara-Lab/Sails-Hello-World) - Minimal Sails program and client demonstrating build, deploy, and message flow end to end.
- [Create a program with gstd](https://wiki.gear.foundation/docs/build/gstd/create) - Step‑by‑step program creation flow.

## Community
- [Vara website](https://vara.network/) - Ecosystem, updates, and builder links.
- [Gear Technologies](https://gear-tech.io/) - Company site and engineering posts.
- [Discord](https://discord.gg/gear-vara) - Official community server.
- [X (Twitter)](https://x.com/VaraNetwork) - News and updates.
- [gear-tech on GitHub](https://github.com/gear-tech) - Core organization for Gear code.
- [gear-foundation on GitHub](https://github.com/gear-foundation) - Foundation repos and standards.

## Code

### Standards
- [gear-foundation/standards](https://github.com/gear-foundation/standards) - Canonical VNFT, VFT, and VMT standards and service interfaces.
- [Vara‑Lab/standards](https://github.com/Vara-Lab/standards) - Standalone variants with auto‑generated IDL and client.

### Frameworks
- [Sails](https://github.com/gear-tech/sails) - Higher‑level Rust framework for ergonomic program development on Gear.

### Examples
- [Vara examples index](https://wiki.vara.network/docs/examples) - Curated examples across tokens, auctions, multisig, and more.
- [gear-foundation/dapps](https://github.com/gear-foundation/dapps) - Ecosystem dApps and reference implementations.

## Tools
- [gcli](https://docs.rs/gcli) - Command‑line client for upload, init, message send, key management, and queries.
- [sails-js CLI](https://wiki.gear.foundation/docs/sails-js/client-generation) - Generate TypeScript clients from Sails IDL.

## IDEs
- [Gear IDEA](https://wiki.vara.network/docs/idea) - Browser IDE to build, deploy, and interact with programs on testnet or local.

## Wallets
- [Nova Wallet](https://vara.network/ecosystem/nova-wallet) - Mobile Substrate wallet with Vara support and staking guides.
- [SubWallet](https://www.subwallet.app/) - Browser and mobile wallet for Substrate ecosystems including Vara.
- [Polkadot Vault](https://wiki.vara.network/docs/account/polkadot-vault) - Air‑gapped signing app and setup guide for Vara.

## SDKs

### Rust SDKs
- [gstd](https://docs.rs/gstd) - Core program runtime API for Gear smart programs.
- [gclient](https://docs.rs/gclient) - Client library for interacting with Gear nodes.
- [gtest](https://docs.rs/gtest) - Integration testing utilities for Gear programs.
- [gsdk](https://docs.rs/gsdk) - Utilities and helpers for Gear development.

### TypeScript / JS SDKs
- [@gear-js/api](https://github.com/gear-tech/gear-js/tree/main/apis/gear) - Primary JS/TS API for connecting to Gear/Vara nodes.
- [sails-js](https://github.com/gear-tech/sails/tree/master/js) - TypeScript library for interacting with Sails programs and generated clients.
- [gear-tech/gear-js](https://github.com/gear-tech/gear-js) - Examples, utilities, and docs for JS integrations.

### React
- [@gear-js/react-hooks](https://github.com/gear-tech/gear-js/tree/main/utils/gear-hooks) - React library that provides hooks used across Gear applications.
- [@gear-js/wallet-connect](https://github.com/gear-tech/gear-js/tree/main/utils/wallet-connect) - React library to connect Substrate-based wallets in a standardized and consistent way across decentralized applications.
- [gear-ez-transactions](https://github.com/gear-foundation/dapps/tree/master/frontend/packages/ez-transactions) - React library to provide gasless and signless transactions.
- [create-vara-app](https://github.com/gear-foundation/dapps/tree/master/frontend/templates/create-vara-app)/[create-gear-app](https://github.com/gear-foundation/dapps/tree/master/frontend/templates/create-gear-app) - A ready-made application template with a well-thought-out infrastructure for quickly turning the application on Gear blockchain.

## Papers
- [Inside the Vara Bridge](https://gear-tech.io/news/inside-the-vara-bridge-a-technical-breakdown-of-cross-chain-communication) - Technical breakdown of cross‑chain communication.
- [The Actor Model & Why We Use It](https://gear.foundation/news/the-actor-model-why-we-use-it) - Rationale for message‑passing in Gear.

## Videos
- [Vara Education Hub: Gear Protocol for Beginners](https://vara.network/education-hub/videos/gear-protocol-for-beginners) - Intro video series.

## Blog Posts
- [Development paradigm on Gear](https://medium.com/@gear_techs/development-paradigm-on-gear-fc169db70151) - Architecture, patterns, and dev workflow.
- [Vara Network: pioneering the future of Web3](https://gear-tech.io/news/vara-network-pioneering-the-future-of-web-30-development) - Overview and design notes.

## Security
- [Vara Anti‑Scam](https://vara.network/anti-scam-check) - Official verification and anti‑scam checks for community outreach.

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md). This list follows the [Awesome List](https://github.com/sindresorhus/awesome) guidelines and uses `awesome-lint` in CI.

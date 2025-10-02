# Awesome Gear Protocol [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of code and content from the **Gear Protocol** and **Vara Network** community.
>
> Gear Protocol is an actor‑model smart‑program runtime that powers the **Vara** L1 network. Programs run in WebAssembly (Wasm), use async message passing, and support fork‑less upgrades, enabling fast, parallelizable dApps.

## Contents
- [Awesome Gear Protocol ](#awesome-gear-protocol-)
  - [Contents](#contents)
  - [Overview](#overview)
  - [Gear‑Powered Networks](#gearpowered-networks)
  - [Whitepapers \& Books](#whitepapers--books)
  - [Tutorials](#tutorials)
  - [Community](#community)
  - [Code](#code)
    - [Standards](#standards)
    - [Frameworks](#frameworks)
    - [Libraries](#libraries)
    - [Examples](#examples)
  - [Tools](#tools)
  - [IDEs](#ides)
  - [Wallets](#wallets)
  - [SDKs](#sdks)
    - [Rust SDKs](#rust-sdks)
    - [TypeScript / JS SDKs](#typescript--js-sdks)
  - [Papers](#papers)
  - [Videos](#videos)
  - [Blog Posts](#blog-posts)
  - [Security](#security)
  - [Contributing](#contributing)

## Overview
- **Vara Docs Portal** — official documentation hub for building on Vara and Gear.  [wiki.vara.network/docs/welcome](https://wiki.vara.network/docs/welcome).
- **Getting started in 5 minutes** — write, compile, and deploy your first program.  [wiki.vara.network/docs/getting-started-in-5-minutes](https://wiki.vara.network/docs/getting-started-in-5-minutes).
- **Gear core repo** — node, runtime, core crates, CLI, and examples.  [github.com/gear-tech/gear](https://github.com/gear-tech/gear).

## Gear‑Powered Networks
- **Vara mainnet** — standalone L1 powered by Gear with explorer at Subscan.  [vara.subscan.io](https://vara.subscan.io/).
- **Network activity** — live stats, top programs, and finalized blocks.  [vara.network/network](https://vara.network/network).

## Whitepapers & Books
- **Gear Protocol Whitepaper** — v1.2, architecture, properties, and interfaces.  [whitepaper.gear.foundation](https://whitepaper.gear.foundation/).
- **Gear.exe Whitepaper** — off‑chain P2P compute layer design for Wasm programs.  [gear-tech.io/gear-exe/whitepaper/technical/components](https://gear-tech.io/gear-exe/whitepaper/technical/components).
- **Technology overview** — actor model, persistent memory, and Wasm execution.  [wiki.vara.network/docs/about/technology](https://wiki.vara.network/docs/about/technology).

## Tutorials
- **Build on Vara** — developer guide index for programs and tooling.  [wiki.vara.network/docs/build](https://wiki.vara.network/docs/build).
- **Examples catalog** — reference programs ready to compile and extend.  [wiki.vara.network/docs/examples](https://wiki.vara.network/docs/examples).
- **Sails-JS overview** — how to use sails-js to interact with Sails applications.  [wiki.vara.network/docs/sails-js](https://wiki.vara.network/docs/sails-js).
- **Create a program with `gstd`** — step‑by‑step program creation flow.  [wiki.gear.foundation/docs/build/gstd/create](https://wiki.gear.foundation/docs/build/gstd/create).

## Community
- **Vara website** — ecosystem, updates, and builder links.  [vara.network](https://vara.network/).
- **Gear Technologies** — company site and engineering posts.  [gear-tech.io](https://gear-tech.io/).
- **Discord** — official community server.  [discord.gg/gear-vara](https://discord.gg/gear-vara).
- **X (Twitter)** — news and updates.  [x.com/VaraNetwork](https://x.com/VaraNetwork).
- **GitHub orgs** — source code and standards.  [github.com/gear-tech](https://github.com/gear-tech) · [github.com/gear-foundation](https://github.com/gear-foundation).

## Code
Code written for Gear/Vara.

### Standards
- **gear-foundation/standards** — canonical VNFT, VFT, and VMT standards and service interfaces.  [github.com/gear-foundation/standards](https://github.com/gear-foundation/standards).
- **Vara‑Lab/standards** — standalone, buildable variants with auto‑generated IDL and client.  [github.com/Vara-Lab/standards](https://github.com/Vara-Lab/standards).

### Frameworks
- **Sails** — higher‑level Rust framework for ergonomic program development on Gear.  [github.com/gear-tech/sails](https://github.com/gear-tech/sails).

### Libraries
- **Core crates** — `gstd`, `gcore`, `gclient`, `gtest`, `gsdk` used across programs and tooling.  [github.com/gear-tech/gear](https://github.com/gear-tech/gear).

### Examples
- **Vara examples index** — curated examples across tokens, auctions, multisig, and more.  [wiki.vara.network/docs/examples](https://wiki.vara.network/docs/examples).
- **gear-foundation/dapps** — ecosystem dApps and reference implementations.  [github.com/gear-foundation/dapps](https://github.com/gear-foundation/dapps).

## Tools
- **gcli** — command‑line client for upload, init, message send, key management, and queries.  [docs.rs/gcli](https://docs.rs/gcli).
- **sails-js CLI** — generates TypeScript client libraries from Sails IDL (code generation).  [wiki.gear.foundation/docs/sails-js/client-generation](https://wiki.gear.foundation/docs/sails-js/client-generation).
- **Subscan (Vara)** — blocks, extrinsics, accounts, and events.  [vara.subscan.io](https://vara.subscan.io/).

## IDEs
- **Gear IDEA** — browser IDE to build, deploy, and interact with programs on testnet or local.  [wiki.vara.network/docs/idea](https://wiki.vara.network/docs/idea).

## Wallets
- **Nova Wallet** — mobile Substrate wallet with Vara support and staking guides.  [vara.network/ecosystem/nova-wallet](https://vara.network/ecosystem/nova-wallet).
- **SubWallet** — browser and mobile wallet for Substrate ecosystems including Vara.  [subwallet.app](https://www.subwallet.app/).
- **Polkadot Vault** — air‑gapped signing app and setup guide for Vara.  [wiki.vara.network/docs/account/polkadot-vault](https://wiki.vara.network/docs/account/polkadot-vault).

## SDKs

### Rust SDKs
- **gear core crates** — program runtime (`gstd`, `gcore`), client and testing (`gclient`, `gtest`), utilities (`gsdk`).  [github.com/gear-tech/gear](https://github.com/gear-tech/gear).
- **Sails** — opinionated Rust framework for writing and composing programs.  [github.com/gear-tech/sails](https://github.com/gear-tech/sails).

### TypeScript / JS SDKs
- **@gear-js/api** — primary JS/TS API for connecting to Gear/Vara nodes.  [npmjs.com/package/@gear-js/api](https://www.npmjs.com/package/@gear-js/api).
- **sails-js** — TypeScript library for interacting with Sails programs and generated clients.  [npmjs.com/package/sails-js](https://www.npmjs.com/package/sails-js).
- **gear-tech/gear-js** — examples, utilities, and docs for JS integrations.  [github.com/gear-tech/gear-js](https://github.com/gear-tech/gear-js).

## Papers
- **Gear Protocol Whitepaper** — design goals and architecture of Gear.  [whitepaper.gear.foundation](https://whitepaper.gear.foundation/).
- **Inside the Vara Bridge** — technical breakdown of cross‑chain communication.  [gear-tech.io/news/inside-the-vara-bridge-a-technical-breakdown-of-cross-chain-communication](https://gear-tech.io/news/inside-the-vara-bridge-a-technical-breakdown-of-cross-chain-communication).
- **The Actor Model & Why We Use It** — rationale for message‑passing in Gear.  [gear.foundation/news/the-actor-model-why-we-use-it](https://gear.foundation/news/the-actor-model-why-we-use-it).

## Videos
- **Vara Education Hub: Gear Protocol for Beginners** — intro video series.  [vara.network/education-hub/videos/gear-protocol-for-beginners](https://vara.network/education-hub/videos/gear-protocol-for-beginners).

## Blog Posts
- **Development paradigm on Gear** — architecture, patterns, and dev workflow.  [medium.com/@gear_techs/development-paradigm-on-gear-fc169db70151](https://medium.com/@gear_techs/development-paradigm-on-gear-fc169db70151).
- **Vara Network: pioneering the future of Web3** — overview and design notes.  [gear-tech.io/news/vara-network-pioneering-the-future-of-web-30-development](https://gear-tech.io/news/vara-network-pioneering-the-future-of-web-30-development).

## Security
- **Vara Anti‑Scam** — official verification and anti‑scam checks for community outreach.  [vara.network/anti-scam-check](https://vara.network/anti-scam-check).
- **Polkadot Vault** — air‑gapped operational security for signing on Vara.  [wiki.vara.network/docs/account/polkadot-vault](https://wiki.vara.network/docs/account/polkadot-vault).

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md). This list follows the [Awesome List](https://github.com/sindresorhus/awesome) guidelines and uses `awesome-lint` in CI.

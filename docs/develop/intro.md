---
title: Getting Started
sidebar_position: 1
description: A Getting Started guide for the Autonomys Network
keywords:
    - Developers Documentation
    - DevDocs
    - SDK
    - Auto SDK
---

### Introduction
Autonomys is a secure, scalable, and decentralized blockchain that resolves the blockchain trilemma without making compromises. It offers a platform where developers can build applications with ease, leveraging innovative protocols and familiar tools. This guide provides an overview of the development options available on the Autonomys Network.

### Is It Difficult to Build Applications on Autonomys?

Absolutely not! Our primary objective is to minimize barriers to entry for both farmers and developers.

We pride ourselves on enabling unlimited possibilities - there are no boundaries!

## Development Options

**Developers** can choose to utilize **Auto SDK** - a comprehensive toolkit designed to simplify development on the Autonomys Network, or **Nova** - Autonomys's EVM-compatible domain, allowing you to utilize all the familiar functionalities available on networks like Ethereum. Soon, you'll also be able to build your own local custom virtual machines.

## [Auto SDK](/develop/auto-sdk/intro)

### Key Features:
- **Modular Packages**: The SDK is organized into packages like auto-utils, auto-consensus, and auto-id. This partitions functionality intuitively and allows you to import only what you need.
- **Simplified Interactions**: Abstracts the complexity of blockchain operations with high-level functions.
- **Flexibility**: Suitable for building decentralized applications (dApps) and services with ease.

### Getting Started with Auto SDK
To start using Auto SDK, refer to our [Setup Instructions](/develop/auto-sdk/intro) to clone the repository, install dependencies, and run tests. The SDK is designed to be developer-friendly, ensuring you can get up and running quickly.

## [Nova - EVM Compatible Domain](/develop/nova/introduction)

:::info
Currently, Nova is available exclusively on the **Gemini-3h** network. It will soon be accessible on the new test network, **Taurus**.

Nova's availability on the mainnet is planned for **Phase 2 of the mainnet launch**. For further details, please refer to our [Phased Launch Roadmap](https://forum.autonomys.xyz/t/phased-launch-roadmap/4414) post on the forum.
:::

### Key Features:
- **Solidity Smart Contracts**: Write and deploy smart contracts using Solidity, just as you would on Ethereum.
- **Tool Compatibility**: Any tool available for Ethereum development - like Remix, Truffle, or Hardhat - is compatible with Nova.
- **Seamless Transition**: Developers familiar with Ethereum can transition to Autonomys without a steep learning curve.

### Why Use Nova?
- **Familiar Environment**: Leverage existing knowledge and resources from the Ethereum ecosystem.
- **Scalability and Security**: Benefit from Autonomys's scalable and secure infrastructure while using tried-and-true development practices.
- **Interoperability**: Create applications that can interact seamlessly with other EVM-compatible networks.

### Getting Started with Nova
To start using Nova, refer to our [Guides and Manuals](/develop/nova/introduction).


## RPC endpoints

**List of Currently Active RPCs endpoints**

#### Consensus
- wss://rpc-0.gemini-3h.subspace.network/ws
- wss://rpc-1.gemini-3h.subspace.network/ws
- wss://rpc.taurus.subspace.foundation/ws
- wss://rpc.mainnet.subspace.foundation/ws

:::tip Nova
Currently, Nova is available exclusively on the gemini-3h network. It will soon be accessible on the taurus network.
:::

#### Nova
- wss://nova-0.gemini-3h.subspace.network/ws 
- wss://nova-1.gemini-3h.subspace.network/ws

:::tip Auto ID
Currently, Auto ID is available exclusively on the gemini-3h network. It will soon be accessible on the taurus network.
:::

#### Auto ID
- wss://autoid-0.gemini-3h.subspace.network/ws
---
title: Overview
section: Docs
order: 0
---

colonyJS is a library to help developers build with Colony.

Using the colonyJS library, you can build applications that query and interact with the Colony Network smart contracts through a simple and standard JavaScript interface.

![overview diagram](img/colonyJS_overview_r1.svg)

colonyJS itself is split into a few components to allow for flexibility in development:

* [Loaders](/colonyjs/docs-loaders) provide a simple way to get the address and ABI of a deployed contract, in a certain version, at a particular location (testnet, mainnet, local). Loaders can pull from etherscan.io, or from Colony's own TrufflePig.

* [Adapters](/colonyjs/docs-adapters) represent the colonyJS solution for the many different ways to access the Ethereum blockchain provided by various JavaScript libraries. Adapters provide a wrapper for such libraries that enforces a standard and predictable API for use with Colony's contracts.

* The [Contract Client](/colonyjs/docs-contractclient) is the main event: it aggregates all of the interactions possible with Colony into a standard set of methods that can be used in your (d)app to hook into the Colony Network.

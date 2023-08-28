---
title: extension
categories: ['typescript', 'polkadot', 'substrate']
---
## [extension](https://github.com/polkadot-js/extension)

### Simple browser extension for managing Polkadot and Substrate network accounts in a browser. Allows the signing of extrinsics using these accounts. Also provides a simple interface for compliant extensions for dapps.


A very simple scaffolding browser extension that injects a [@polkadot/api](https://github.com/polkadot-js/api) Signer into a page, along with any associated accounts, allowing for use by any dapp. This is an extensible POC implementation of a Polkadot/Substrate browser signer.

As it stands, it does one thing: it _only_ manages accounts and allows the signing of transactions with those accounts. It does not inject providers for use by dapps at this early point, nor does it perform wallet functions where it constructs and submits txs to the network.

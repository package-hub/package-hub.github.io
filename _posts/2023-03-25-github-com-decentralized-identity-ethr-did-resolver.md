---
title: ethr-did-resolver
categories: ['typescript', 'wg-id', 'decentralized-identity']
---
## [ethr-did-resolver](https://github.com/decentralized-identity/ethr-did-resolver)

### DID resolver for Ethereum Addresses with support for key management


This library is intended to use ethereum addresses or secp256k1 publicKeys as fully self-managed
[Decentralized Identifiers](https://w3c.github.io/did-core/#identifier) and wrap them in a
[DID Document](https://w3c.github.io/did-core/#did-document-properties)

It supports the proposed [Decentralized Identifiers](https://w3c.github.io/did-core/#identifier) spec from the
[W3C Credentials Community Group](https://w3c-ccg.github.io).

It requires the `did-resolver` library, which is the primary interface for resolving DIDs.

This DID method relies on the [ethr-did-registry](https://github.com/uport-project/ethr-did-registry).

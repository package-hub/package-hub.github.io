---
title: ethr-did-registry
categories: ['typescript']
---
## [ethr-did-registry](https://github.com/uport-project/ethr-did-registry)

### Ethereum registry for ERC-1056 ethr did methods


This library contains the Ethereum contract code that allows the owner of an ethr-did identity to update the attributes
that appear in its did-document. It exposes an API that allows developers to call the contract functions using
Javascript.

Use this if you want to interact directly with a deployed registry contract directly, or deploy a copy of the contract
to another Ethereum network.

A DID is an [Identifier](https://w3c.github.io/did-core/#a-simple-example) that allows you to lookup
a [DID document](https://w3c.github.io/did-core/#example-a-simple-did-document) that can be used to authenticate you and
messages created by you.

It's designed for resolving public keys for off-chain authentication—where the public key resolution is handled by using
decentralized technology.

This contract allows Ethereum addresses to present signing information about themselves with no prior registration. It
allows them to perform key rotation and specify different keys and services that are used on its behalf for both on and
off-chain usage.

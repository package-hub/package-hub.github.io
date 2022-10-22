---
title: PyGrid
categories: ['python', 'peer-to-peer', 'pygrid']
---
## [PyGrid](https://github.com/OpenMined/PyGrid)

### A Peer-to-peer Platform for Secure, Privacy-preserving, Decentralized Data Science


PyGrid platform is composed by three different components.

- **Network** - A Flask-based application used to manage, monitor, control, and route instructions to various PyGrid Domains.
- **Domain** - A Flask-based application used to store private data and models for federated learning, as well as to issue instructions to various PyGrid Workers.
- **Worker** - An emphemeral instance, managed by a PyGrid Domain, that is used to compute data.

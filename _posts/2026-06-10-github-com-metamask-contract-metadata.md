---
title: contract-metadata
categories: ['javascript']
---
## [contract-metadata](https://github.com/MetaMask/contract-metadata)

### A mapping of ethereum contract addresses to broadly accepted icons for those addresses.


A mapping of checksummed Ethereum contract addresses to metadata, like names, and images of their logos.

All address keys follow the [EIP 55 address checksum format](https://github.com/ethereum/EIPs/issues/55).
All file keys follow the [CAIP 19 asset id format](https://github.com/ChainAgnostic/CAIPs/blob/main/CAIPs/caip-19.md).

This repository is effectively frozen. We recommend that developers of new tokens use [EIP 747](https://docs.metamask.io/guide/registering-your-token.html) to ask the user's permission to display your tokens in their wallet. This reduces the dangers of airdrop-based phishing, and reduces administrative overhead from managing this list.

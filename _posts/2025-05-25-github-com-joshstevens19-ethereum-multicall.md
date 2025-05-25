---
title: ethereum-multicall
categories: ['typescript']
---
## [ethereum-multicall](https://github.com/joshstevens19/ethereum-multicall)

### Ability to call many ethereum constant function calls in 1 JSONRPC request


ethereum-multicall is a lightweight library for interacting with the [`Multicall3`](https://github.com/mds1/multicall) smart contract. 

Multicall allows multiple smart contract constant function calls to be grouped into a single call and the results aggregated into a single result. This reduces the number of separate JSON RPC requests that need to be sent over the network if using a remote node like Infura, and provides the guarantee that all values returned are from the same block. The latest block number is also returned along with the aggregated results.

ethereum-multicall is fully written in typescript so has full compile time support. The motivation of this package was to expose a super simple and easy to understand interface for you to take the full benefits of the multicalls. Also to not being opinionated on how you use it, you can use it with web3, ethers or even pass in a custom nodeUrl and we do it for you. This package takes care of the decoding for you but at the same time if you dont want it to you can turn that part off.

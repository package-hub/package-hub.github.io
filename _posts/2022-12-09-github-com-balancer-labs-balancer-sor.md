---
title: balancer-sor
categories: ['typescript']
---
## [balancer-sor](https://github.com/balancer-labs/balancer-sor)

### Smart order router: off-chain linear optimization of routing orders across pools for best price execution


There are two types of swap available:

**swapExactIn** - i.e. You want to swap exactly 1 ETH as input and SOR will calculate X amount of BAL you receive in return.  
or  
**swapExactOut** - i.e. You want to receive exactly 1 BAL and SOR will calculate X amount of ETH you must input.

The SOR will return totalReturn/totalInput as well as a list swaps to achieve the total. Swaps can be through direct pools, i.e. A > POOL1 > B, or via a multihop pool, i.e. A > POOL1 > C > POOL2 > B. The swaps are returned in a format that can be directly to the Vault to execute the trade.

The example file `swapExample.ts` in: [./testScripts](test/testScripts/), demonstrates full examples with comments.

To Run:

Create a .env file in root dir with your infura provider key: `INFURA=your_key`

Install dependencies: `$ yarn install`

Run example: `$ ts-node ./test/testScripts/swapExample.ts`

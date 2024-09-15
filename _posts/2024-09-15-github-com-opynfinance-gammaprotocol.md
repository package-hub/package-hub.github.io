---
title: GammaProtocol
categories: ['typescript', 'solidity', 'ethereum']
---
## [GammaProtocol](https://github.com/opynfinance/GammaProtocol)

### The most powerful, capital efficient DeFi options protocol


Gamma is a decentralized capital efficient option protocol that enables sellers to create spreads. 
Gamma protocol enables any user to create arbitrary option tokens, that represent the right to buy or sell a certain asset in a predefined price (strike price) at or before expiry. 
As the option seller in Gamma, you can reduce the amount of capital locked in the system by creating spreads. (e.g Instead of putting down 100 USDC and mint 1 ETH-USDC-100 Put, you can buy a ETH-USDC-50 Put, and only deposit 50 USDC as collateral)
The oTokens created by Gamma are cash settled European option, means all the options will automatically be exercised at expiry. A holder can redeem the proceeds by sending the oTokens back, the system will pay the holder the cash value based on strike price and underlying spot price at expiry, instead of actually exchanging the underlying asset and the strike asset.

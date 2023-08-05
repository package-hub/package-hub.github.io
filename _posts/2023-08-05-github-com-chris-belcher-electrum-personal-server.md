---
title: electrum-personal-server
categories: ['python']
---
## [electrum-personal-server](https://github.com/chris-belcher/electrum-personal-server)

### Maximally lightweight electrum server for a single user


Electrum Personal Server aims to make using Electrum bitcoin wallet more secure
and more private. It makes it easy to connect your Electrum wallet to your own
full node.

[Full node](https://en.bitcoin.it/wiki/Full_node) wallets are important in
bitcoin because they are a big part of what makes the system trustless. No
longer do people have to trust a financial institution like a bank or Paypal,
they can run software on their own computers. If bitcoin is digital gold, then
a full node wallet is your own personal goldsmith who checks for you that
received payments are genuine.

Full node wallets are also important for privacy. Using Electrum under default
configuration requires it to send (hashes of) all your bitcoin addresses to some
server. That server can then easily spy on your transactions. Full node
wallets like Electrum Personal Server would download the entire blockchain and
scan it for the user's own addresses, and therefore don't reveal to anyone else
which bitcoin addresses they are interested in.

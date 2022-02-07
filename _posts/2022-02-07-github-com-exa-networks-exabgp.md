---
title: exabgp
categories: ['python', 'bgp', 'ddos-protection']
---
## [exabgp](https://github.com/Exa-Networks/exabgp)

### The BGP swiss army knife of networking


[ExaBGP](https://github.com/Exa-Networks/exabgp) provides a convenient way to implement [Software Defined Networking](https://en.wikipedia.org/wiki/Software-defined_networking) by transforming [BGP messages](http://thomas.mangin.com/data/pdf/UKNOF%2015%20-%20Mangin%20-%20Naked%20BGP.pdf) into friendly plain [text or JSON](https://github.com/Exa-Networks/exabgp/wiki/Controlling-ExaBGP-:-API-for-received-messages), which can then be easily handled by simple scripts or your BSS/OSS.

It is routinely used to improve service resilience and provide protection against network or service failures. For example, thanks to the `healthcheck` backend included, anycasted DNS service failures can be detected and handled [gracefully](http://blog.iweb-hosting.co.uk/blog/2012/01/27/using-bgp-to-serve-high-availability-dns/). To help you get started, [Vincent Bernat](https://github.com/vincentbernat) put forward a full lab [explaining](https://vincent.bernat.ch/en/blog/2013-exabgp-highavailability)  how to best use this feature.

Also, [alone](http://perso.nautile.fr/prez/fgabut-flowspec-frnog-final.pdf) or in conjunction with [FastNetMon](https://github.com/pavel-odintsov/fastnetmon) or [WanGuard](https://www.andrisoft.com/software/wanguard), it provides network operators a cost effective DDOS protection solution.

Thanks to modern routers' flow balancing, ExaBGP can also be used to save you money on [load balancers](https://tech.shutterstock.com/2014/05/22/stop-buying-load-balancers), some good information can be found [here](https://vincent.bernat.ch/en/blog/2018-multi-tier-loadbalancer) too.

Other uses include keeping an eye on network changes done as was done by [RIPE](https://labs.ripe.net/Members/wouter_miltenburg/researching-next-generation-ris-route-collectors) or by other networks with [GIXLG](https://github.com/dpiekacz/gixlg/wiki/GIXLG-wiki).

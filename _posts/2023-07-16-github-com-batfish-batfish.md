---
title: batfish
categories: ['java', 'network', 'configuration']
---
## [batfish](https://github.com/batfish/batfish)

### Batfish is a network configuration analysis tool that can find bugs and guarantee the correctness of (planned or current) network configurations. It enables network engineers to rapidly and safely evolve their network, without fear of outages or security breaches.


Batfish is a network validation tool that provides correctness guarantees for security, reliability, and compliance by analyzing the configuration of network devices. It builds complete models of network behavior from device configurations and finds violations of network policies (built-in, user-defined, and best-practices).

A primary use case for Batfish is to validate configuration changes *before* deployment (though it can be used to validate deployed configurations as well). Pre-deployment validation is a critical gap in existing network automation workflows. By including Batfish in automation workflows, network engineers can close this gap and ensure that only correct changes are deployed.

**Batfish does NOT require direct access to network devices.** The core analysis requires only the configuration of network devices. This analysis may be enhanced using additional information from the network such as:
* BGP routes received from external peers
* Topology information represented by LLDP/CDP

See [www.batfish.org](http://www.batfish.org) for technical information on how it works.

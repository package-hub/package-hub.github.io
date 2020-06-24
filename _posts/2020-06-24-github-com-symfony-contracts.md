---
title: contracts
categories: ['php', 'symfony', 'contract']
---
## [contracts](https://github.com/symfony/contracts)

### A set of abstractions extracted out of the Symfony components


The abstractions in this package are useful to achieve loose coupling and
interoperability. By using the provided interfaces as type hints, you are able
to reuse any implementations that match their contracts. It could be a Symfony
component, or another one provided by the PHP community at large.

Depending on their semantics, some interfaces can be combined with autowiring to
seamlessly inject a service in your classes.

Others might be useful as labeling interfaces, to hint about a specific behavior
that could be enabled when using autoconfiguration or manual service tagging (or
any other means provided by your framework.)

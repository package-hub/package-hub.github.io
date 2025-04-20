---
title: scribble
categories: ['typescript', 'scribble', 'language']
---
## [scribble](https://github.com/ConsenSysDiligence/scribble)

### Scribble instrumentation tool


The design of the Scribble specification language takes inspiration from several existing
languages and we expect the language to evolve gradually as we gain more experience
in using it. We rely on the following principles and design goals to guide language
evolution:

1. Specifications are easy to understand by developers and auditors
2. Specifications are simple to reason about
3. Specifications can be efficiently checked using off-the-shelf analysis tools
4. A small number of core specification constructs are sufficient to express and reason about more advanced constructs

We are aware that this will make it difficult or impossible to express certain
properties. We encourage users to reach out if they encounter such properties. However, it
is not our itention to support every property imaginable. We consider it a great success if
Scribble is able to capture 95% of the properties that users _want_ to express.

---
title: mobius
categories: ['java', 'android', 'functional-reactive-programming']
---
## [mobius](https://github.com/spotify/mobius)

### A functional reactive framework for managing state evolution and side-effects.


Mobius is in Production status, meaning it is used in production in Spotify Android applications, and that we consider the APIs to be stable and the implementation bug-free. We will not make backwards-compatibility-breaking changes.

Mobius is currently built for Java 7 (because Java 8 is not fully supported on all versions of Android), hence the duplication of some concepts defined in `java.util.function` (see `com.spotify.mobius.functions`).

When using Mobius, we recommend using Kotlin or Java 8 or later, primarily because of the improved type inference and because using lambdas greatly improves readability and conciseness of code.

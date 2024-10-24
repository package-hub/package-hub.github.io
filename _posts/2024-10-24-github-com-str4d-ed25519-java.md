---
title: ed25519-java
categories: ['java', 'eddsa', 'ed25519']
---
## [ed25519-java](https://github.com/str4d/ed25519-java)

### Pure Java implementation of EdDSA


- The library has been extensively profiled for contention issues in a multi-threaded environment.  The only
  remaining potential contention is in `EdDSANamedCurveTable.defineCurve()`, which will be rarely called.
- The public constant for the curve name has returned as `ED_25519`, and the curve specification has a public
  constant `ED_25519_CURVE_SPEC` to avoid repeated lookups when converting to and from encoded form for the
  public or private keys.
- `GroupElement` is now completely immutable, and all fields final, to avoid the need for `synchronized`
  blocks over mutable fields. This required some new constructors and paths to construction.
- `EdDSAPublicKeySpec.getNegativeA()` and `EdDSAPublicKey.getNegativeA()` now evaluate lazily, taking
  advantage of the immutability of `GroupElement.negate()`. This boosts the performance of the public key
  constructor when the key is just being passed around rather than used.
- Support for X509Key wrapped EdDSA public keys.

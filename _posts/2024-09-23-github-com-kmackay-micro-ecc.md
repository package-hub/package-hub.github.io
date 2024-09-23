---
title: micro-ecc
categories: ['php']
---
## [micro-ecc](https://github.com/kmackay/micro-ecc)

### ECDH and ECDSA for 8-bit, 32-bit, and 64-bit processors.

Compressed points are represented in the standard format as defined in http://www.secg.org/sec1-v2.pdf; uncompressed points are represented in standard format, but without the `0x04` prefix. All functions except `uECC_decompress()` only accept uncompressed points; use `uECC_compress()` and `uECC_decompress()` to convert between compressed and uncompressed point representations.

Private keys are represented in the standard format.

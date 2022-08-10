---
title: s3s3mirror
categories: ['java']
---
## [s3s3mirror](https://github.com/cobbzilla/s3s3mirror)

### Mirror one S3 bucket to another S3 bucket, or to/from the local filesystem.


I started with "s3cmd sync" but found that with buckets containing many thousands of objects, it was incredibly slow
to start and consumed *massive* amounts of memory. So I designed s3s3mirror to start copying immediately with an intelligently
chosen "chunk size" and to operate in a highly-threaded, streaming fashion, so memory requirements are much lower.

Running with 100 threads, I found the gating factor to be *how fast I could list items from the source bucket* (!?!)
Which makes me wonder if there is any way to do this faster. I'm sure there must be, but this is pretty damn fast.

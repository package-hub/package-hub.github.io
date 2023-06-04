---
title: wa-sqlite
categories: ['javascript', 'sqlite', 'webassembly']
---
## [wa-sqlite](https://github.com/rhashimoto/wa-sqlite)

### WebAssembly SQLite with experimental support for browser storage extensions

This is a WebAssembly build of SQLite with experimental support for writing SQLite virtual filesystems and virtual table modules completely in Javascript. This allows alternative browser storage options such as IndexedDB and File System Access. Applications can opt to use either a synchronous or asynchronous (using Asyncify) SQLite library build (an asynchronous build is required for asynchronous extensions).

[IndexedDB](https://github.com/rhashimoto/wa-sqlite/blob/master/src/examples/IDBMinimalVFS.js) and [Origin Private File System](https://github.com/rhashimoto/wa-sqlite/blob/master/src/examples/OriginPrivateFileSystemVFS.js) virtual file systems and a [virtual table module that accesses Javascript arrays](https://github.com/rhashimoto/wa-sqlite/blob/master/src/examples/ArrayModule.js) are among the examples provided as proof of concept.

[Try the demo](https://rhashimoto.github.io/wa-sqlite/demo/) or run [benchmarks](https://rhashimoto.github.io/wa-sqlite/demo/benchmarks.html) with a modern desktop web browser. More information is available in the [FAQ](https://github.com/rhashimoto/wa-sqlite/issues?q=is%3Aissue+label%3Afaq+), [discussion forums](https://github.com/rhashimoto/wa-sqlite/discussions), and [API reference](https://rhashimoto.github.io/wa-sqlite/docs/).

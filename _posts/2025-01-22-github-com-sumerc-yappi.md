---
title: yappi
categories: ['python', 'profilers', 'multi-threaded-applications']
---
## [yappi](https://github.com/sumerc/yappi)

### Yet Another Python Profiler, but this time multithreading, asyncio and gevent aware.


- **Fast**: Yappi is fast. It is completely written in C and lots of love and care went into making it fast.
- **Unique**: Yappi supports multithreaded, [asyncio](https://github.com/sumerc/yappi/blob/master/doc/coroutine-profiling.md) and [gevent](https://github.com/sumerc/yappi/blob/master/doc/greenlet-profiling.md) profiling. Tagging/filtering multiple profiler results has interesting [use cases](https://github.com/sumerc/yappi/blob/master/doc/api.md#set_tag_callback).
- **Intuitive**: Profiler can be started/stopped and results can be obtained from any time and any thread.
- **Standards Compliant**: Profiler results can be saved in [callgrind](http://valgrind.org/docs/manual/cl-format.html) or [pstat](http://docs.python.org/3.4/library/profile.html#pstats.Stats) formats.
- **Rich in Feature set**: Profiler results can show either [Wall Time](https://en.wikipedia.org/wiki/Elapsed_real_time) or actual [CPU Time](http://en.wikipedia.org/wiki/CPU_time) and can be aggregated from different sessions. Various flags are defined for filtering and sorting profiler results.
- **Robust**: Yappi has been around for years.

---
title: pigaios
categories: ['python']
---
## [pigaios](https://github.com/joxeankoret/pigaios)

### A tool for matching and diffing source codes directly against binaries.


Pigaios ('πηγαίος', Greek for 'source' as in 'source code') is a tool for diffing/matching source codes directly against binaries. The idea is to point a tool to a code base, regardless of it being compilable or not (for example, partial source code or source code for platforms not at your hand), extract information from that code base and, then, import in an IDA database function names (symbols), structures and enumerations. It uses the Python CLang bindings (which are very limited, but still better than using pycparser).

Basically, the tool does the following:

 * Parse C source code and extract features from the Abstract Syntax Tree (AST) of each function.
 * Export the same data extracted from C source codes from IDA databases.
 * Find matches between the features found in C source codes and IDA databases.
 * After an initial set of matches with no false positive is found, find more matches from the callgraph.
 * Rate the matches using both an "expert system" and a "machine learning" based system.
 * Also, import into the IDA database all the required structures and enumerations of a given code base (something not trivial in IDA).
 
The tool was released in October 2018, during the [Hacktivity](https://www.hacktivity.com/) conference.

NOTE: If you're looking for a tool for diffing or matching between binaries or if you can properly build binaries, you might want to take a look to [Diaphora](https://github.com/joxeankoret/diaphora).

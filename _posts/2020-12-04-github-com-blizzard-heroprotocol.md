---
title: heroprotocol
categories: ['python']
---
## [heroprotocol](https://github.com/Blizzard/heroprotocol)

### Python library to decode Heroes of the Storm replays


heroprotocol is a [Python](https://www.python.org/downloads/) library and command-line tool to decode Heroes of the Storm replay files into Python data structures.

The tool is available as a [PyPI Package](https://pypi.org/project/heroprotocol/) or as source code.

Currently heroprotocol can decode these structures and events:

* Replay header
* Game details
* Replay init data
* Game events
* Message events
* Tracker events

heroprotocol can be used as a base-build-specific library to decode binary blobs, or it can be run as a standalone tool
to pretty print information from supported replay files.

Note that heroprotocol does not expose game balance information or provide any kind of high level analysis of replays;
it's meant to be just the first tool in the chain for your data mining application.

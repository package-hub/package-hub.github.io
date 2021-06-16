---
title: PettingZoo
categories: ['python']
---
## [PettingZoo](https://github.com/PettingZoo-Team/PettingZoo)

### Gym for multi-agent reinforcement learning


PettingZoo includes the following families of environments:

* [Atari](https://www.pettingzoo.ml/atari): Multi-player Atari 2600 games (cooperative, competitive and mixed sum)
* [Butterfly](https://www.pettingzoo.ml/butterfly): Cooperative graphical games developed by us, requiring a high degree of coordination
* [Classic](https://www.pettingzoo.ml/classic): Classical games including card games, board games, etc.
* [MAgent](https://www.pettingzoo.ml/magent): Configurable environments with massive numbers of particle agents, originally from https://github.com/geek-ai/MAgent
* [MPE](https://www.pettingzoo.ml/mpe): A set of simple nongraphical communication tasks, originally from https://github.com/openai/multiagent-particle-envs
* [SISL](https://www.pettingzoo.ml/sisl): 3 cooperative environments, originally from https://github.com/sisl/MADRL

To install the pettingzoo base library, use `pip install pettingzoo`.

This does not include dependencies for all families of environments (there's a massive number, and some can be problematic to install on certain systems). You can install these dependencies for one family like `pip install pettingzoo[atari]` or use `pip install pettingzoo[all]` to install all dependencies.

We support Python 3.6, 3.7, 3.8 and 3.9 on Linux and macOS. We will accept PRs related to Windows, but do not officially support it.

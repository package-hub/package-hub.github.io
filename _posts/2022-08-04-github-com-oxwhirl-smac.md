---
title: smac
categories: ['python', 'starcraft-ii', 'reinforcement-learning']
---
## [smac](https://github.com/oxwhirl/smac)

### SMAC: The StarCraft Multi-Agent Challenge


[SMAC](https://github.com/oxwhirl/smac) is [WhiRL](http://whirl.cs.ox.ac.uk)'s environment for research in the field of collaborative multi-agent reinforcement learning (MARL) based on [Blizzard](http://blizzard.com)'s [StarCraft II](https://en.wikipedia.org/wiki/StarCraft_II:_Wings_of_Liberty) RTS game. SMAC makes use of Blizzard's [StarCraft II Machine Learning API](https://github.com/Blizzard/s2client-proto) and [DeepMind](https://deepmind.com)'s [PySC2](https://github.com/deepmind/pysc2) to provide a convenient interface for autonomous agents to interact with StarCraft II, getting observations and performing actions. Unlike the [PySC2](https://github.com/deepmind/pysc2), SMAC concentrates on *decentralised micromanagement* scenarios, where each unit of the game is controlled by an individual RL agent.


Please refer to the accompanying [paper](https://arxiv.org/abs/1902.04043) and [blogpost](http://whirl.cs.ox.ac.uk/blog/smac) for the outline of our motivation for using SMAC as a testbed for MARL research and the initial experimental results.

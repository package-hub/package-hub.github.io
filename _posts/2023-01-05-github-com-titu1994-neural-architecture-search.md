---
title: neural-architecture-search
categories: ['python', 'neural-architecture-search', 'keras']
---
## [neural-architecture-search](https://github.com/titu1994/neural-architecture-search)

### Basic implementation of [Neural Architecture Search with Reinforcement Learning](https://arxiv.org/abs/1611.01578).


Basic implementation of Controller RNN from [Neural Architecture Search with Reinforcement Learning](https://arxiv.org/abs/1611.01578) and [Learning Transferable Architectures for Scalable Image Recognition](https://arxiv.org/abs/1707.07012).

- Uses Keras to define and train children / generated networks, which are defined in Tensorflow by the Controller RNN.
- Define a state space by using `StateSpace`, a manager which adds states and handles communication between the Controller RNN and the user.
- `Controller` manages the training and evaluation of the Controller RNN
- `NetworkManager` handles the training and reward computation of a Keras model

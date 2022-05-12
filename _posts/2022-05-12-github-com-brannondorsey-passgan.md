---
title: PassGAN
categories: ['python', 'password-cracking', 'machine-learning']
---
## [PassGAN](https://github.com/brannondorsey/PassGAN)

### A Deep Learning Approach for Password Guessing (https://arxiv.org/abs/1709.00440)


This repository contains code for the [_PassGAN: A Deep Learning Approach for Password Guessing_](https://arxiv.org/abs/1709.00440) paper. 

The model from PassGAN is taken from [_Improved Training of Wasserstein GANs_](https://arxiv.org/abs/1704.00028) and it is assumed that the authors of PassGAN used the [improved_wgan_training](https://github.com/igul222/improved_wgan_training) tensorflow implementation in their work. For this reason, I have modified that reference implementation in this repository to make it easy to train (`train.py`) and sample (`sample.py`) from. This repo contributes:

- A command-line interface
- A pretrained PassGAN model trained on the RockYou dataset

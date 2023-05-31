---
title: gputil
categories: ['python']
---
## [gputil](https://github.com/anderskm/gputil)

### A Python module for getting the GPU status from NVIDA GPUs using nvidia-smi programmically in Python

`GPUtil` is a Python module for getting the GPU status from NVIDA GPUs using `nvidia-smi`.
`GPUtil` locates all GPUs on the computer, determines their availablity and returns a ordered list of available GPUs.
Availablity is based upon the current memory consumption and load of each GPU.
The module is written with GPU selection for Deep Learning in mind, but it is not task/library specific and it can be applied to any task, where it may be useful to identify available GPUs.

**Table of Contents**

1. [Requirements](#requirements)
1. [Installation](#installation)
1. [Usage](#usage)
   1. [Main functions](#main-functions)
   1. [Helper functions](#helper-functions)
1. [Examples](#examples)
   1. [Select first available GPU in Caffe](#select-first-available-gpu-in-caffe)
   1. [Occupy only 1 GPU in TensorFlow](#occupy-only-1-gpu-in-tensorflow)
   1. [Monitor GPU in a separate thread](#monitor-gpu-in-a-separate-thread)
1. [License](#license)

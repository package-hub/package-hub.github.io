---
title: senet.pytorch
categories: ['python', 'senet', 'pytorch']
---
## [senet.pytorch](https://github.com/moskomule/senet.pytorch)

### PyTorch implementation of SENet


An implementation of SENet, proposed in **Squeeze-and-Excitation Networks** by Jie Hu, Li Shen and Gang Sun, who are the winners of ILSVRC 2017 classification competition.

Now SE-ResNet (18, 34, 50, 101, 152/20, 32) and SE-Inception-v3 are implemented.

* `python cifar.py` runs SE-ResNet20 with Cifar10 dataset.

* `python imagenet.py` and `python -m torch.distributed.launch --nproc_per_node=${NUM_GPUS} imagenet.py` run SE-ResNet50 with ImageNet(2012) dataset,
    + You need to prepare dataset by yourself in `~/.torch/data` or set an enviroment variable `IMAGENET_ROOT=${PATH_TO_YOUR_IMAGENET}`
    + First download files and then follow the [instruction](https://github.com/facebook/fb.resnet.torch/blob/master/INSTALL.md#download-the-imagenet-dataset).
    + The number of workers and some hyper parameters are fixed so check and change them if you need.
    + This script uses all GPUs available. To specify GPUs, use `CUDA_VISIBLE_DEVICES` variable. (e.g. `CUDA_VISIBLE_DEVICES=1,2` to use GPU 1 and 2)

For SE-Inception-v3, the input size is required to be 299x299 [as the original Inception](https://github.com/tensorflow/models/tree/master/inception).

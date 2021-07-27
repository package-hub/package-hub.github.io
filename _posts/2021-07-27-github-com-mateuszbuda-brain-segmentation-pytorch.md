---
title: brain-segmentation-pytorch
categories: ['python']
---
## [brain-segmentation-pytorch](https://github.com/mateuszbuda/brain-segmentation-pytorch)

### U-Net implementation in PyTorch for FLAIR abnormality segmentation in brain MRI


U-Net implementation in PyTorch for FLAIR abnormality segmentation in brain MRI based on a deep learning segmentation algorithm used in [Association of genomic subtypes of lower-grade gliomas with shape features automatically extracted by a deep learning algorithm](https://doi.org/10.1016/j.compbiomed.2019.05.002).

This repository is an all Python port of official MATLAB/Keras implementation in [brain-segmentation](https://github.com/mateuszbuda/brain-segmentation).
Weights for trained models are provided and can be used for inference or fine-tuning on a different dataset.
If you use code or weights shared in this repository, please consider citing:

```
@article{buda2019association,
  title={Association of genomic subtypes of lower-grade gliomas with shape features automatically extracted by a deep learning algorithm},
  author={Buda, Mateusz and Saha, Ashirbani and Mazurowski, Maciej A},
  journal={Computers in Biology and Medicine},
  volume={109},
  year={2019},
  publisher={Elsevier},
  doi={10.1016/j.compbiomed.2019.05.002}
}
```

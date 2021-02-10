---
title: BiSeNet
categories: ['python', 'bisenet', 'cityscapes']
---
## [BiSeNet](https://github.com/CoinCheung/BiSeNet)

### Add bisenetv2.  My implementation of BiSeNet


My implementation of [BiSeNetV1](https://arxiv.org/abs/1808.00897) and [BiSeNetV2](https://arxiv.org/abs/1808.00897).


The mIOU evaluation result of the models trained and evaluated on cityscapes train/val set is:
| none | ss | ssc | msf | mscf | fps(fp16/fp32) | link |
|------|:--:|:---:|:---:|:----:|:---:|:----:|
| bisenetv1 | 75.55 | 76.90 | 77.40 | 78.91 | 60/19 | [download](https://drive.google.com/file/d/140MBBAt49N1z1wsKueoFA6HB_QuYud8i/view?usp=sharing) |
| bisenetv2 | 74.12 | 74.18 | 75.89 | 75.87 | 50/16 | [download](https://drive.google.com/file/d/1qq38u9JT4pp1ubecGLTCHHtqwntH0FCY/view?usp=sharing) |

> Where **ss** means single scale evaluation, **ssc** means single scale crop evaluation, **msf** means multi-scale evaluation with flip augment, and **mscf** means multi-scale crop evaluation with flip evaluation. The eval scales of multi-scales evaluation are `[0.5, 0.75, 1.0, 1.25, 1.5, 1.75]`, and the crop size of crop evaluation is `[1024, 1024]`.

> The fps is tested in different way from the paper. For more information, please see [here](./tensorrt).

Note that the model has a big variance, which means that the results of training for many times would vary within a relatively big margin. For example, if you train bisenetv2 for many times, you will observe that the result of **ss** evaluation of bisenetv2 varies between 72.1-74.4. 


---
title: sentinel2-cloud-detector
categories: ['python', 'python-library', 'cloud-detector']
---
## [sentinel2-cloud-detector](https://github.com/sentinel-hub/sentinel2-cloud-detector)

### Sentinel Hub Cloud Detector for Sentinel-2 images in Python


**NOTE: s2cloudless masks are now available as a precomputed layer within Sentinel Hub. Check the [announcement blog post](https://medium.com/sentinel-hub/cloud-masks-at-your-service-6e5b2cb2ce8a) and [technical documentation](https://docs.sentinel-hub.com/api/latest/#/API/data_access?id=cloud-masks-and-cloud-probabilities).**

The **s2cloudless** Python package provides automated cloud detection in
Sentinel-2 imagery. The classification is based on a *single-scene pixel-based cloud detector*
developed by Sentinel Hub's research team and is described in more detail
[in this blog](https://medium.com/sentinel-hub/improving-cloud-detection-with-machine-learning-c09dc5d7cf13).

The **s2cloudless** algorithm was part of an international collaborative effort aimed at intercomparing cloud detection algorithms. The s2cloudless algorithm was validated together with 9 other algorithms on 4 different test datasets and in all cases found to be on the Pareto front. See [the paper](https://www.sciencedirect.com/science/article/pii/S0034425722001043?via%3Dihub)

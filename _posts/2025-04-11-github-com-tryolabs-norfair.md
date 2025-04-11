---
title: norfair
categories: ['python', 'tracking', 'tracking-algorithm']
---
## [norfair](https://github.com/tryolabs/norfair)

### Lightweight Python library for adding real-time multi-object tracking to any detector.


- Any detector expressing its detections as a series of `(x, y)` coordinates can be used with Norfair. This includes detectors performing tasks such as object or keypoint detection (see [examples](#examples--demos)).

- Modular. It can easily be inserted into complex video processing pipelines to add tracking to existing projects. At the same time, it is possible to build a video inference loop from scratch using just Norfair and a detector.

- Supports moving camera, re-identification with appearance embeddings, and n-dimensional object tracking (see [Advanced features](#advanced-features)).

- Norfair provides several predefined distance functions to compare tracked objects and detections. The distance functions can also be defined by the user, enabling the implementation of different tracking strategies.

- Fast. The only thing bounding inference speed will be the detection network feeding detections to Norfair.

Norfair is built, used and maintained by [Tryolabs](https://tryolabs.com).

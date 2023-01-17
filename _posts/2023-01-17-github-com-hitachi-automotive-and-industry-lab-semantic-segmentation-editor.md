---
title: semantic-segmentation-editor
categories: ['javascript', 'labeling-tool', 'machine-learning']
---
## [semantic-segmentation-editor](https://github.com/Hitachi-Automotive-And-Industry-Lab/semantic-segmentation-editor)

### Web labeling tool for bitmap images and point clouds


A web based labeling tool for creating AI training data sets (2D and 3D).
The tool has been developed in the context of autonomous driving research.
It supports images (.jpg or .png) and point clouds (.pcd).
It is a [Meteor](http://www.meteor.com) app developed with [React](http://reactjs.org),
[Paper.js](http://paperjs.org/) and [three.js](https://threejs.org/).

**Latest changes**
 - **Version 1.5:** Provide a Docker image and update to Meteor 1.10 
 - **Version 1.4:** Support for RGB pointclouds (thanks @Gekk0r)
 - **Version 1.3:** Improve pointcloud labeling: bug fixes and performance improvement (labeling a 1M pointcloud is now possible)
 - **Version 1.2.2:** Breaking change: exported point cloud coordinates are no longer translated (thanks @hetzge)
 - **Version 1.2.0:** Support for binary and binary compressed point clouds (thanks @CecilHarvey)
 

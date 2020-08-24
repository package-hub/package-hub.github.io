---
title: visual_odometry
categories: ['python']
---
## [visual_odometry](https://github.com/Transportation-Inspection/visual_odometry)

### visual odometry in python scripts


The Python Monocular Visual Odometry (py-MVO) project used the [monoVO-python](https://github.com/uoip/monoVO-python) repository, which is 
a Python implementation of the [mono-vo](https://github.com/avisingh599/mono-vo) repository, as its backbone.
An in depth explanation of the fundamental workings of the algorithm maybe found in [Avi Sinhg's report](http://avisingh599.github.io/assets/ugp2-report.pdf). 
The monoVO-python code was optimized in order to make it more robust, using advance methods in order to obtain a 
higher level of accuracy.This [report]() provides information about the optimizations done to the monoVO-python code. The GPS data in the images EXIF file can also be used to formulate a GPS trajectory in order to compare with the results of Visual Odometry(VO) trajectory. A merge between the GPS and VO trajectories is also possible in order to get an even more reliable motion estimation. The [KITTI](http://www.cvlibs.net/datasets/kitti/eval_odometry.php) dataset was used for testing our methods and new implementations, since they offer accurate camera projection matrices, undistorted images, and reliable ground truth data. 

*The GPS trajectories can only be done with GPS-tagged images(GPS data inside the image's EXIF file).

---
title: python_motion_planning
categories: ['python', 'a-star', 'd-star']
---
## [python_motion_planning](https://github.com/ai-winter/python_motion_planning)

### Motion planning(Path Planning and Trajectory Planning/Tracking) of AGV/AMR：python implementation of Dijkstra, A*, JPS, D*, LPA*, D* Lite, (Lazy)Theta*, RRT, RRT*, RRT-Connect, Informed RRT*, Voronoi, PID, DWA, APF, LQR, MPC, RPP, Bezier, Dubins etc.


`Python Motion Planning` repository provides the implementations of common `Motion planning` algorithms, including path planners on N-D grid, controllers for path-tracking, trajectory optimizers, a visualizer based on matplotlib and a toy physical simulator to test controllers.

`Motion planning` plans the state sequence of the robot without conflict between the start and goal. 

`Motion planning` mainly includes `Path planning` and `Trajectory planning`.

* `Path Planning`: It's based on path constraints (such as obstacles), planning the optimal path sequence for the robot to travel without conflict between the start and goal.
* `Trajectory planning`: It plans the motion state to approach the global path based on kinematics, dynamics constraints and path sequence.

The theory analysis can be found at [motion-planning](https://blog.csdn.net/frigidwinter/category_11410243.html).

We also provide [ROS C++](https://github.com/ai-winter/ros_motion_planning) version and [Matlab](https://github.com/ai-winter/matlab_motion_planning) version.

**Your stars and forks are welcome!**

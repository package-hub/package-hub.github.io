---
title: black-hole
categories: ['javascript', 'simulation', 'webgl']
---
## [black-hole](https://github.com/oseiskar/black-hole)

### WebGL simulation of a Schwarzschild black hole


In this simulation, the light ray paths are computed by integrating an ODE describing the Schwarzschild geodesics using GLSL on the GPU, leveraging WebGL and [three.js](http://threejs.org). This should result to a fairly physically accurate gravitational lensing effect. Various other relativistic effects have also been added and their contributions can be toggled from the GUI.
The simulation has normalized units such that the Schwarzschild radius of the black hole is one and the speed of light is one length unit per second (unless changed using the "time scale" parameter).

See **[this page](https://oseiskar.github.io/black-hole/docs/physics.html)** ([PDF version](https://oseiskar.github.io/black-hole/docs/physics.pdf)) for a more detailed description of the physics of the simulation.

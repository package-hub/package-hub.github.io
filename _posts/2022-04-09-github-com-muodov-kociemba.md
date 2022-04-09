---
title: kociemba
categories: ['python']
---
## [kociemba](https://github.com/muodov/kociemba)

### A pure Python and pure C ports of Kociemba's algorithm for solving Rubik's cube

This Python package contains two equivalent implementations (in C and Python) of Herbert Kociemba's two-phase algorithm for solving Rubik's Cube.
Original Java implementation can be found here: http://kociemba.org/download.htm.

These ports are pretty straightforward (not to say dumb) and most probably can be optimized. But they have been extensively tested in our Rubik's cube solving machines ([FAC System Solver](https://blog.zok.pw/hacking/2015/08/18/fac-rubik-solver/) and [Meccano Rubik's Shrine](http://blog.zok.pw/hacking/2016/08/12/meccano-rubiks-shrine/)), so be confident the algorithm is working.

**NB** please note that two-phase algorithm does not guarantee that the produced solution is the shortest possible. Instead, it gives you a "good enough" solution in a very short time. You can implement additional checks on top of this library, for example, to not produce any moves if the cube is already solved. 

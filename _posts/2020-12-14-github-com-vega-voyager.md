---
title: voyager
categories: ['typescript']
---
## [voyager](https://github.com/vega/voyager)

### Visualization Tool for Data Exploration


Voyager 2 is a data exploration tool that blends manual and automated chart specification. Voyager 2 combines PoleStar, a traditional chart specification tool inspired by Tableau and Polaris (research project that led to the birth of Tableau), with two partial chart specification interfaces: (1) *wildcards* let users specify multiple charts in parallel,(2) *related views* suggest visualizations relevant to the currently specified chart.  With Voyager 2, we aim to  help analysts engage in both breadth-oriented exploration and depth-oriented question answering.

For a quick overview of Voyager, see our [preview video](https://vimeo.com/199084718), or [a 4-minute demo in our Vega-Lite talk at OpenVisConf](https://youtu.be/9uaHRWj04D4?t=1462), or watch our [research talk at CHI 2017](https://www.youtube.com/watch?v=nrnN0l3rjdk).
For more information about our design, please read our [CHI paper](http://idl.cs.washington.edu/papers/voyager2) and other related papers ([1](http://idl.cs.washington.edu/papers/compassql/), [2](http://idl.cs.washington.edu/papers/voyager/), [3](http://idl.cs.washington.edu/papers/vega-lite/)).

Voyager 2 can be used from [JupyterLab](https://github.com/jupyterlab/jupyterlab) via the [JupyterLab extension for Voyager](https://github.com/altair-viz/jupyterlab_voyager). The [DataVoyager.jl](https://github.com/queryverse/DataVoyager.jl) package integrates Voyager 2 into the [Julia programming language](https://julialang.org/).

**WARNING**:

This repository now hosts an alpha version of the migration of Voyager 2 to a React/Redux application.
Older versions of Voyager built in AngularJS at the following URL.

- The __Voyager 2__ visualization tool, which blends manual and automated chart specification – demo at http://vega.github.io/voyager2 and source code at https://github.com/vega/voyager2
- The __Voyager 1__ visualization browser -- demo at http://uwdata.github.io/voyager and source code in the `vy1` branch of this repository.

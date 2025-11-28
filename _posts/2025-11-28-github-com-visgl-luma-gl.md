---
title: luma.gl
categories: ['typescript', 'webgl', 'data-visualization']
---
## [luma.gl](https://github.com/visgl/luma.gl)

### High-performance Toolkit for WebGL-based Data Visualization


luma.gl is a GPU toolkit for the Web focused primarily on data visualization use cases. luma.gl aims to provide support for GPU programmers that need to work directly with shaders and want a low abstraction API that remains conceptually close to the WebGPU and WebGL APIs. Some features of luma.gl include:

- A robust GLSL shader module system.
- A convenient object-oriented API wrapping most WebGL objects
- Higher-level engine constructs to manage the animation loop, drawing and resource management

Unlike other common WebGL APIs, the developer can choose to use the parts of luma.gl that support their use case and leave the others behind.

While generic enough to be used for general 3D rendering, luma.gl's mandate is primarily to support GPU needs of data visualization frameworks in the vis.gl suite, such as:

- [kepler.gl](https://github.com/keplergl/kepler.gl) a powerful open source geospatial analysis tool for large-scale data sets
- [deck.gl](https://github.com/visgl/deck.gl) a WebGL-powered framework for visual exploratory data analysis of large data sets
- [streetscape.gl](https://github.com/uber/streetscape.gl) A visualization toolkit for autonomy and robotics data encoded in the XVIZ protocol

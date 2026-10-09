---
title: Stop-motion-OBJ
categories: ['python', 'blender', 'animation']
---
## [Stop-motion-OBJ](https://github.com/neverhood311/Stop-motion-OBJ)

### A Blender add-on for importing a sequence of OBJ meshes as frames

[Tutorial](https://github.com/neverhood311/Stop-motion-OBJ/wiki#quick-start) | [Forum](https://blenderartists.org/t/stop-motion-obj-obj-stl-ply-sequence-importer/670105) | [Documentation](https://github.com/neverhood311/Stop-motion-OBJ/wiki) | [How to Support](#how-to-support)

Stop Motion OBJ is a tool that lets you import a sequence of mesh files (.obj, .stl, .ply, .x3d, or .wrl), play them back in real time, then render them out to an animation. Each mesh may have a different vertex count, poly count, and even different UVs. This is especially useful for importing fluid simulations, for visualization of scientific data, and for rendering of 4D scan data.

Once a sequence is imported, you may perform many of the same operations on the sequence that you would on a single mesh. Many of the Object Modifiers work on the entire mesh sequence. Mesh sequences may be rendered in both Cycles and Eevee.

Stop Motion OBJ is able to import very complex mesh sequences that cannot fit in memory. Using [Streaming sequences](https://github.com/neverhood311/Stop-motion-OBJ/wiki#streaming), you can specify how many meshes to keep in memory at any given time and Stop Motion OBJ will automatically load and/or remove meshes so you don’t run out of memory.


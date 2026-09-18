---
title: numpy-stl
categories: ['python', 'python3', 'python2']
---
## [numpy-stl](https://github.com/wolph/numpy-stl)

### Simple library to make working with STL files (and 3D objects in general) fast and easy.


```bash
pip install numpy-stl
```

```python
from stl import mesh

# Load an STL file (auto-detects binary/ASCII)
your_mesh = mesh.Mesh.from_file('model.stl')

# Inspect
print(f'{len(your_mesh)} triangles')
print(f'Bounding box: {your_mesh.min_} to {your_mesh.max_}')

# Save
your_mesh.save('output.stl')
```

---
title: openMotor
categories: ['python', 'rockets', 'science']
---
## [openMotor](https://github.com/reilleya/openMotor)

### An open-source internal ballistics simulator for rocket motor experimenters

openMotor uses Qt Designer to design the GUI, which generates `.ui` files describing the user interface. 
We use `pyuic5` to compile these files into Python source code which is then included in the program as ordinary source code.

Because these autogenerated files are not committed to the source tree, you must build them by running:
```
$ python setup.py build_ui
```
Note that if you make changes to the UI using the `.ui` forms, you must re-build using the same command.

Once everything is set up, you can start openMotor by running: `python main.py`
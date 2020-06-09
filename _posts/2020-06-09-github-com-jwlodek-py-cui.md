---
title: py_cui
categories: ['python', 'cui', 'tui']
---
## [py_cui](https://github.com/jwlodek/py_cui)

### A python library for intuitively creating CUI/TUI interfaces with widgets, inspired by gocui.


`py_cui` is a python library meant to simplify writing command line user interfaces in python. It relies on the `curses` module, which is traditionally a unix-specific python module, however, you may use the [windows-curses](https://github.com/zephyrproject-rtos/windows-curses) module to run `py_cui` on windows.

The main advantage `py_cui` has over typical text-based user interface builders is that it relies on widgets and a grid layout manager like most traditional graphical user interfaces. You may define a grid size, and then drop predefined widgets onto it into specific grid locations. Widgets can also be stretched accross multiple grid rows and columns. If you've ever made a Tkinter GUI, you will feel right at home.

If you would like to contribute, feel free to make an issue or pull request after reading through the `CONTRIBUTING.md` file.

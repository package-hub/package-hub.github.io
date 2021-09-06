---
title: python-adb
categories: ['python']
---
## [python-adb](https://github.com/google/python-adb)

### Python ADB + Fastboot implementation


Install using pip:

```sh
pip install adb
```

Once installed, two new binaries should be available: `pyadb` and `pyfastboot`.

```sh
pyadb devices
pyadb shell ls /sdcard
```

Running `./make_tools.py` creates two files: `adb.zip` and `fastboot.zip`. They
can be run similar to native `adb` and `fastboot` via the python interpreter:

    python adb.zip devices
    python adb.zip shell ls /sdcard

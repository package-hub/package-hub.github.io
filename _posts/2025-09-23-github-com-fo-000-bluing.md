---
title: bluing
categories: ['python', 'bluetooth', 'scanner']
---
## [bluing](https://github.com/fO-000/bluing)

### An intelligence gathering tool for hacking Bluetooth


Bluing partially depend on [BlueZ](http://www.bluez.org/), the official Linux Bluetooth protocol stack. So it only supports running on Linux. The following command is used to install dependencies:

```sh
sudo apt install python3-pip python3-dev libcairo2-dev libgirepository1.0-dev \
                 libbluetooth-dev libdbus-1-dev bluez-tools python3-cairo-dev \
                 rfkill meson patchelf bluez ubertooth adb python-is-python3
```

Currently, bluing is distributed via [PyPI](https://pypi.org/project/bluing/) and **only supports Python 3.10**. The following is an installation command:

```sh
sudo pip3.10 install bluing
```

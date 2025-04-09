---
title: gatt-python
categories: ['python', 'bluetooth', 'bluetooth-low-energy']
---
## [gatt-python](https://github.com/getsenic/gatt-python)

### Bluetooth GATT SDK for Python

The Bluetooth GATT SDK for Python helps you implementing and communicating with any Bluetooth Low Energy device that has a GATT profile. As of now it supports:

* Discovering nearby Bluetooth Low Energy devices
* Connecting and disconnecting devices
* Implementing your custom GATT profile
* Accessing all GATT services
* Accessing all GATT characteristics
* Reading characteristic values
* Writing characteristic values
* Subscribing for characteristic value change notifications

Currently Linux is the only platform supported by this library. Unlike other libraries this GATT SDK is based directly on the mature and stable D-Bus API of BlueZ to interact with Bluetooth devices. In the future we would like to make this library platform-independent by integrating with more Bluetooth APIs of other operating systems such as MacOS and Windows.

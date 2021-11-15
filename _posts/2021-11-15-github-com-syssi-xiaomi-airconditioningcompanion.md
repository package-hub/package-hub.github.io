---
title: xiaomi_airconditioningcompanion
categories: ['python', 'xiaomi', 'acpartner']
---
## [xiaomi_airconditioningcompanion](https://github.com/syssi/xiaomi_airconditioningcompanion)

### Xiaomi Mi and Aqara Air Conditioning Companion integration for Home Assistant


This is a custom component for home assistant to integrate the Xiaomi Mi and Aqara Air Conditioning Companion:

| Model ID          | Model number | Product name                            | Shape    |
|-------------------|--------------|-----------------------------------------|----------|
| `acpartner.v1`    | KTBL01LM     | Aqara Air Conditioning Companion        | square   |
| `acaprtner.v2`    | KTBL02LM     | Xiaomi Mi Air Conditioner Companion     | round    |
| `acpartner.v3`    | KTBL11LM     | Aqara Air Conditioning Companion        | square   |

Unsupported devices: `lumi.acpartner.mcn02`

Please follow the instructions on [Retrieving the Access Token](https://www.home-assistant.io/components/vacuum.xiaomi_miio/#retrieving-the-access-token) to get the API token to use in the configuration.yaml file.

Credits: Thanks to [Rytilahti](https://github.com/rytilahti/python-miio) for all the work.

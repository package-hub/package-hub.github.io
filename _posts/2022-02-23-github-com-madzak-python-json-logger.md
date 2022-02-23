---
title: python-json-logger
categories: ['python', 'logging']
---
## [python-json-logger](https://github.com/madzak/python-json-logger)

### Json Formatter for the standard python logger


Json outputs are provided by the JsonFormatter logging formatter. You can add the custom formatter like below:

**Please note: version 0.1.0 has changed the import structure, please update to the following example for proper importing**

```python
    import logging
    from pythonjsonlogger import jsonlogger

    logger = logging.getLogger()

    logHandler = logging.StreamHandler()
    formatter = jsonlogger.JsonFormatter()
    logHandler.setFormatter(formatter)
    logger.addHandler(logHandler)
```

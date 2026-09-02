---
title: huobi_Python
categories: ['python', 'huobi', 'cryptocurrency']
---
## [huobi_Python](https://github.com/HuobiRDCenter/huobi_Python)

### Python SDK for Huobi Spot API


This is Huobi Python SDK v3, you can import to your python project and use this SDK to query all market data, trading
and manage your account. The SDK supports RESTful API invoking, and concurrently subscribing the market, account and
order update from the Websocket connection.

If you already use SDK v1 or v2, it is strongly suggested migrate to v3 as we refactor the implementation to make it
simpler and easy to maintain. The SDK v3 is completely consistent with the API documentation of the new HTX open
platform. Compared to SDK versions v1 and v2, due to changes in parameters of many interfaces, in order to match the
latest interface parameter situation, v3 version has made adjustments to parameters of more than 80 interfaces to ensure
that requests can be correctly initiated and accurate response data can be obtained. Meanwhile, the v3 version has added
over 130 new interfaces available for use, greatly expanding the number of available interfaces. We will stop the
maintenance of v2 in the near future. Please refer to the instruction on how to migrate v1 or v2 to v3 in
section [Migrate from v1 or v2](#Migrate-from-v1-or-v2)

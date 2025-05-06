---
title: PySocks
categories: ['python', 'proxy', 'socks-proxy']
---
## [PySocks](https://github.com/Anorov/PySocks)

### A SOCKS proxy client and wrapper for Python.


```python
import socks

s = socks.socksocket() # Same API as socket.socket in the standard lib

s.set_proxy(socks.SOCKS5, "localhost") # SOCKS4 and SOCKS5 use port 1080 by default
# Or
s.set_proxy(socks.SOCKS4, "localhost", 4444)
# Or
s.set_proxy(socks.HTTP, "5.5.5.5", 8888)

# Can be treated like a regular socket object
s.connect(("www.somesite.com", 80))
s.sendall("GET / HTTP/1.1 ...")
print(s.recv(4096))
```

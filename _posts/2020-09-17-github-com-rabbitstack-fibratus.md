---
title: fibratus
categories: ['python', 'windows', 'windows-kernel']
---
## [fibratus](https://github.com/rabbitstack/fibratus)

### Tool for exploration and tracing of the Windows kernel

[Download the latest release](https://github.com/rabbitstack/fibratus/releases/download/v0.7.2/fibratus-0.7.2.exe) (Windows installer). The changelog and older releases can be found [here](https://github.com/rabbitstack/fibratus/releases).

Alternatively, you can get **fibratus** from PyPI.

1. Install the dependencies
  * [Download](https://www.python.org/ftp/python/3.4.0/python-3.4.0.amd64.msi) and install Python 3.4.
  * Install Visual Studio 2015 (you'll only need the Visual C compiler to build the `kstreamc` extension). Make sure to export the `VS100COMNTOOLS` environment variable so it points to `%VS140COMNTOOLS%`. 
  * Get **Cython**: `pip install Cython >=0.23.4`.
2. Install **fibratus** via the pip package manager:

```bash
pip install fibratus
```
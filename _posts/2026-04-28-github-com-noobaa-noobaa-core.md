---
title: noobaa-core
categories: ['javascript', 'noobaa', 'hybrid']
---
## [noobaa-core](https://github.com/noobaa/noobaa-core)

### Cutting edge S3 server stack


To deploy NooBaa, we recommend using NooBaa CLI.
Follow the instructions in https://github.com/noobaa/noobaa-operator#noobaa-operator 

Once NooBaa CLI installed, simply Install the operator and noobaa with: 
```
./noobaa install
```
The install output includes S3 service endpoint and credentials, as well as web management console address with credentials.

Getting this information is always available with: 
```
./noobaa status
```
Remove NooBaa deployment can be done with: 
```
./noobaa uninstall
```

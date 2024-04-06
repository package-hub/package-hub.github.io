---
title: syncClient
categories: ['java', 'canal', 'elasticsearch']
---
## [syncClient](https://github.com/sasou/syncClient)

### syncClient，数据实时同步中间件（同步mysql到kafka、redis、elasticsearch、httpmq）！


>   syncClient，数据实时同步中间件（同步mysql到kafka、redis、elasticsearch、httpmq）！

 本项目使用canal，将mysql的表数据实时同步到kafka、redis、elasticsearch、httpmq；  
 
 基本原理：    
 canal解析binlog的数据，由syncClient订阅，然后实时推送到kafka或者redis、elasticsearch、httpmq、ssdb；如果kafka、redis、es、httpmq服务异常，syncClient会回滚操作；canal、kafka、redis、es、httpmq的异常退出，都不会影响数据的传输；


---

**目录：**  
bin：已编译二进制项目，可以直接使用；  
src：源代码；  

---

**配置说明：**

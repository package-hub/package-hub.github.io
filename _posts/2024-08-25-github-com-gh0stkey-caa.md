---
title: CaA
categories: ['java', 'burpsuite', 'bounty-hunters']
---
## [CaA](https://github.com/gh0stkey/CaA)

### CaA - Collector and Analyzer, Insight into information, exploring with intelligence in a thousand ways.


**CaA**是一款**网络安全（漏洞挖掘）领域**下的辅助型项目，收集HTTP协议报文中的参数、路径、文件、参数值等信息，并统计出现的频次，从而帮助用户构建出具有实战应用价值的Fuzzing字典。除此之外CaA可以生成各类HTTP请求提供给BurpSuite Intruder用于Fuzzing工作。

**CaA**的设计思想来源于Web Fuzzing技术，皆在帮助用户发现隐藏的漏洞面，通过对信息的收集分析整理，让用户真正意义上的实现**数据挖掘**。

**思路来源**:

1. [我的Web应用安全模糊测试之路](https://gh0st.cn/archives/2018-07-25/1)
2. [WebFuzzing方法和漏洞案例总结](https://gh0st.cn/archives/2019-11-11/1)

**所获荣誉**:

1. [入选2024年KCon兵器谱](https://mp.weixin.qq.com/s/H7QLItrMw-aaqL2-CAvBTg)

**注意事项**:

1. CaA采用`Montoya API`进行开发，需要满足BurpSuite版本（>=2023.12.1）才能使用。

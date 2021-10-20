---
title: DeepTrade
categories: ['python', 'lstm', 'neural-network']
---
## [DeepTrade](https://github.com/happynoom/DeepTrade)

### A LSTM model using Risk Estimation loss function for stock trades in market

    
首先说一下收益率。离开收益率去谈算法都是在耍流氓。项目利用最近700个交易日做验证，700个交易日之前的所有交易数据作为训练集，也就是说，确保不存在验证信息的泄漏。在上证综合指数上最近700个交易日的复利收益率为200%以上，同期上证指数上涨约50%。在深圳成指近700个交易日的复利收益率也在200%左右。收益为验证收益，并非实际交易数据，且为复利计算，没有扣除交易印花税和佣金。（提醒：项目仅用于学术交流，投资有风险，损失需自负。）


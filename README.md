# bnhy
币安事件合约分析，合约分析，币圈合约分析

官网【币圈工具站】bqbot.cn

在线合约分析地址：https://bqbot.cn/jms.html

客户端版事件合约分析：https://bqbot.cn/sites/%e5%90%88%e7%ba%a6%e5%88%86%e6%9e%90%e5%b7%a5%e5%85%b7.html

网页版合约分析效果如图：

![e02ede358d27a9867aa7ae2ff1a4280](https://github.com/user-attachments/assets/ae12daa3-4469-4400-8453-316b8e24a4f1)

1.基于机器学习模型完善权重指标（根据历史的指标，历史的实际涨跌答案，去反推权重数据，优化权重数据，再把这个机器学习的权重模型用户实时预测）

2.根据机器学习权重模型数据完善实时数据指标权重

3.双重混合策略，能根据信号强弱给出不同的策略，例如（信号弱时是建议观望，信号强会给出建议入场点位及止盈止损点位）

4.加入多数表决算法（应对单边行情）

5.回测胜率提升至60%以上

6.增加了（压力位支撑位）作为回测参考指标

7.更新了回测数据逻辑，根据选择周期进行回测数据量计算，比如选择10分钟周期，那么500条K线的回测数据反而会影响指标的真实状态。

这里是根据不同的周期，设置了不同的回测数据量
10分钟K线30~60根
1小时K线20~40根……….

8.加入了成交量过滤，更加重视伴随大成交量的高低点






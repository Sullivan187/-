# -基于李宏毅老师的机器学习课程作业的python实现

## homework1
### hw1任务:用梯度下降法预测PM2.5值
### train -- 训练数据
### test -- 测试数据
### ans -- 标准答案
### hw1_preprocess -- 数据处理代码部分
### hw1_model -- 建模部分

#### 训练集中包含一年中，某地区每个月前20天，每个一小时对包括PM2.5（label)在内的18个指标的观测值。测试集中每个ID代表在每个月后10天内的某个时间点，测试集中拥有该时间点的前9个时间点（如ID:0表示n时，则测试数据最后一列表示n-1时的数据，最后第二列表示n-2时的数据）的18个指标的观测值，需要预测该时间点的PM2.5数值。以均方误差衡量预测结果。

# 机器学习的定义

## TPE

概念解析：

​	两个算法

## 组成

- 数据
  - 从数据到特征
  - 特征选择
  - 获取数据集
    - 网络数据源
    - Artificial Data Synthesis人工数据构造
  - 加载
  - 探索
    - Matplotlib画图
    - Visualization可视化
  - 预处理
    - Vectorization向量化
    - Normalization标准化：使将所有特征的大小变成相同规模的，如果不同特征的值大小差别很大，小的特征的参数会快速收敛，大的则会慢，慢的将会使梯度下降收敛的慢。
      - Feature Scaling：除以标准差或(最大减最小)
      - Mean Normalization：减去平均值
- 模型
  - 构造
  - 训练
    - 最优化
      - 梯度下降
      - 优化器
    - Regularization正则化
  - 评估
  - 调参
  - 预测
- 部署
  - 预测
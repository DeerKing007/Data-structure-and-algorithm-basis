# Data-structure-and-algorithm-basis
数据结构和算法基础


### 人工智能
### 机器学习：
#### 监督学习:

    包括KNN算法（K近邻法k-nearest neighbors，KNN），线性回归，逻辑回归，朴素贝叶斯，决策树，随机森林，集成算法---adaboost，SVM。
    
`Knn`：近朱者赤近墨者黑 谁离我近就是谁 

`线性回归`：假设特征与目标变量之间的关系是线性的，求出最合适的参数  

`逻辑回归`：在线性回归之外套一层sigmod函数 

`朴素贝叶斯`：假设特征之间相互独立 根据贝叶斯公式进行计算在给定类别的情况下，出现某个特征的概率 谁大就是谁 

`决策树`：计算系统的信息熵  找到最大信息增益对应的一组最佳特征解 根据新的特征组合构建一棵树 根据树做预测

`随机森林`：多棵树并行做预测 将所有的树出现的结果做投票选举（少数服从多数） 

`集成算法 adaboost`：多个弱训练器串行 强迫后续训练器关注那些训练错误的数据，提高整体准确率

`SVM(支持向量机)`：利用核函数将低维度不可分的数据转化为高维度可分 找到一个最佳的分割位置（最大间隔）（超平面） 


#### 无监督学习

    包括：K-means，DBSCAN(基于密度的聚类算法)。
    
`means`：随意一个质心 计算每个点到该点的距离，划分形成一个簇 将每个簇的平均值作为新的质心  迭代

`DBSCAN(基于密度的聚类算法)`：根据给定的eps邻域和最小点数来找核心点 根据核心点找到对应的所有密度可达点 形成一个簇。

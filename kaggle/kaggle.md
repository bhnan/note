处理缺失值
knn（k 近邻算法），中位数，均值。
标记为新的特征（缺失特征）

### 特征转化
转化为正态

### 特征编码
##### 数字特征
##### 类别特征
	需要转换为数字特征
		1. 直接转化为数字（1，2，3……）
		2. one-hot（每个类单独作为特征）

### 特征选择









EDA (exploratory data analysis)
Feature engineering 
	缺失值处理（XGboost（基于决策树）自动处理缺失值）
	一般确保数据正态分布-boxcox（树模型不需要）
	text feature 处理（tf-idf encoding）
	feature interaction（树模型需要注意）
model tuning
model ensemble
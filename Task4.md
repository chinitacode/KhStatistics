### 线性回归(LR)  
概念：线性回归是利用数理统计中回归分析，来确定两种或两种以上变量间相互依赖的定量关系的一种统计分析方法，运用十分广泛。 其表达形式为y = w'x+e，e为误差服从均值为0的正态分布。 
回归分析中，只包括一个自变量和一个因变量，且二者的关系可用一条直线近似表示，这种回归分析称为一元线性回归分析。  
坐标系中若干点，找出一条直线y=mx+b，使这些点到该直线上同一横坐标的点的距离的平方和最小，求斜率m与截距b
每个点同回归直线的竖直距离

### 决定系数(coefficient of determination)  
概念：y的波动程度有多少百分比能被x的波动程度所描述

### 协方差  
概念：两随机变量离各自均值之积的期望值，同步程度决定协方差的大小  
[协方差](https://www.zhihu.com/question/20852004)

### 自由度的计算：  
n个数据点只有n-1个自由度，是因为根据n-1个数据点可以推算出第n个数据的信息（以存取的信息量为准）

### 列联表卡方检验  
自由度：（行数−1）∗（列数−1） （行数-1）*（列数-1）（行数−1）∗（列数−1）

### 方差分析  
分析数据总波动有多少是由于组内波动造成的，有多少是由于组外波动造成的  
SST:方差的分子部分，自由度为m∗n−1 m n-1m∗n−1  
SSB:组内平方和，概念为总波动是有多少因为组均值之间的波动，自由度为m-1  
SSW:组内平方和，不同分组内数据对组均值差的平方和之和，自由度为m∗(n−1) m(n-1)m∗(n−1)  
==》 SST的自由度=SSB自由度+SSW自由度

#前言

+The performance of these simple machine learning algorithms depends heavily on the **representation** of the data they are given.
在这里represetation，应该翻译成**表述/陈述/表达**比较合适，而不是表示。

+When designing features or algorithms for learning features, our goal is usually to separate the **factors of variation** that explain the observed data.
observed data: 观测数据/实验数据
factors of variation: 变化因子/变化系数

#第一章笔记

##线性组合 linear combination
  定义一个包含k个实数变量的集合  ,且假设已知一个k个实数权重集合  。我们定义  。s变量是对变量x的加权线性”混合”。因此，将s定义为变量的线性组合。
  
##线性相关/线性无关
  Formally, this kind of redundancy is known as linear dependence. A set of vectors is linearly independentif no vector in the set is a linear combination of the other vectors.

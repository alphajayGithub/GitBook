# basic - ML General

## Overview
![](http://5b0988e595225.cdn.sohucs.com/images/20180102/7585b43ca14b490b8d2df881cafb775e.jpeg)

> [AI、ML、统计学、数据挖掘之间有什么区别？](https://www.sohu.com/a/214247323_463989)

## Introduction
![](../resource/pic/2022-03-07_scikitLearnAlgorithms.jpeg)

Machine learning is essentially a form of applied statistics with increased emphasis on the use of computers to statistically estimate complicated functions and a decreased emphasison proving conﬁdence intervals around these functions;

we therefore present the two central approaches to statistics:

- frequentist estimators  频率派估计
- Bayesian inference.     贝叶斯推断

Most machine learning algorithms can be divided into the categories of
- supervised  learning    监督学习
- unsupervised  learning  非监督学习

Most deep learning algorithms are based on an optimization algorithm called

- stochastic gradient  随机梯度下降

## E T P definition

what do we mean by learning?

> A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E.

E -> Data Set； supervised/unsupervised

T -> Function Set/Model； 回归  分类  概率估计

P -> 准确率

O -> fitting

## P评估和O优化
梯度下降

正则化
## 数据预处理

## 数据可视化

[12个案例教你用Python玩转数据可视化 !其实可视化真的不难! - 知乎](https://zhuanlan.zhihu.com/p/62776660?from_voters_page=true)

# basic - 监督算法
## 线性回归

> [sklearn.linear_model.LinearRegression — scikit-learn 1.0.2 documentation](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html#sklearn.linear_model.LinearRegression)

See also
Ridge
Ridge regression addresses some of the problems of Ordinary Least Squares by imposing a penalty on the size of the coefficients with l2 regularization.

Lasso
The Lasso is a linear model that estimates sparse coefficients with l1 regularization.

ElasticNet
Elastic-Net is a linear regression model trained with both l1 and l2 -norm regularization of the coefficients.


线性回归可视化的重要性

> [什么是安斯库姆Anscombe四重奏？ - 知乎](https://www.zhihu.com/question/67493742)

> [论数据可视化的重要性--从安斯库姆.四重奏和数据恐龙说起 - 知乎](https://zhuanlan.zhihu.com/p/413824758)

多项式线性回归

> [Polynomial and Spline interpolation — scikit-learn 1.0.2 documentation](https://scikit-learn.org/stable/auto_examples/linear_model/plot_polynomial_interpolation.html#sphx-glr-auto-examples-linear-model-plot-polynomial-interpolation-py)

> [sklearn 的 PolynomialFeatures 的用法 - 李威威 - 博客园](https://www.cnblogs.com/liweiwei1419/p/9715702.html)


> [在B-spline中，如何理解knot和breakpoint？彼此之间联系和区别是什么？ - 知乎](https://www.zhihu.com/question/52199904)

> [分段多项式及样条 - szcf715 - 博客园](https://www.cnblogs.com/szcf715/p/7684877.html)   [样条拟合_百度百科](https://baike.baidu.com/item/%E6%A0%B7%E6%9D%A1%E6%8B%9F%E5%90%88/12726280?fr=aladdin)

## 逻辑回归


[sklearn中的逻辑回归 - banshaohuan - 博客园](https://www.cnblogs.com/banshaohuan/p/13308732.html#13-sklearn%E4%B8%AD%E7%9A%84%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92)


## 神经网络


### 3b1b 神经网络基础讲解

[【官方双语】深度学习之神经网络的结构 Part 1 ver 2.0_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1bx411M7Zx)

[【官方双语】深度学习之梯度下降法 Part 2 ver 0.9 beta_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1Ux411j7ri?spm_id_from=333.999.0.0)

[【官方双语】深度学习之反向传播算法 上/下 Part 3 ver 0.9 beta_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV16x411V7Qg)

## SVM支持向量机

## 朴素贝叶斯

###
判别模型与生成模型
![](https://pic3.zhimg.com/80/v2-8eeb29ce793a0660450d9fbddf237dfe_720w.jpg)
判别模型：学习得到条件概率分布 P(y|x) ，即在特征 x 出现的情况下标记 y 出现的概率。
生成模型：学习得到联合概率分布  P(x,y) ，即特征 x 和标记 y共同出现的概率，然后求条件概率分布。

常见判别模型：k近邻法、感知机、决策树、逻辑回归、线性回归、最大熵模型、支持向量机(SVM)、提升方法、条件随机场（CRF）
常见生成模型：朴素贝叶斯、隐马尔可夫（em算法）、受限玻耳兹曼机（Restricted Boltzmann Machine，RBM）、自编码器（Autoencoder，AE）、深层信念网络（Deep Belief Network，DBN）、高斯混合模型（GMM）

## 随机森林

[决策树、熵与最大熵 - 简书](https://www.jianshu.com/p/7da2f6f563f3)

[决策树 - 熵,信息增益的计算 - 苹果提子 - 博客园](https://www.cnblogs.com/okokok/p/6117333.html)
### XGBoost

[GBDT原理最通俗的解释 - 简书](https://www.jianshu.com/p/9b647afc1cdc)

[XGBoost算法原理 - 简书](https://www.jianshu.com/p/a31091d5acbb)


## KNN

[机器学习_基于距离的算法KNN与K-Means - 简书](https://www.jianshu.com/p/95a4bcff2198)


[K最近邻算法（KNN） - 简书](https://www.jianshu.com/p/a5ab25716c6b)

[深入浅出KNN算法（一） KNN算法原理 - zzzzMing - 博客园](https://www.cnblogs.com/listenfwind/p/10311496.html)

# basic - 无监督算法
## PCA

## LSA

## NMF

## LDA

## k-means

## 混合高斯分布

## LLE

## t-SNE

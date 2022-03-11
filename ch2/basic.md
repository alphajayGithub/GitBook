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
[sklearn.linear_model.LinearRegression — scikit-learn 1.0.2 documentation](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html#sklearn.linear_model.LinearRegression)

See also
Ridge
Ridge regression addresses some of the problems of Ordinary Least Squares by imposing a penalty on the size of the coefficients with l2 regularization.

Lasso
The Lasso is a linear model that estimates sparse coefficients with l1 regularization.

ElasticNet
Elastic-Net is a linear regression model trained with both l1 and l2 -norm regularization of the coefficients.



线性回归可视化的重要性
[什么是安斯库姆Anscombe四重奏？ - 知乎](https://www.zhihu.com/question/67493742)
[论数据可视化的重要性--从安斯库姆.四重奏和数据恐龙说起 - 知乎](https://zhuanlan.zhihu.com/p/413824758)

多项式线性回归
[Polynomial and Spline interpolation — scikit-learn 1.0.2 documentation](https://scikit-learn.org/stable/auto_examples/linear_model/plot_polynomial_interpolation.html#sphx-glr-auto-examples-linear-model-plot-polynomial-interpolation-py)

## 逻辑回归

## 神经网络


## SVM支持向量机

## 朴素贝叶斯

## 随机森林

## KNN


# basic - 无监督算法
## PCA

## LSA

## NMF

## LDA

## k-means

## 混合高斯分布

## LLE

## t-SNE

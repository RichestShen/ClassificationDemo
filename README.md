# 基于 `Python` 语言的分类算法案例分析

本仓库通过两个案例对流行的分类算法进行了分析。在 `cls_demo.ipynb` 中，利用鸢尾花数据集，选取逻辑回归、朴素贝叶斯和 XGBoost 算法对数据集进行分类，并通过混淆矩阵、数据可视化手段比较了结果。在 `weather_cls.ipynb` 中，选取公开天气数据集，就“明天是否下雨”利用XGBoost进行分类预测。

## 复现说明

环境：Windows 11 23H2, Intel Ultra 9 185H 2.30GHz, Python 3.11.3 + XGBoost 2.0.3

目录下的 `Boster.py` 是 `Python` 绘图的配置文件，主要用于中文支持、绘图设置调整等。

```python
from Boster import *
```

`weather_cls.csv` 为原始数据集，结果和图像存储于 `src` 目录下。

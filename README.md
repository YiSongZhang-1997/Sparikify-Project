# Sparkify Project - Udacity NanoDegree

## 项目动机
Sparkify是一家音乐软件公司，用户流失率是这家公司很关键的一个问题，如果能预测用户流失率就可以尽可能挽留用户。Udacity给我提供了这家公司关于用户的数据集，我要利用机器学习模型来预测用户流失情况，来找到影响用户流失率的关键特征。

## 依赖库
**pandas**

**numpy**

**pyspark**

**datetime**

**matplotlib**

## 文件说明

**mini_sparkify_event_data.json.zip**

项目用到的数据集压缩文件

**sparkify.ipynb**

数据集大小：128MB

_此文件详细记录了数据集的处理，分析，特征工程和模型建立_

清洗数据集

利用探索性数据分析找到相关的特征并可视化

利用特征工程正确提取需要的特征

建立三个机器学习分类模型对标签进行预测

对项目的总结

**问题修复**
1:Future Warning(cell: 24, 26, 29)
通过在第24，26，29个cell里面的concat方法里添加sort=False,来解决这一问题。



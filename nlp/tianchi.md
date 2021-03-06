[TOC]


# 文本挖掘-新闻自动分类

## 文本分类算法介绍

### 文本分类算法思路 

#### 文本分析常见需求

- 文本分类

- 文本打标签

- 情感分析

#### 文本分类算法

- 基于语义向量距离

将文本按着语义映射成高维向量特征，通过向量距离进行分类

- 基于关键词、主题

提取文本中的关键词、主题等信息; 然后通过这些词语的对照关系进行分类

## 基于主题的文本分类

思路： 具有相似主题的一类文本，属于相同的类别

### 基本流程

- 分词

- 过滤、词频统计

停用词、标点符号过滤; 统计每一篇文章中的词频

- 文本主题挖掘

词频统计中的三元组转为kv; 使用LDA生成每篇文章的主题

- 结果分析与评估

使用Kmeans进行聚类，并做结果分析 


[【玩转数据系列六】文本分析算法实现新闻自动分类](https://yq.aliyun.com/articles/59205)
[技术圈>【机器学习系列】文本挖掘-新闻自动分类](https://tianchi.aliyun.com/course/video?liveId=4050)


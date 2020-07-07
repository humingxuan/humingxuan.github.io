---

layout: post
title: Numpy|Pandas|Matplotlib学习笔记
date:   2020-07-07 15:28:39 +0800
categories: jekyll update
tags:
    - 数据处理
---

> 在基于python的机器学习、金融数据分析或是其他需要处理大量数据的技术方法中，一般都需要先对数据进行处理、清洗或者可视化等操作。
>
> 常用的数据处理的包为numpy、pandas和matplotlib，特此汇总记录相关函数以供查阅。

# numpy

## 列表转换为矩阵

```python
array =np.array([[1,2,3],[2,3,4]])  # 把列表转换成矩阵的方法 [][]是列表
print(array)
[[1 2 3]
 [2 3 4]]
```

## 查看形状

```python
print('shape:',array.shape)  # 查看形状
shape: (2, 3)
```

## 元素数量

`array.size`

## 生成矩阵

```python
np.zeros((3,4))
a = np.ones((3,4), dtype=np.int16)
a = np.empty((3,4))  # 全部为空的
a = np.arange(10,20,2)  # 生成有序的矩阵 起始值，终止值，步长
a = np.arange(12).reshape((3,4))  # 生成有序的三行四列
a = np.linspace(1, 10, 5)  # 生成线段
a = np.random.random((2,4)) # 随机矩阵
```






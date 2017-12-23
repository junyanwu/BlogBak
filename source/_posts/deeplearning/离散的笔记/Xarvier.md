---
title: Xavier初始化方法
date: 2017-12-21 11:05:23
categories: Deep Learning
tags:
- 离散的笔记
- DL&ML
---

## Xavier

- 此方法用于初始化参数

- 初始化方法：

  定义参数所在层的input_shape = n，output_shape = m，那么参数将以均匀分布的方式在以下在 $[-\sqrt{\frac{6}{m+n}}, \sqrt{\frac{6}{m+n}}]$ 的范围内进行初始化

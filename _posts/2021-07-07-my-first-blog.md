---
layout: post
title:  "First Blog"
date:   2021-07-07
categories: blog
author:     "YZ"
catalog: false
header-style: text
tags:
  - 日常
---

# 第一个博客 #
2021/7/7 14:25:08 

## java 5个常用的api包 ##
### java.lang包下的api ###
java常用基础包，在开发中会自动导入代码环境中

----------

1.基本数据类型/包装类
	（1）基本数据类型：byte（1字节）、short(2字节)、int(4字节）、long(8字节）、float(4字节)、double(8字节）、boolean(1字节)、char(2字节)
	（2）包装类：
	
* Byte：提供了将字节数据转换为其他类型的方法
* Short、Integer：将short、Integer转换为其他类型的方法
* Float、Double-isInfinite()：判断数字是否有趋近无穷大。isNaN()：判断浮点数据是否为有效数据
	（3）包装类与基本数据类型之间可以实现自动转换，即装箱和拆箱
    `装箱：自动将基本数据类型转换为其对应的包装类
拆箱：自动将包装类型转换为基本数据类型`

----------
2.数学运算类：Math

```
abs() ：获取绝对值函数.
acos()、asin()：反余弦、反正弦函数(以弧度为参数值PI结合运算).
cbrt()：立方根函数.
cos()、sin()：三角余弦、三角正弦函数(以弧度为参数值PI结合运算).
max()、min()：获取两个数值中的最大值或最小值.
log()、log10()：对数.
random()：获取随机数.
round()：四舍五入(获得整形值).
floor()：得到小于该数的最小整数.
ceil()：得到大于该数的最大整数.
sqrt()：平方根.
```

| 一个普通标题 | 一个普通标题 | 一个普通标题 |
| ------ | ------ | ------ |
| 短文本 | 中等文本 | 稍微长一点的文本 |
| 稍微长一点的文本 | 短文本 | 中等文本 |
---
title: transient变量有什么特点
date: 2018-08-28 17:46:54
tags: 
---

> transient的特点：

1、transient只能修饰成员变量，不能修饰局部变量、方法和类。

2、用户自定义的类变量，需要实现 Serilizable 接口才能被 transient 修饰。

3、被 transient 关键字修饰的变量不再能被序列化，一个静态变量不管是否被 transient 修饰，均不能被序列化。

4、一旦变量被 transient 修饰，变量将不再是对象持久化的一部分，该变量内容在序列化后无法获得访问。

具体实例可参考: [Java transient关键字使用小记](https://blog.csdn.net/lanxuezaipiao/article/details/16358677)
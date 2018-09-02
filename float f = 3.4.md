---
title: "float f = 3.4; 是否正确"
date: 2018-09-02 09:29:46
tags: 
---

答案：不正确。 

原因：要用强制类型转换

正确答案是  float f = (float)3.4 或 float f = 3.4f;

在java里面，没小数点的默认是int,有小数点的默认是 double; 

编译器自动向上转型，如 int 转成 long 系统自动转换没有问题，因为后者精度更高.

double 转成 float 就不能自动做了，所以后面的加上个 f;

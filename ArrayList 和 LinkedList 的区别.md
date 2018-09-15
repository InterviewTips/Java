---
title: ArrayList 和 LinkedList 的区别
date: 2018-09-11 17:20:14
tags: 
---

ArrayList 和 LinkedList 的大致区别如下:

1. ArrayList 是实现了基于动态数组的数据结构，LinkedList基于链表的数据结构。 
2. 对于随机访问 get 和 set，ArrayList 觉得优于 LinkedList，因为 LinkedList 要移动指针。 

3. 对于新增和删除操作 add 和 remove，LinedList 比较占优势，因为 ArrayList 要移动数据。

---

ArrayList 更适合读取数据，linkedList 更多的时候添加或删除数据。
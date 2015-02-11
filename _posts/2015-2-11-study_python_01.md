---
layout: post
title: 【Learn Python The Hard Way】学习笔记：格式化运算符 ‘%’
---
格式化运算符‘%’在exercise 5中是一个重点，虽然开篇讲的是变量，但是后面牵扯到变量的打印print，那么就无法避免将变量嵌入一个字符串的情况，此时，格式化运算符‘%’就派上了用场。例如书中的范例：
![_config.yml]({{ site.baseurl }}/images/ex_5_example_01.png)
但是在例子中，只有常用的两种格式化类型，d:有符号十进制整数，s:字符串(本质上是str())。以作者的习惯，必然会让我们去扒出所有的格式化类型，果不其然，在后面的练习中，作者出了一道题：Search online for all the Python format characters。
既然如此，那就扒吧，直奔python官网，在library中，找到了全部的格式化类型，并附上实例：

---
layout: post
title: "nil,Nil,NULL,NSNull的区别"
date: 2014-03-04 23:51:01 +0800
comments: true
categories:  
---

#1. nil
 nil指objective-C中对象的空指针;
 {% blockquote %}
 *什么是对象*
 对象是类的一个实例，是一个具体的事物.
 {% endblockquote %}
 
 ```
 NSString *str = nil; //str是类NSString的实例
 ```
 
#2.Nil
Nil指的是objective-C类的空指针;

```
Class aClass = Nil; //aClass是一个类的指针
```

#3.NULL
NULL表示集合对象中空值的对象；所有C/C++的指针都可以赋值为NULL;

```
int *point = NULL;
```

#4. NSNull
NSNull是个单例，是一个Objective-C对象，通常用于占位符,放在数组中可以用来区分其他元素.



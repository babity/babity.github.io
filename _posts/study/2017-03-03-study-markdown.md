---
layout: post
title: MarkDown 学习
description: 介绍一些简单的MarkDown语法
date: 2017-03-03
category: blog
---

# 我的Markdown

## 关于标题
```
#   一级标题  
##  二级标题  
### 三级标题  
```
以此类推，总共六级标题

---

## 关于字体

>用 \*\* 包含一段文本就是粗体，用 \* 包含一段文本就是斜体

 *斜体字Hale*  
 **粗体字Hale**  
 ***加粗加斜Hale***  
 ~~hello~~  
 ++hello++  
 ==hello==

---

## 关于列表


1. 无序列表
```  
  * 1
  * 2
```
  * 1
  * 2
2. 有序列表  
```  
  1. a
  2. b
```
  1. a
  2. b

***

## 关于引用与插入
引用 如果你需要引用一小段别处的句子，那么就要用引用的格式。
```
> 例如这样
```
> 例如这样

插入链接与插入图片的语法很像，区别在一个 !号
```
链接为：[]()

图片为：![](){ImgCap}{/ImgCap}
```
[Google](www.google.com)

![百度图片](https://www.baidu.com/img/baidu.gif)


***
## 关于制表

|    列1左对齐    |    列2居中对齐    |    列3右对齐    |
| :------------- |:-------------:| --------------:|
| 1         | 1         | 1         |
| 11        | 11        | 11        |
| 1111      | 1111      | 1111      |

***

## 代码框
使用```包裹代码
```
public static voiid main(String[] args){
    System.out.println("Hello World");
}
```

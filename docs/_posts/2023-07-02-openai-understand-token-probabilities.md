---
layout: post
title:  "openai understand tokens and probabilities"
date:   2023-07-01
categories: openai quickstart	
typora-root-url: ../
---

# 理解Token和概率

​	我们在前面”一些概念“中接触过Token，接下来在多介绍一些关于Token以及概率的概念。

​	我们的模型通过将文本分解为称为Token的更小的单元来处理文本。Token可以是单词、单词块或单个字符。来看下下面的文本以查看它如何被转化为Token的。

![token](/assets/images/quick-start-7.png)

<center>图-7</center>

​	像“cat”这样的常见单词是单个Token，而不太常见的单词通常会分解为多个Token。例如，“Butterscotch”翻译为四个Token：“But”、“ters”、“cot”和“ch”。许多Token以空格开头，例如“hello”和“bye”。

​	什么是概率，给定一些文本，模型会确定接下来最有可能出现的Token。例如，文本“Horses are my favorite”最有可能后面跟着Token是“animal”。

​	![](/assets/images/quick-start-8.png)

<center>图-8</center>

---
layout: post
title:  "openai quickstart"
date:   2023-07-01
categories: openai quickstart	
typora-root-url: ../
---

# Quickstart

​	OpenAI已经训练出了先进的语言模型，这些模型在理解和生成文本方面表现出色。我们的API提供对这些模型的访问，并可用于解决几乎任何涉及语言处理的任务。

​	在本快速入门教程中，您将构建一个简单的示例应用程序。在此过程中，您将学习使用 API 执行任何任务所必需的关键概念和技术，包括：

- Content generation
- Summarization
- Classification, categorization, and sentiment analysis
- Data extraction
- Translation
- Many more!

## Introduction

​	completions endpoint 是 Open AI 的核心 API。它提供了一个简单而灵活、功能强大的接口。您可以将一些文本作为提示(prompt)输入，API将返回一个文本结果(completion)，尝试与您提供的提示(prompt)或上下文相匹配。

​	您可以将其视为非常高级的自动完成功能 - 该模型处理您的文本提示并尝试预测后续将出现的内容。

![img](/assets/images/quick-start-1.png)
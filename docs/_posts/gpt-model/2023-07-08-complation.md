---
layout: post
title:  "function-calling"
date:   2023-07-07
categories: openai function-calling	
typora-root-url: ../../
---

# completions API

​	Completions API与Chat Completions API具有不同的接口。输入不再是消息列表，而是一个名为prompt的自由文本字符串。

以下是一个示例API调用：

```python
import openai

response = openai.Completion.create(
  model="text-davinci-003",
  prompt="Write a tagline for an ice cream shop."
)
```

> 查看详细接口文档[Completions API](https://platform.openai.com/docs/api-reference/completions)

Completions API 会根据提示给出相应的返回结果，返回结果和请求中的提示一样也是可划分为token。而Completions API 可以提供与每个输出token相关的最可能标记的有限数量的对数概率。通过使用logprobs字段来控制此功能。在某些情况下，这对于评估模型在输出中的置信度可能是有用的。

---
layout: post
title:  "openai first app"
date:   2023-07-03
categories: openai quickstart	
typora-root-url: ../
---

# GO

# 构建第一个程序

​	经过前面的介绍，已经对基本概念有所了解。现在我们根据官方的例子实际运行一下。

> 1. 如果你本地没有python环境，请先[下载python](https://www.python.org/downloads/)并安装。你也可以通过[链接下载zip](https://github.com/openai/openai-quickstart-python/archive/refs/heads/master.zip)包
> 2. 如果你本地没有git环境，请先[下载git](https://git-scm.com/downloads)并安装，
> 3. 创建[Secret key](https://platform.openai.com/account/api-keys)

通过git从github上clone下来最新的代码

```shell
git clone https://github.com/openai/openai-quickstart-python.git
```

切换到项目目录openai-quickstart-python。 从环境配置文件样例复制一份环境配置文件。

```shell
cd openai-quickstart-python
cp .env.example .env  # window下是 copy .env.example .env
```

使用你喜欢的工具，编辑 .env 文件。配置OPEN_API_KEY。效果如下：

```properties
FLASK_APP=app
FLASK_ENV=development

# Once you add your API key below, make sure to not share it with anyone! The API key should remain private.
OPENAI_API_KEY=sk-5r6JsRQixRtCqZTvs6o8T3BlbkFJXXXXXxxxxxxxx
```


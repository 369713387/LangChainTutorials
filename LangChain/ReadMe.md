# LangChain教程

这个项目包含了一系列关于LangChain框架的教程示例，从基本概念到高级应用，帮助你快速掌握如何使用LangChain构建强大的AI应用。

## 目录

1. [安装与配置](#1-安装与配置)
2. [核心概念](#2-核心概念)
3. [提示工程](#3-提示工程)
4. [模型与解析器](#4-模型与解析器)
5. [文档处理](#5-文档处理)
6. [链与流程](#6-链与流程)
7. [存储与检索](#7-存储与检索)
8. [高级主题](#8-高级主题)
9. [项目示例](#9-项目示例)

## 1. 安装与配置

- [1.Install_LangChain.ipynb](1.Install_LangChain.ipynb) - LangChain的安装指南
- [2.Set_ApiKey.ipynb](2.Set_ApiKey.ipynb) - 如何配置API密钥和环境变量

## 2. 核心概念

- [3.BaseMessage.ipynb](3.BaseMessage.ipynb) - 消息类型与对话模型
- [5.Model.ipynb](5.Model.ipynb) - 大语言模型的使用和配置
- [18.Runnable.ipynb](18.Runnable.ipynb) - LangChain的Runnable对象详解

## 3. 提示工程

- [6.ExampleSelector.ipynb](6.ExampleSelector.ipynb) - 示例选择器的使用方法
- [8.Prompt.ipynb](8.Prompt.ipynb) - 提示模板与提示工程技巧

## 4. 模型与解析器

- [5.Model.ipynb](5.Model.ipynb) - 大语言模型的调用方式
- [7.OutputParser.ipynb](7.OutputParser.ipynb) - 输出解析器的实现和应用

## 5. 文档处理

- [4.Document.ipynb](4.Document.ipynb) - 文档加载、处理与分割

## 6. 链与流程

- [9.Chain.ipynb](9.Chain.ipynb) - 链的基本概念与简单应用
- [10.Memory.ipynb](10.Memory.ipynb) - 会话记忆与状态管理
- [18.Runnable.ipynb](18.Runnable.ipynb) - 使用Runnable接口构建流程

## 7. 存储与检索

- [ChromaDB/](ChromaDB/) - ChromaDB向量数据库的使用
- [15.RAG.ipynb](15.RAG.ipynb) - 检索增强生成(RAG)实现
- [16.MultiVectorRetriever.ipynb](16.MultiVectorRetriever.ipynb) - 多向量检索技术
- [17.SelfQuery.ipynb](17.SelfQuery.ipynb) - 自查询实现

## 8. 高级主题

- [11.Evaluate.ipynb](11.Evaluate.ipynb) - 评估模型和链的性能
- [12.SQL.ipynb](12.SQL.ipynb) - 使用LangChain操作SQL数据库
- [13.API.ipynb](13.API.ipynb) - 调用外部API与服务
- [14.Cache.ipynb](14.Cache.ipynb) - 缓存机制的实现

## 9. 项目示例

本教程包含多个实际项目示例，展示了如何将LangChain的各个组件组合起来构建完整的应用：

- RAG系统实现
- 文档摘要生成器
- 对话式SQL查询
- 多模态内容处理

## 快速入门

要开始使用本教程，请按照以下步骤操作：

1. 安装必要的依赖：
   ```
   pip install langchain langchain-openai openai chromadb
   ```

2. 配置API密钥：
   ```python
   import os
   os.environ["API_KEY"] = "你的API密钥"
   os.environ["API_BASEURL"] = "你的API基础URL"
   ```

3. 按照教程序号顺序学习，从基础概念到高级应用

## 项目运行环境

- Python 3.12.3
- LangChain 0.3.22
- 阿里云百炼 (Dashscope, FAISS等)
- 向量数据库 (ChromaDB, FAISS等)

## 贡献

欢迎对本教程进行贡献！如果你发现错误或有改进建议，请提交issue或pull request。

# AI 学习计划

## 目标

我希望在 24 周内系统建立 AI 能力，达到以下 3 个目标：

1. 高效利用 AI 提升编程工作效率
2. 利用 AI 处理日常重复性工作任务
3. 不只是会用 AI，还对其原理、常见工具和工程实践有一定深度认知

## 学习原则

- 以真实任务驱动学习，不走只看不做的路线
- 应用、工程、原理三条线并行推进
- 每周都要有可交付产物
- 每 4 周做一次复盘，评估是否真的提效
- 先掌握高频、高价值能力，再补底层原理

## 时间安排

默认节奏：

- 每周投入 8 到 10 小时
- 学习周期 24 周
- 每周结构：
  - 2 小时课程或文档学习
  - 3 小时动手练习
  - 2 小时用 AI 解决真实工作任务
  - 1 小时复盘、整理模板、沉淀经验

如果每周只有 4 到 5 小时，可以把整个计划拉长到 40 到 48 周。

## 总体路线

本计划分为 6 个阶段：

1. AI 使用与提效基础
2. 日常自动化与工作流
3. 机器学习与深度学习基础
4. LLM 原理与核心论文
5. AI 工程化与 Agent 系统
6. 方向深化与作品产出

---

## 第 1 阶段：第 1-4 周

### 主题

先把 AI 真正用进工作

### 目标

- 学会把任务清晰交给 AI
- 建立稳定的 AI 编程协作方式
- 开始积累自己的提示词、模板和工作规则

### 学习重点

- Prompt 基础：目标、上下文、限制、验收标准
- 结构化提问
- 任务拆分
- 编程类常见用法：排错、读代码、写小功能、Review、写测试
- 人工复核意识

### 每周任务

#### 第 1 周

- 列出 10 个高频编程任务
- 列出 10 个重复性办公任务
- 开始记录 AI 使用日志
- 用 AI 完成 2 个真实工作任务

#### 第 2 周

- 建立个人常用提问模板
- 建立 Bug 排查模板
- 建立 Code Review 模板
- 建立代码解释模板

#### 第 3 周

- 用 AI 完成 1 次完整 Bug 修复
- 用 AI 完成 1 次小功能开发
- 用 AI 完成 1 次 Review
- 对比自己做和 AI 协作做的效率差异

#### 第 4 周

- 写出第一版个人 AI 工作手册
- 复盘哪些任务最适合 AI
- 复盘哪些任务 AI 容易出错

### 阶段交付物

- `AI_CODING_PLAYBOOK.md`
- 至少 5 个真实案例复盘
- 一套你自己的高频提示词模板

---

## 第 2 阶段：第 5-8 周

### 主题

用 AI 处理重复性工作

### 目标

- 把重复任务流程化、自动化
- 建立任务、工具、审批、输出的工作流思维
- 形成日常办公自动化能力

### 学习重点

- API 和工具调用的基本概念
- 工作流设计
- Human in the loop
- 文件处理、知识检索、表格清洗、文档总结
- MCP 和外部工具集成的基本认知

### 每周任务

#### 第 5 周

- 选 3 个最想自动化的重复任务
- 分析每个任务的输入、处理过程、输出和风险点
- 先自动化 1 个低风险任务

#### 第 6 周

- 学习工作流基本概念
- 做一个会议纪要或文档总结流程
- 给流程加人工确认步骤

#### 第 7 周

- 做一个数据清洗、分类或提取流程
- 尝试连接文件、表格或文档类工具

#### 第 8 周

- 梳理哪些任务可以全自动
- 梳理哪些任务必须保留人工审核
- 写出自动化风险清单

### 阶段交付物

- 2 个可实际使用的自动化流程
- `AI_AUTOMATION_RULES.md`
- 一份重复任务优先级清单

---

## 第 3 阶段：第 9-12 周

### 主题

补上机器学习和深度学习地基

### 目标

- 理解模型是怎么训练出来的
- 掌握最基础的 ML 和 DL 工作流
- 对损失函数、优化和验证建立清晰直觉

### 学习重点

- 监督学习基本概念
- 神经网络基础
- 前向传播和反向传播
- 训练集、验证集、测试集
- 过拟合与泛化
- PyTorch 基础

### 每周任务

#### 第 9 周

- 学习 PyTorch 基础
- 跑通 1 个官方教程
- 理解 tensor、dataset、dataloader、model、loss、optimizer

#### 第 10 周

- 手写一个简单训练循环
- 观察 loss 变化
- 尝试调整学习率和 batch size

#### 第 11 周

- 练习模型评估
- 理解过拟合和泛化
- 做一个小型分类任务

#### 第 12 周

- 写总结：训练一个模型时到底发生了什么
- 用自己的话解释反向传播和梯度下降

### 阶段交付物

- 1 个完整的小模型训练项目
- `ML_FOUNDATIONS_NOTES.md`

---

## 第 4 阶段：第 13-16 周

### 主题

系统理解 LLM 原理

### 目标

- 理解现代 LLM 的核心机制
- 知道为什么 Prompt、Few-shot 和 RAG 有效
- 对 Transformer 有基本且能讲清的认知

### 学习重点

- Tokenizer
- Embedding
- Attention
- Transformer
- In-context learning
- Few-shot learning
- Chain-of-thought
- Retrieval-augmented generation

### 每周任务

#### 第 13 周

- 学 Tokenizer 和 Embedding
- 理解 token 和文本的关系
- 理解向量表示的作用

#### 第 14 周

- 学 Attention 和 Transformer
- 理解为什么 Transformer 成为主流架构

#### 第 15 周

- 学 Few-shot、In-context learning 和 Chain-of-thought
- 做 Prompt 实验，对比不同提示方式的效果

#### 第 16 周

- 学 RAG 的基本思路
- 做一个最小可用的文档问答系统

### 阶段交付物

- 1 个简单 RAG 项目
- `LLM_CORE_CONCEPTS.md`
- 一份核心概念图，覆盖 token、embedding、attention、transformer、inference 和 tool use

---

## 第 5 阶段：第 17-20 周

### 主题

进入 AI 工程化

### 目标

- 从会用模型升级到会搭系统
- 理解 Agent、Tool、Workflow 和 Evaluation
- 把安全性和稳定性当作一等公民

### 学习重点

- Agent 工作流
- Tools
- Memory
- Routing
- Retrieval
- Evaluation
- Prompt injection
- 权限边界
- 失败案例复盘

### 每周任务

#### 第 17 周

- 学 Agent 和 Workflow 的区别
- 设计 1 个多步骤任务流

#### 第 18 周

- 给 Agent 接入工具
- 让 Agent 能查文件、文档或知识库

#### 第 19 周

- 给 Agent 增加评测方法
- 设计 10 条测试样本

#### 第 20 周

- 复盘失败案例
- 优化 Prompt、流程设计和工具选择

### 阶段交付物

- 1 个多步骤 Agent
- 1 套最小 Eval 数据集
- `AGENT_FAILURE_CASES.md`

---

## 第 6 阶段：第 21-24 周

### 主题

按方向深化并做作品

### 目标

选择一个主方向，做出真正能展示的成果。

### 可选方向

#### 方向 A：AI 编程提效

- Coding agent
- 仓库知识库
- PR Review
- 测试生成
- 文档生成
- 调试辅助

#### 方向 B：AI 自动化

- 工作流平台
- 文档、表格、邮件自动化
- MCP 集成
- 审批流
- 内部知识处理

#### 方向 C：AI 原理与底层

- Transformer 深入
- 向量检索
- 推理优化
- 开源模型生态
- 轻量微调和部署

### 阶段交付物

- 1 个完整项目
- 1 篇项目复盘文章
- 1 套可长期复用的个人 AI 工作体系

---

## 每周复盘模板

每周固定回答这 6 个问题：

1. 这周 AI 真实帮我省了什么时间？
2. 哪些任务适合 AI，哪些不适合？
3. 哪个环节最不稳定？
4. 我新学到的原理解释了什么现象？
5. 我这周产出了什么可复用资产？
6. 下周最该补的短板是什么？

---

## 里程碑

### 第 8 周时

- 已经形成稳定的 AI 提问习惯
- 已经自动化至少 2 个重复任务
- 已经有一套个人模板体系

### 第 16 周时

- 能讲清 LLM 的核心概念
- 能自己做简单 RAG
- 能用自己的话解释 Prompt、Embedding、Attention 和 Transformer

### 第 24 周时

- 能熟练用 AI 处理编程和办公任务
- 能搭建简单 Agent 或 Workflow
- 能评估一个 AI 系统，而不是只凭感觉判断
- 有一个拿得出手的项目或作品

---

## 学习资源

### AI 使用与工程

- OpenAI Prompting Guide
- OpenAI Agent Builder
- OpenAI Agent Evals
- OpenAI File Search
- OpenAI Computer Use
- Codex use cases

### 自动化与工具集成

- MCP 官方文档
- n8n Advanced AI 文档

### 深度学习与原理

- PyTorch Learn the Basics
- fast.ai Practical Deep Learning for Coders
- Karpathy Zero to Hero
- Hugging Face LLM Course

### 核心论文

- Attention Is All You Need
- Language Models are Few-Shot Learners
- Chain-of-Thought Prompting Elicits Reasoning in Large Language Models
- Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks

---

## 前期不要做什么

- 不要一开始就学怎么训练大模型
- 不要同时追太多框架
- 不要只学提示词，不学评测和工具
- 不要只看内容，不做真实任务
- 不要把高风险任务完全自动化

## 前期最该优先做什么

1. 先把 AI 用进真实工作
2. 先做低风险自动化
3. 先学核心工程能力和工作流
4. 再补系统原理
5. 最后做方向深化和作品输出

---

## 未来 7 天行动清单

1. 创建 `AI_CODING_PLAYBOOK.md`
2. 创建 `AI_AUTOMATION_RULES.md`
3. 列出 10 个高频编程任务
4. 列出 10 个重复办公任务
5. 用 AI 完成 2 个真实任务
6. 写第一次每周复盘

# Agent 应用开发学习手册

> 从单 Agent 到多 Agent 协作系统 —— 系统梳理主流框架、关键组件、部署评测与选型策略，配架构图、流程图与代码片段，构建可落地、可演进的智能体工程认知体系。

2026 年，大语言模型（LLM）应用的主线已从"提示词调优"迁移到"智能体工程（Agentic Engineering）"。本手册围绕三条主线展开：**用什么框架构建**、**由哪些组件构成**、**如何部署与持续进化**。

## 📖 在线阅读

本手册为**单文件自包含 HTML**（内联 mermaid 图表库、CSS、JavaScript，无任何外部依赖），下载后用浏览器直接打开即可阅读，无需联网、无需安装。

```bash
# 克隆后双击或用浏览器打开
open "Agent应用开发学习手册.html"      # macOS
start "" "Agent应用开发学习手册.html"  # Windows
xdg-open "Agent应用开发学习手册.html"  # Linux
```

## 📐 内容结构

手册分为四大部分及附录，共覆盖 **7 大框架、9 类关键组件、19 张架构图**。

### 第一部分 · 主流 Agent 框架解析
- 1.1 OpenCode
- 1.2 Claude Code —— 从单 Agent 到多 Agent 系统的基础设施
- 1.3 LangGraph
- 1.4 横向对比
- 1.5 AutoGen & Semantic Kernel

### 第二部分 · Agent 关键组件
- 2.1 RAG 知识库
- 2.2 Skill 技能系统
- 2.3 MCP 协议
- 2.4 上下文工程
- 2.5 多 Agent 协作
- 2.6 记忆系统
- 2.7 安全与护栏
- 2.8 可观测性
- 2.9 工具设计方法论

### 第三部分 · 部署与持续评测优化
- 3.1 部署策略
- 3.2 持续评测
- 3.3 持续优化

### 第四部分 · 框架选型建议
- 4.1 各框架速查与用例
- 4.2 实战进阶：复杂 Agent

### 附录
- A 术语表
- B 其他主流平台
- C 参考文献与延伸阅读

## ✨ 特性

- **工程视角**：不止讲概念，更讲选型权衡与落地路径
- **图示丰富**：19 张 mermaid 架构图 / 流程图，支持点击放大、滚轮缩放
- **代码片段**：覆盖各框架的真实调用示例（LangGraph、LangChain、AutoGen、Semantic Kernel、Claude Code CLI 等）
- **时效标注**：框架版本、API 与行业数据截至 2026 年 6 月
- **离线可用**：单文件自包含，无外链依赖

## 📁 目录说明

```
.
├── Agent应用开发学习手册.html   # 手册正文（自包含单文件）
└── README.md                    # 本文件
```

## 🔍 涉及的框架与平台

OpenCode · Claude Code · LangGraph · LangChain · AutoGen / Microsoft Agent Framework · Semantic Kernel · CrewAI · MCP · mcp-agent · LangSmith / LangFuse · OpenAI Agents SDK · Google ADK / Vertex AI Agent Builder

## 📌 说明

- 手册中提及的 Claude、OpenAI、Anthropic 等名称均为**技术内容引用**（用于讨论对应框架与厂商方案），商标版权归各自所有者。
- 框架 API 在 2025–2026 间变动较快，具体用法请以官方文档为准。

## 📜 许可

本手册内容仅供学习交流。如需转载，请注明来源。

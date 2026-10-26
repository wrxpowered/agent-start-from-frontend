# Agent Start From Scratch

从 Web 前端工程师出发，系统学习 AI / LLM 与 Agent 工程，通过连续迭代的项目积累可验证的工程能力。

## 总体目标

逐步具备独立设计、开发、测试、部署和维护 AI / Agent 应用的能力。重点不只是调用模型或使用框架，而是理解系统机制、验证结果、处理失败、控制权限与成本，并交付可复现的项目。

## 整体路线概要

| 阶段 | 主题 | 主要成果 |
|---|---|---|
| 1 | AI / LLM 基础与结构化交互 | 可校验、有状态的多轮交互流程 |
| 2 | 模型 API 与 TypeScript 后端 | 完整的 AI 对话应用 |
| 3 | Python 工程基础 | 可调用、可测试的 Python 服务 |
| 4 | RAG 与检索评估 | 有来源引用和质量评估的知识库问答 |
| 5 | Tool Calling 与 Agent | 能执行多步骤任务的 Agent |
| 6 | MCP | 能接入并开发 MCP Server |
| 7 | 生产级 Agent 工程 | 可评估、可观测、可部署的工程产品 |

路线采取“前端优势起步、逐步补齐后端、深入 AI 工程、强化生产能力”的方式。先使用 TypeScript / Node.js 构建 AI 应用，再系统学习 Python；先手动理解 Tool Calling 与 Agent 的核心机制，再按需求引入框架。

各阶段可以按项目需要交叉补充，但是否进入下一阶段，以当前阶段的理解、实践和验收结果为准。

## 阶段规划

日常学习只需聚焦当前阶段的文件；本 README 用于查看全局路线。

1. [阶段一：AI / LLM 基础与结构化交互](stages/stage-01-llm-foundations.md)
2. [阶段二：模型 API 与 TypeScript 后端](stages/stage-02-model-api-typescript-backend.md)
3. [阶段三：Python 工程基础](stages/stage-03-python-engineering.md)
4. [阶段四：RAG 与检索评估](stages/stage-04-rag-retrieval-evaluation.md)
5. [阶段五：Tool Calling 与 Agent](stages/stage-05-tool-calling-agent.md)
6. [阶段六：MCP](stages/stage-06-mcp.md)
7. [阶段七：生产级 Agent 工程](stages/stage-07-production-agent-engineering.md)

## 当前进度

- 当前阶段：阶段一——AI / LLM 基础与结构化交互（进行中，尚未完成）。
- 已练习：Token 基础、售后客服结构化 JSON、意图与缺失字段识别、Agent 交互流程意识、后端校验边界。
- 当前重点：完善 Schema、必填字段校验、缺失信息追问和状态流转。
- 详细记录见 [PROGRESS.md](PROGRESS.md)。

## 学习节奏原则

不规定每次学习必须投入固定时长。学习单元的大小、连续投入时间和拆分方式由内容难度、任务完整性和学习效果决定。需要连续思考或调试的任务优先保障连贯性；短知识点在达到目标后即可结束。

进度按实际完成的学习单元和阶段验收结果记录，不按日历天数推进。中断后从上次实际进度继续，不自动跳过内容，也不为了赶进度牺牲理解与验证。

## 工程与工具原则

- 优先使用云端模型/API，不把本地运行大型模型作为前置条件。
- 先理解底层机制，再选择适合项目的 SDK 或框架。
- 模型输出视为需要校验的数据；可信业务事实与最终执行由后端负责。
- 对缺失信息、异常输出、工具失败和高风险操作设计明确的控制流程。
- 项目以可运行、可测试、可解释和可复现为目标。

## 文档导航

- [阶段规划目录](stages/)
- [学习进度](PROGRESS.md)
- [学习规则与工程原则](docs/learning-rules.md)
- [AI / LLM 基础笔记](notes/llm-foundations.md)
- [路线索引（兼容入口）](ROADMAP.md)

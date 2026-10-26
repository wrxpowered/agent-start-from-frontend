# 阶段六：MCP（Model Context Protocol）

> 目标：理解 MCP 的连接模型，能够接入已有 MCP Server，并开发一个简单的自定义 Server。

## 学习范围

1. MCP 的设计目标与基本架构
2. Client 与 Server 的职责
3. Tools、Resources 等核心概念
4. 连接、发现能力和调用流程
5. 输入输出约束、错误处理与兼容性
6. 权限、凭据管理和信任边界
7. 接入已有 MCP Server
8. 开发简单 MCP Server
9. MCP 与直接 Tool Calling 的区别
10. MCP 的适用场景和不必要的复杂度

## 实践项目：为 Agent 增加 MCP 能力

为前一阶段的 Agent 接入一个 MCP Server，并实现一个小型自定义 Server，暴露明确且受控的工具或资源。

## 阶段验收标准

- 能解释 MCP Client 和 Server 的职责。
- 能描述从发现能力到调用工具的基本过程。
- 能接入并调试一个 MCP Server。
- 能实现一个简单、输入输出明确的 MCP Server。
- 能识别工具权限和不可信输入带来的风险。
- 能说明何时 MCP 有价值，何时直接 API 或 Tool Calling 更简单。

## 学习边界

优先掌握核心协议概念与端到端实践，不要求一开始覆盖所有传输方式和生态工具。

# 阶段五：MCP（Model Context Protocol）

> **阶段定位：重要可选扩展，不是进入生产工程前的硬性门槛。** 建议先理解核心概念并接入一个已有 MCP Server；是否深入开发自定义 Server、学习更多传输方式或高级部署，按项目与目标岗位需要决定。尚未深入 MCP 不应阻塞阶段六。

## 学习优先级

- **建议掌握：** Host/Client/Server 的基本角色、Tools/Resources/Prompts 的概念、接入并调用一个已有 MCP Server、基本权限和信任边界。
- **了解即可：** MCP 如何标准化能力发现与调用，以及它与直接 API / Tool Calling 的取舍。
- **后续再学：** 完整自定义 Server、更多传输方式、高级部署与生态细节，按实际需求决定。


> 目标：理解 MCP 如何标准化 AI 应用与外部能力之间的连接，并能接入已有 MCP Server；是否开发自定义 Server 取决于项目需要。

## 学习范围

1. MCP 的设计目标、基本角色和架构
2. Host、Client、Server 的职责
3. Tools、Resources 和 Prompts 的基本概念
4. 能力发现、连接与调用流程
5. 输入输出约束、错误处理和兼容性
6. MCP 工具与直接 API / Tool Calling 的差异
7. Server 权限、凭据管理和信任边界
8. 接入已有 MCP Server 并排查调用问题
9. 实现一个简单的自定义 MCP Server
10. 何时 MCP 带来复用价值，何时会增加不必要的复杂度

## 实践项目：为售后 Agent 增加 MCP 能力

为前一阶段的 Agent 接入一个 MCP Server，并实现一个小型自定义 Server，暴露少量、输入输出明确且权限受控的工具或资源。优先沿用已经掌握的 TypeScript 技术栈；若具体生态或项目要求 Python，再按需补充 Python。

## 阶段验收标准

- 能解释 MCP Client 和 Server 的职责。
- 能描述从能力发现到工具调用的基本过程。
- 能接入并调试一个 MCP Server。
- 能实现一个简单、输入输出明确的 MCP Server。
- 能识别工具权限和不可信输入带来的风险。
- 能说明 MCP 与直接 API / Tool Calling 的取舍，而不是为了使用 MCP 而使用 MCP。

## 学习边界

优先掌握核心协议概念与一次端到端接入，不要求一开始覆盖所有传输方式、生态工具或高级部署模式。MCP 是标准化集成协议，不是 Agent 本身；若当前项目没有集成需求，可先完成基本认识后继续阶段六，之后再回来深化。

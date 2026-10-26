# 学习路线索引

完整路线概要请查看 [README.md](README.md)。详细学习内容按阶段拆分，每次学习聚焦当前阶段；阶段验收完成后再进入下一阶段。

## 核心路线

1. [阶段一：AI / LLM 基础与结构化交互](stages/stage-01-llm-foundations/README.md)
2. [阶段二：模型 API 与 TypeScript 后端](stages/stage-02-model-api-typescript-backend/README.md)
3. [阶段三：RAG、检索与评估](stages/stage-03-rag-retrieval-evaluation/README.md)
4. [阶段四：Tool Calling 与 Agent](stages/stage-04-tool-calling-agent/README.md)
5. [阶段五：MCP（重要可选扩展，不是硬性门槛）](stages/stage-05-mcp/README.md)
6. [阶段六：生产级 Agent 工程](stages/stage-06-production-agent-engineering/README.md)

## 阶段优先级与门槛

- **主线必修：** 阶段一（LLM 基础与结构化交互）、阶段二（模型 API 与 TypeScript 后端）、阶段四（Tool Calling 与 Agent）、阶段六（生产级 Agent 工程）。
- **项目核心能力：** 阶段三完成基础 RAG 和评估，尤其适用于当前售后知识库主项目；但 RAG 不是所有 Agent 应用的普适前置条件。
- **重要可选扩展：** 阶段五 MCP。建议掌握概念并接入已有 Server；是否深入开发自定义 Server 按项目或岗位需要决定，不阻塞阶段六。
- **贯穿全程：** 测试、评估与安全逐步进入每个阶段，不能只留到最后。
- 每阶段的“必修 / 了解即可 / 后续再学”、验收标准、目录组织理由及外部课程对照，见 [路线设计依据、阶段取舍与目录组织说明](docs/roadmap-decisions.md)。

## 按需能力模块

- [Python 按需补充模块](modules/python-on-demand.md)：不作为独立前置阶段；根据 RAG、数据处理和所选框架的实际需要补齐。建议初始预算约占总学习投入的 10%–15%，按需要上下调整。

## 推进规则

- 按实际学习单元和验收结果推进，不按日历天数推进。
- 不规定每次学习必须投入固定时长，按内容完整性和学习效果安排。
- 项目中遇到的前置知识可以按需补充，不要求先完成所有语言或工具课程。
- 评估、异常处理和安全边界应逐步贯穿每个阶段，而非只留到最后。
- 详细进度见 [PROGRESS.md](PROGRESS.md)。

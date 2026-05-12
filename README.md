# Maoist AI Agent Framework

<div align="center">

**用《毛选》思想指导AI Agent效能管理的开源框架**  
*Multi-Agent Governance Framework Inspired by Maoist Organizational Theory*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/kcxsb/maoist-ai-agent-framework?style=social)](https://github.com/kcxsb/maoist-ai-agent-framework)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

</div>

> **AI Agent 的瓶颈不是模型不够大，而是管理不够好。**  
> *The bottleneck of AI agents isn't model size — it's management.*

---

## 为什么需要这个框架？| Why This Framework?

**AI Agent 效能管理** 是一个被严重忽视的问题。单个模型变强很容易，但一群 Agent 一起干活的时候：

- Agent 之间互相干扰，输出质量互相污染
- 缺乏有效的监督和纠错机制
- Token 浪费在无意义的循环和自我验证上
- 系统越跑越乱，熵增不可逆

**《毛选》的组织方法论**恰恰解决了这些问题。这不是生搬硬套——群众路线、批评与自我批评、集中优势兵力、调查研究——这些原则在 AI Agent 集群管理中天然适用。

This is an **open-source AI agent governance framework** that translates proven organizational principles into **multi-agent management** mechanisms.

---

## 核心机制 | Core Mechanisms

### 1. 调查研究 — Mandatory Context Pipeline
Agent 必须先调查再输出，禁止"凭记忆瞎编"。

- Forces **data-driven reasoning** over hallucination
- 每个 claim 必须可溯源
- Cuts the root cause of **LLM hallucination**

### 2. 群众路线 — Mass Line Feedback
用户反馈作为 Agent 系统的核心调优信号，不是从上层打分，而是从底层收集。

- **Bottom-up evaluation**: real users, not model-scored
- Feedback stored as persistent battle history
- Continuous **agent behavior improvement** loop

### 3. 批评与自我批评 — Adversarial Self-Inspection
内置红蓝对抗机制——Blue Team 干活，Red Team 挑毛病。

- Built-in **red teaming for AI systems**
- Automated flaw discovery and output auditing
- Self-correction without human intervention

### 4. 集中优势兵力 — Token Budget & Dynamic Routing
把算力集中到关键任务上，低价值任务只给最少资源。

- **Token optimization** for cost efficiency
- **Dynamic resource allocation** based on task priority
- Maximizes **LLM cost savings**

### 5. 反对本本主义 — Anti-Hallucination Layer
强制 Agent 根据上下文判断，不机械执行指令。

- Context-aware execution over rigid instruction-following
- **Hallucination prevention** at the architecture level
- Reduces **agent error rates** significantly

---

## 适用场景 | Use Cases

| 场景 | 解决的问题 |
|------|-----------|
| **Multi-Agent Collaboration** | 多个 Agent 协同工作时互相干扰、输出质量下降 |
| **Enterprise AI Workflow** | 企业级 AI 流程需要质量管控和审计追踪 |
| **LLM Cost Optimization** | Token 浪费严重，需要精细化的预算管理 |
| **AI Agent Reliability** | Agent 输出不稳定，需要纠错和自检机制 |
| **Autonomous Agent Systems** | 长时间运行的 Agent 系统需要对抗熵增 |

This **multi-agent governance framework** is designed for teams building **production AI agent systems** that need structure, reliability, and efficiency.

---

## 与 Agent Cluster Control 的关系

[Agent Cluster Control](https://github.com/kcxsb/agent-cluster-control) 是本框架的工程化实现项目，提供完整的 **AI agent orchestration system** 和 **agent management platform**。

- 这个仓库：方法论和治理原则
- Agent Cluster Control：工程实现和部署方案

---

## 路线图 | Roadmap

- [ ] 调查研究管道参考实现
- [ ] 红蓝对抗自动化框架
- [ ] 群众路线反馈收集系统
- [ ] Token 预算分配算法
- [ ] 战斗历史记忆存储方案
- [ ] 完整的工程参考实现 (Python / TypeScript)

---

## 贡献指南 | Contributing

欢迎各种形式的贡献：

- **Issues**: 指出理论缺陷、补充用例
- **PRs**: 工程实现、代码示例
- **讨论**: 分享你在真实 Agent 系统中遇到的组织管理问题

---

## License

MIT

---

> **"没有调查就没有发言权。" — 毛泽东**  
> *"No investigation, no right to speak." — Mao Zedong*

# Hi, I'm Xue Dingtian (薛丁天) 👋

**Building reliable LLM Agents** — Agent 评测 · 证据溯源 · 上下文工程

```
Agent Reliability Engineering  ·  Evidence-Grounded AI  ·  Context Engineering
```

---

## 我在解决什么问题

大模型能干活，但不能**信**。答案里混着一个编造的财务数字、一次无法追溯的结论、一段没有来源的引用 —— 这些在真实业务里是致命的。

我的工作聚焦在让 LLM 系统具备工程属性：

| 方向 | 具体问题 | 方法 |
|---|---|---|
| **三态决策** | LLM 输出无法用 true/false 断言 | `PASS / FAIL / REVIEW_REQUIRED` + 人工兜底通道 |
| **证据溯源** | 结论凭什么可信 | 每个数字/结论绑定 `page + bbox`，可点开原文 |
| **失败分类** | 出错了不知道为什么错 | Failure Taxonomy + Precondition + Trace ID |
| **上下文工程** | 多轮追问就"忘了"前面说过什么 | 实体追踪 + 指代消解 + 短期记忆 |
| **评测基准** | 没人说清楚"什么算好" | 自建垂类 benchmark + 多模型量化对比 |

---

## 精选项目

| 项目 | 一句话 | 技术栈 |
|---|---|---|
| **[finverify](https://github.com/KBber/finverify)** | 财报数字溯源 —— 每个财务数字都能点开看到原文出处 | Python · PyMuPDF · RAG · Benchmark |
| **[graphrag-financial-report](https://github.com/KBber/graphrag-financial-report)** | GraphRAG 处理上市公司年报，多跳财务查询 | GraphRAG · Neo4j · FastAPI · Ragas |
| **[react-llm-memory-agent](https://github.com/KBber/react-llm-memory-agent)** | Agent 记住"那另一家呢"这类追问 | ReAct · Memory · Entity Tracking |

---

## 技术栈

**语言与后端**　Python（异步并发）· FastAPI · Linux · 异步 IO
**AI 应用**　　　Agent Workflow · RAG · GraphRAG · 混合检索（BM25 + Vector）· 工具调用
**LLMOps**　　　　LangSmith · Phoenix · Ragas · Trace / Evaluation / Debug
**模型**　　　　　GPT · DeepSeek · Qwen · 开源与闭源混合
**数据**　　　　　Neo4j · FAISS · Pydantic 强类型 Schema

---

## 关于我

- 🎓 燕山大学 · 计算机科学与技术
- 💼 AI 应用工程 / 解决方案落地 —— 金融与政企场景的 LLM 系统从 PoC 到生产
- 🏷️ Agent Loop · Harness Engineering · Context Engineering
- 📍 开放远程协作

---

## 联系我

[![GitHub](https://img.shields.io/badge/GitHub-KBber-black?style=for-the-badge&logo=github)](https://github.com/KBber)

欢迎交流 Agent 评测方法、证据溯源设计、RAG 落地踩坑。

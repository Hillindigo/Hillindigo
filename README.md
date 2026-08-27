<div align="center">

# Hi, I'm Ni 👋

### Agent Developer · Go Backend Engineering Background

专注于将大模型能力落地为可运行、可验证的业务系统，而不只是聊天 Demo。

I build business-oriented Agent applications by connecting LLM reasoning with deterministic backend workflows.

[![GitHub](https://img.shields.io/badge/GitHub-Hillindigo-181717?style=flat-square&logo=github)](https://github.com/Hillindigo) [![Blog](https://img.shields.io/badge/Blog-青山黛-2f6f5e?style=flat-square&logo=astro)](https://hillindigo.cc.cd/) [![X](https://img.shields.io/badge/X-Hillindigo__A-000000?style=flat-square&logo=x)](https://x.com/Hillindigo_A) [![Email](https://img.shields.io/badge/Email-1397628709%40qq.com-1f6feb?style=flat-square&logo=maildotru&logoColor=white)](mailto:1397628709@qq.com)

</div>

---

## Current Focus

- 构建面向真实业务流程的 **Agent 应用**，关注任务编排、RAG、Tool Calling 与结构化输出
- 用确定性后端代码管理 **状态、权限、事务、冲突与幂等**，而不是把业务正确性交给 Prompt
- 探索 Agent 的 **评测、可观测性、人工接管与失败降级**
- 将 **Go 后端实习经验**形成的工程思维带入 AI 应用开发

---

## Featured Projects

### 01 · [ShopFlow](https://github.com/Hillindigo/ShopFlow)

> 跨境电商智能导购 Agent MVP

将商品检索、预算与目的地约束、价格估算、订单确认和多轮对话串联为一条可追踪的购物闭环。

**Engineering highlights**

- Supervisor–Workers 多智能体协作与任务调度
- 基于 Qdrant 的语义检索与结构化排序
- Tool Calling 驱动商品搜索、估价、下单与取消订单
- `DRAFT → CONFIRMED → CANCELLED` 状态化订单流程
- React + TypeScript 前端与 WebSocket 流式交互

`Python` · `FastAPI` · `AgentScope` · `Qdrant` · `React` · `WebSocket`

[Repository →](https://github.com/Hillindigo/ShopFlow)

---

### 02 · [AI Front Desk](https://github.com/Hillindigo/ai-front-desk)

> 面向线下服务门店的智能咨询、预约与运营 Agent

把客户咨询、知识检索、预约排班、偏好记录、商家管理和人工接管串成可扩展的业务工作流。

**Engineering highlights**

- 多 Agent 任务分类、路由与共享上下文
- FAISS + Embedding 的 RAG 知识检索
- 持久化会话、预约状态与冲突处理
- SSE 流式事件、请求幂等与失败语义
- 商家后台、权限边界、审计事件与人工接管

`Python` · `FastAPI` · `FAISS` · `SQLite` · `SSE` · `GitHub Actions`

**Boundary:** Local-first MVP with a reproducible Fake-provider baseline; not presented as production deployment evidence.

[Repository →](https://github.com/Hillindigo/ai-front-desk)

---

### 03 · [ORBITAL/LIVE](https://github.com/Hillindigo/orbital-live)

> 实时三维卫星轨道追踪应用

从实时 TLE 数据获取、SGP4 轨道传播到 WebGL 三维地球渲染，构建可交互、可部署的卫星可视化产品。

**Engineering highlights**

- Three.js / WebGL 三维地球与卫星轨道渲染
- satellite.js SGP4 轨道传播
- Web Worker 计算与离线 TLE 快照降级
- 自动化数据更新与 Cloudflare 部署
- 卫星筛选、遥测查看和交互式探索

`TypeScript` · `React` · `Three.js` · `Web Worker` · `Cloudflare`

[Live Demo →](https://orbital-live.1hillindigo.workers.dev/) · [Repository →](https://github.com/Hillindigo/orbital-live)

---

## Go Backend Experience

具备 **Go 后端实习经历**。这段经历让我在开发 Agent 应用时，不只关注模型输出，也关注 API 契约、业务状态、数据持久化和服务可靠性。

---

## Open-source Contributions

- **[ZTools](https://github.com/ZToolsCenter/ZTools)** — 新增最小化更新窗口支持
  - [Merged PR #627](https://github.com/ZToolsCenter/ZTools/pull/627) · 206 additions · 3 files changed

- **[pixi](https://github.com/prefix-dev/pixi)** — 修复顶层 `concurrency` 配置覆盖问题
  - [PR #6665](https://github.com/prefix-dev/pixi/pull/6665) · Open / awaiting review

- **[Hermes Agent](https://github.com/NousResearch/hermes-agent)** — 提交并跟踪桌面端交互问题
  - [Issue #80228](https://github.com/NousResearch/hermes-agent/issues/80228) · [Issue #84345](https://github.com/NousResearch/hermes-agent/issues/84345)

---

## Technical Stack

| Area | Technologies & Practices |
|---|---|
| **Agent Engineering** | Agent orchestration, RAG, Tool Calling, structured output, stateful workflows, evaluation |
| **Backend** | Python, FastAPI, Go, REST API, SQL, WebSocket, SSE |
| **Frontend & Visualization** | TypeScript, React, Three.js, Astro |
| **Engineering** | GitHub Actions, Docker, automated testing, Cloudflare |

---

## Connect

- GitHub: [github.com/Hillindigo](https://github.com/Hillindigo)
- Blog: [青山黛 · Hillindigo](https://hillindigo.cc.cd/)
- X: [@Hillindigo_A](https://x.com/Hillindigo_A)
- Email: [1397628709@qq.com](mailto:1397628709@qq.com)

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Hillindigo/Hillindigo/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Hillindigo/Hillindigo/output/github-contribution-grid-snake.svg" />
  <img src="https://raw.githubusercontent.com/Hillindigo/Hillindigo/output/github-contribution-grid-snake.svg" alt="Hillindigo GitHub contribution grid snake animation" />
</picture>

</div>

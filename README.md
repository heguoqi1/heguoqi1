<img src="https://capsule-render.vercel.app/api?type=rect&color=0:8b5cf6,50:ec4899,100:f97316&height=3" width="100%"/>

<div align="center">

# 何国奇

**AI 大模型应用开发 ｜ AI Agent 开发 ｜ Java 后端开发   ｜ FDE**

本科 · 计算机科学与技术 · 2025 届 · 英语四级

[![Email](https://img.shields.io/badge/Email-798139726%40qq.com-red?style=flat&logo=gmail&logoColor=white)](mailto:798139726@qq.com)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:8b5cf6,50:ec4899,100:f97316&height=3" width="100%"/>

## 🎯 技术画像

我的关注点集中在 **Agent 工业落地** —— 让 Agent 真正在企业业务里跑起来，并且算得清账。

- 🤖 **Agent 工程** — LangGraph 多层图编排 · Router-Worker / 主-子 Agent 协作 · 多 Agent 并行分支与条件回退 · Function Calling 与 MCP 工具封装
- 🔍 **RAG 检索** — 多格式文档解析 · 递归语义分块 · 混合检索 + RRF 融合 · Reranker 交叉编码器精排 · RAGAS 评测
- ⚡ **成本与延迟** — 分层模型路由 · 高频 Query 缓存直出 · 意图改写走小模型 · 语义匹配走嵌入模型
- 🛡 **工程化与容灾** — RBAC Agent / Tool 双层白名单 · 多 LLM Fallback 容灾 · 指数退避重试 · Pydantic 校验 + Schema 结构化输出兜底
- 🎙 **多模态交互** — 讯飞 ASR + Azure Neural TTS 语音闭环 · 钉钉单聊 / 群聊机器人集成
- 🧠 **微调与可观测** — LoRA / QLoRA 微调 · Ollama / vLLM 本地化部署 · LangSmith 全链路 Trace

## 🛠 技术栈

**① 语言 · 后端 · 算法**

<p>
  <img src="https://skillicons.dev/icons?i=java,python,pytorch,spring,fastapi,maven&theme=dark" height="48" />
</p>

**② AI · Agent · 知识图谱**

<p>
  <img src="https://cdn.simpleicons.org/langchain/7FC8FF" height="44" title="LangChain" />
  <img src="https://cdn.simpleicons.org/langgraph/7FC8FF" height="44" title="LangGraph" />
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/modelcontextprotocol/FFFFFF" />
    <img src="https://cdn.simpleicons.org/modelcontextprotocol/000000" height="44" title="MCP" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/ollama/FFFFFF" />
    <img src="https://cdn.simpleicons.org/ollama/000000" height="44" title="Ollama" />
  </picture>
  <img src="https://cdn.simpleicons.org/deepseek/5786FE" height="44" title="DeepSeek" />
  <img src="https://cdn.simpleicons.org/qwen/6950EF" height="44" title="Qwen" />
  <img src="https://cdn.simpleicons.org/claude/D97757" height="44" title="Claude" />
  <img src="https://cdn.simpleicons.org/coze/4D53E8" height="44" title="Coze" />
  <img src="https://cdn.simpleicons.org/dify/0033FF" height="44" title="Dify" />
  <img src="https://cdn.simpleicons.org/neo4j/4581C3" height="44" title="Neo4j" />
</p>

**③ 数据存储 · 中间件**

<p>
  <img src="https://skillicons.dev/icons?i=mysql,postgres,redis,mongodb,elasticsearch,rabbitmq&theme=dark" height="48" />
</p>

**④ 运维 · 工具**

<p>
  <img src="https://skillicons.dev/icons?i=docker,nginx,linux,git,postman&theme=dark" height="48" />
</p>

## 💼 工作经历

**四川某医美公司** · AI 全栈开发 ｜ `2025.08 – 至今`

- 负责 Agent 技术架构选型与 RAG 知识库搭建，主导多 Agent 系统编排设计与核心业务开发
- 负责基于开源模型的 LoRA 微调与模型评估
- 负责 RESTful API 设计与开发，输出 Swagger 接口文档并完成前后端联调
- 负责核心业务模块详细设计文档编写，与前端、产品对齐接口规范
- 负责部分业务数据库表结构设计，完成索引优化与慢查询治理
- 配合测试完成单元测试用例编写与 Bug 修复，参与上线发布与线上问题排查

## 🚀 项目经历

### 星枢 · 企业智能协同平台 <sub>AI 大模型应用开发 ｜ 2025.12 – 2026.04</sub>

> 面向企业通用服务场景的全员生产力 AI Agent 平台，解决跨系统表单填报、报销审核、合同条款逐条比对、跨部门知识检索等高频低效工作。

- **Router-Worker 多 Agent 协作** — 设计并实现 Router-Worker 模式，含 7 个专业化 Agent；风险前置检查、问题改写、意图路由统一分发，各子 Agent 内部以 Workflow 编排，支持工具调用失败自动重试
- **Skill 可插拔框架** — 将合规审查规则抽象为可插拔技能模块，新行业合规规则接入周期 **2 周 → 2 天**，审批效率 **小时级 → 分钟级**
- **检索生成质量优化** — 自研混合检索策略，并行召回经 RRF 融合、Reranker 交叉编码器精排；内部评测集 RAGAS 忠实度 **0.72 → 0.91**，答案准确率 **+26%**
- **延迟与成本优化** — 分层模型路由：高频类命中缓存直出、意图路由与问题改写走小模型、语义匹配走嵌入模型、复杂推理调用大模型；综合成本 **↓40%**，路由延迟控制在 **3s 以内**
- **权限校验** — 基于 RBAC 实现 Agent / Tool 双层白名单，意图路由后、Agent 执行前拦截；权限列表缓存 Redis，SQL Agent 按角色动态追加数据范围防越权，无权限直接拒绝且不消耗 LLM 调用
- **钉钉集成** — 基于 WebSocket 长连接接入消息回调，支持单聊与群聊 @机器人两种场景；卡片消息渲染回复、工作通知推送任务进度，通过 `senderStaffId` 映射内部用户体系并签发 JWT 实现身份自动关联鉴权
- **Agent 可观测性** — 集成 LangSmith 进行全链路 Trace 追踪，搭建执行耗时、Token 消耗、工具调用成功率监控看板

`LangGraph` `FastAPI` `Redis` `PostgreSQL` `PGVector` `Skill` `MCP` `Docker` `钉钉开放平台` `LangSmith`

### AI 旅创智能机器人 <sub>AI Agent 应用开发 ｜ 2025.12 – 2026.08</sub>

> 面向旅游业务的 AI 旅行规划与智能客服平台，覆盖文本与语音双通道，实现从需求理解到预订下单的全链路自动化。

- **多智能体编排** — 基于 LangGraph 构建「主-子 Agent」协作架构：主 Agent 负责需求解析与任务调度，下游挂载 7 个领域子 Agent；无数据依赖子任务（机票 / 酒店 / 美食）并行分支并发执行，关键路径压缩至 **3-4 次 LLM 调用**；质量评估 Agent 不达标时触发条件分支回退，驱动重新规划
- **自建 MCP Server 与业务集成** — 基于 MCP 协议将高德地图 API 与 Java 业务系统接口统一封装为标准 Tool 供 Agent 调用；对外对接 OTA 聚合接口及第三方供应链 API，对内集成景区票务、订单中心、支付系统，打通「查询 → 比价 → 下单 → 退改签 → 退款」全链路闭环
- **对话引擎与情绪检测** — 基于 LLM + RAG 构建旅游领域知识库，覆盖目的地攻略、签证政策、退改规则与 20+ 意图分类；对话状态采用 **FSM + LLM 混合架构**（FSM 管控结构化流程并支持断点恢复，LLM 兜底开放问答）；情绪检测双层设计，规则层关键词零延迟拦截 + BERT 快速分类，LLM 层精细研判，负面情绪超阈值自动转接资深人工
- **语音交互** — 集成讯飞 ASR + Azure Neural TTS，前端 WebSocket 实时流式识别、后端 FastAPI SSE 流式推送 Agent 响应，**首 Token 延迟 < 800ms**；结合 VAD 与噪声抑制针对景区、机场等嘈杂环境做定向优化
- **容灾与工程化** — 接入 DeepSeek、Qwen 等多 LLM 服务商设计 Fallback 容灾链路保障可用性；工具调用指数退避重试，输入侧 Pydantic 校验、输出侧 Schema 约束结构化生成，JSON 解析失败自动重试兜底
- **会话与记忆管理** — 短期记忆基于 Redis 维护会话上下文，长期记忆存入 PGVector 向量库与结构化数据库；子 Agent 在搜索阶段按用户偏好过滤排序，输出个性化行程方案；任务状态机追踪异步流程，支持超时重试与结果持久化

`LangGraph` `FastAPI` `Redis` `PostgreSQL` `PGVector` `MCP` `ASR` `TTS` `Docker`

### 旅游知识图谱抽取与问答系统 <sub>AI 大模型应用开发 ｜ 2025.08 – 2025.11</sub>

> 面向旅游行业的端到端知识图谱系统，实现从游记攻略等非结构化文本到结构化旅游知识图谱的完整闭环。

- **关系抽取模型** — 采用 Casrel 级联关系抽取架构，以 BERT 为编码器、双解码器分别预测主体与客体首尾位置，覆盖「所属景区」「相邻景点」「交通可达」等多种旅游领域关系，并支持抽取门票价格、开放时间等实体属性
- **完整推理流程** — 实现 Span 提取（阈值解码）→ 主体-客体首尾匹配 → 逐关系解码与去重的全流程，支持从任意中文文本自动抽取 SPO 三元组
- **图谱构建** — 将抽取结果导入 Neo4j，构建涵盖景点、城市、酒店等多类节点的旅游知识图谱
- **能力封装** — 将全部图谱查询能力统一封装为**一个 LangChain Tool**（内部集成 Schema 查询、景点/酒店精确与模糊搜索、实体关系查询、按关系类型批量检索、双实体间关系查询），Agent 只需调用这一个工具即可完成所有图谱交互，降低链路复杂度、提升问答稳定性
- **MCP 服务化** — 部署 MCP Server，将智能问答与关系抽取能力统一封装为标准化 Tool 对外暴露，便于客户端快速接入

`PyTorch` `BERT` `Casrel` `Neo4j` `LangChain` `FastAPI` `MCP`

### 学校教务系统 <sub>Java 后端 </sub>

- **认证与鉴权** — 采用 Shiro 实现无状态 Token 认证 + RBAC 多角色动态鉴权 + 部门数据范围隔离，实现基于角色的细粒度数据权限隔离
- **性能优化** — 针对成绩查询、报表统计等高频读操作建立复合索引，结合 Redis 缓存将复杂关联查询 **800ms → 100ms 以内**；成绩录入、文档批量导入采用 EasyExcel 批量读写处理
- **调度与压测** — 引入 Redis 热点数据缓存，结合 SpringTask 定时任务完成排考、监考等调度，**500 并发下平均响应稳定在 400ms**

`Spring Boot` `MyBatis-Plus` `MySQL` `Redis` `EasyExcel` `SpringTask` `Nginx`




<img src="https://capsule-render.vercel.app/api?type=rect&color=0:8b5cf6,50:ec4899,100:f97316&height=3" width="100%"/>

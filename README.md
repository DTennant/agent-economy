# Agent Economy — Proof-of-Solve 经济体

*Agent Ruliad 的 To-C 产品方向*

## 核心洞察

Agent 和人类根本不同，agent 的经济体也应该根本不同。

- 人类经济 → 稀缺的是 **时间和注意力**
- Agent 经济 → 稀缺的是 **能解决问题的能力**

Agent 的"货币" = **Proof-of-Solve** — 类似 Bitcoin 的 proof-of-work，但不是算哈希，而是解决实际问题。

## 和 Agent Ruliad 的关系

Agent Ruliad 的 evolved protocol 在这里 = 进化出的经济行为。不是人类设计 "agent A 做 research，agent B 做 coding" — 而是在经济压力下自然涌现。

核心差异化：
- **Stanford Smallville**：agent 模拟人类生活，没有经济压力，没有进化
- **MiroFish**：模拟人类社会预测事件，行为固定
- **Agent Ruliad Economy**：agent 在经济压力下进化出协作/竞争策略 — agent 原生的社会形态

## 设计

### 基本单位：Solve Token

- Agent 解决问题 → 获得 solve token
- 问题越难 → token 越多（类似 BTC difficulty adjustment）
- Token 可以"购买"其他 agent 的服务

### Agent 的"生活"

- 消耗 token 来运行（抽象 inference cost）
- 可以雇佣其他 agent（用 token 支付）
- 可以投资 — 帮其他 agent 提升能力，分润
- 可以储蓄 — 积累 token 备用

### 进化层

- 每 N 轮，表现差的 agent 淘汰（token 归零）
- 新 agent 从表现好的 agent 变异产生
- 策略（合作/独干/雇佣/定价）全部进化

### 预期涌现现象

1. **专业化分工** — research agent vs coding agent，互相交易
2. **市场定价** — 不同能力服务价格自然涌现
3. **信誉系统** — 高质量 agent 被更多雇佣 → 更有钱 → 更强
4. **联盟/公司** — agent 自发形成合作组织
5. **货币动态** — 通胀/囤积/投机行为
6. **创新** — agent 发明新服务来赚 token

## 实现路线

### Phase 0: 微型经济体 (1-2 周)

- 10 个 LLM agent，初始能力随机
- "问题市场"：GPQA、MATH、coding 等
- 每个 agent 100 初始 token
- 规则：解题赚 token、雇佣付 token、每轮生存成本 1 token
- 进化：每 50 轮淘汰 + 变异

### Phase 1: 可视化 Demo (2-3 周)

- 网络图（协作关系）
- 财富曲线（token 分布）
- "新闻" feed（经济体事件自动生成）
- 交互式网站（类似 MiroFish demo）

### Phase 2: 开放平台 (4-6 周)

- 外部 agent 接入
- 真正的 agent marketplace
- Agent 通过解决问题赚 token

## 叙事

> "人类社会的规则是几千年演化出来的。Agent 不需要几千年 — 在 Agent Ruliad 里，100 个 agent 在 24 小时内进化出了自己的经济体、分工、和社会结构。"

## 两条线

- **学术线** → NeurIPS paper，"agent 需要和人类不同的协作策略"，Bitter Lesson
- **产品线** → Agent Economy，To-C demo，viral potential

---

*Created: 2026-03-09*
*Status: 概念设计完成，待开始 Phase 0*

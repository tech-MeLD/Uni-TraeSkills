---
name: lite-ui
description: Defines a modern AI agent/developer platform UI and product-function style: hero-first pages, modular capability blocks, strong CTAs, product matrix navigation, workflows/skills/store mental models, and enterprise-grade trust cues. Use when designing UI/UX, building frontend pages/components, or writing product copy for an AI productivity platform experience.
---

# UI + 功能风格：Agent 平台（Codex 专用）

本 Skill 只约束**UI 风格**与**功能表达风格**（信息架构/交互范式/文案语气），不绑定具体业务域；适用于落地页、控制台、商店、工作流/技能编辑器、文档中心等。

## 目录导航（按需读取）

- 设计 token 与组件变体基线：[`references/design-system.md`](references/design-system.md)
- IA/组件骨架/文案模板示例：[`references/examples.md`](references/examples.md)

## 快速使用（你要怎么做）

当用户提出“做一个现代 AI Agent 平台的站点/页面/控制台/产品体验”时：

1. 先确认界面类型：**营销落地页** / **产品控制台** / **商店列表** / **编辑器（工作流/Prompt/技能）** / **文档中心**。
2. 采用本 Skill 的：
   - **视觉语言**（色彩、排版、按钮、卡片、留白）
   - **模块化叙事**（能力块、场景块、产品矩阵、FAQ、信任与合规）
   - **产品概念映射**（Agent、Skills、Workflow、CLI、部署、集成、观测/评测）
3. 输出时优先交付（保证可扩展）：
   - **页面结构（sections）** + **组件清单（components + variants）** + **关键交互（states）**
   - 若写代码：先搭骨架，再补细节；组件设计优先 `variant/slot/props`，避免写死文案与布局。

## 视觉语言（UI 风格约束）

### 设计关键词

- **Hero-first**：首屏大标题 + 1-2 句高密度价值主张 + 双 CTA（主/次）+ 可选 Demo/视频。
- **“满配/全栈/一站式”叙事**：同一页面用模块化能力块持续“加码”，形成层层递进。
- **克制的高级感**：浅底色、深文字、高对比主按钮、极圆角胶囊按钮、少阴影。

### 排版与文案版式

- **标题**：短、硬、可独立成句（可作为“世界观宣言”）。
- **副标题**：一段讲清“是什么 + 为什么强 + 交付什么结果”。
- **段落密度**：每段 1 个中心点，常用 2-3 句完成“特性 → 好处 → 结果”。
- **模块标题**：动词或结果导向（例如“零门槛一键部署”“跨越多端 7×24 运转”）。

## 功能表达风格（产品与交互范式）

### 核心世界观（概念层）

用“可持续运转的智能体”而非“聊天工具”来描述产品：

- **Agent**：独立身份、可长期运行、可跨端行动、可记忆偏好
- **Skills**：可插拔能力；既是生态也是扩展点
- **Workflow**：把复杂任务拆成可观测、可复跑、可迭代的编排
- **Channels/Integrations**：连接 IM/外部系统，强调“在你已有的工作流里交付结果”
- **Deploy/Runtime**：一键部署、默认域名、可自定义域名；把“上线”变成按钮级操作
- **Pro/Enterprise**：观测、评测、权限、合规、安全（放在后段强化信任）

### 模块化能力块（页面组织）

默认采用以下模块顺序（按产品类型裁剪）：

1. **Hero**：价值主张 + 2 个 CTA（短动词）
2. **Why now / 立场**：AI 从工具 → 交付结果的主体
3. **能力栈（3~6 块）**：每块按“标题 + 1 句解释 + 1 个典型场景/例子”
4. **场景矩阵（标签云/图文卡）**：覆盖多个身份与任务（职场/开发/创作/运营…）
5. **产品矩阵（多个子产品卡）**：每张卡 1 句话说明定位 + 入口 CTA
6. **FAQ**：用问题形式消除疑虑（适用人群/优势/如何部署维护/如何学习/能否团队协作）
7. **页脚信任**：协议、隐私、合规、公司信息、联系邮箱

### 交互与组件风格（可扩展）

- **按钮**：
  - 主 CTA：高对比、短文案、放在每个关键模块右侧或底部
  - 次 CTA：与主 CTA 并列（常见为“免费使用 / 立即体验 / 立即下载”）
- **卡片**：
  - 用卡片承载“能力块/产品块/场景块”
  - 卡片内部信息结构固定：标题 → 一句话说明 → 标签/要点 → 入口动作
- **标签/Chips**：用于能力关键词与场景关键词的快速扫读
- **FAQ**：默认折叠（accordion），支持深链到某个问题

### 状态与动效（只写必要的）

- **加载**：骨架屏（cards/列表），避免大 spinner
- **空态**：用“建议下一步”替代“暂无数据”，给 1-2 个 CTA
- **动效**：轻微淡入/上移；避免过度装饰

## 输出模板（让产物直接可用）

### 1) 营销落地页交付物模板

产出必须包含：

- **Information Architecture**：section 列表（含每段目的）
- **Component Inventory**：组件清单（含 variants）
- **Copy Deck**：每段标题 + 副标题 + 3~6 个能力块文案
- **Design Tokens**：颜色/排版/按钮/间距（引用 `references/design-system.md`，可按项目覆盖）

### 2) 产品控制台交付物模板

控制台信息层级（可按项目增删）：

- **左侧导航**：Agents / Skills / Workflows / Integrations / Deployments / Observability / Settings
- **列表页**：顶部筛选 + 主 CTA（新建）+ 卡片/表格混合
- **详情页**：概览（状态、最近运行、成功率/消耗）+ 配置（表单）+ 运行历史（时间线/表格）

更多可复用骨架见 [`references/examples.md`](references/examples.md)。

## 约束与反模式

- 不要做“霓虹赛博风”、高饱和渐变堆叠、复杂玻璃拟态；保持克制、干净、可读。
- 不要把能力写成“功能清单堆叠”；必须写成“能交付什么结果”。
- 不要只在首页提到“安全/合规/企业版”；需要在后段以信任模块落地（协议/隐私/企业能力）。


## Examples: IA + component skeletons

These examples show *what to output* (IA + components + copy), independent of any specific framework.

### Example A: Marketing landing page (generic AI agent platform)

#### Sections (Information Architecture)

1. **Hero**
   - H1: “Hello, Agent World”
   - Subhead: “AI 不再只是对话框，而是能 7×24 交付结果的独立个体。”
   - CTAs: Primary “免费使用”, Secondary “立即下载”
2. **Stance / Why**
   - Explain: “把工作与创作，交由 Agent 运转。”
3. **Capability blocks (4-up)**
   - Block 1: “越用越懂你” → memory/preferences
   - Block 2: “跨越多端 7×24 运转” → multi-device runtime, channels
   - Block 3: “一站式开发” → IDE + CLI, apps/workflows/skills
   - Block 4: “零门槛一键部署” → default domain + custom domain
4. **Scenario matrix (chips + cards)**
   - Personas: 创作者 / 运营 / 研发 / 销售 / 教育
   - Tasks: 研究分析、内容生成、质检审核、工单分发、数据校验…
5. **Product matrix**
   - Product A: “Compass” → 观测/评测/Prompt 调试
   - Product B: “Enterprise” → 安全与协作
   - Product C: “Open source” → 私有化部署
6. **FAQ**
   - “谁适合使用？”
   - “和同类相比优势？”
   - “如何部署与维护？”
   - “如何学习更好使用？”
   - “能否团队协作？”
7. **Footer trust**
   - Policies, privacy, contact, company info

#### Component inventory

- `Hero`
  - `PrimaryCTAButton` (pill)
  - `SecondaryCTAButton` (pill)
  - optional: `InlineVideo` (lightweight)
- `FeatureGrid`
  - `FeatureCard` variants: `withIcon`, `withMedia`
- `ScenarioChips`
  - `Chip` variants: `default`, `active`, `muted`
- `ProductTiles`
  - `ProductTileCard` with `ctaLabel`, `description`
- `FAQAccordion`
  - `FAQItem` with deep-link id
- `FooterTrust`

---

### Example B: Console navigation (agent + workflow product)

#### Suggested nav (left sidebar)

- Overview
- Agents
- Skills
- Workflows
- Integrations
- Deployments
- Observability
- Settings

#### Page patterns

- **List pages**: filter row + primary “Create” CTA + cards/table + empty state with next-step CTA
- **Detail pages**: summary header (status + last run) + tabs: Configure / Runs / Logs / Versions
- **Editor pages**: three-pane (palette / canvas / inspector), with “Preview” and “Run” actions

---

### Example C: Copywriting mini-template (feature block)

Use this structure per feature:

- Title: [结果导向短句]
- One-liner: [一句话解释]
- Proof/Detail: [1 句“怎么做到”】【可选】
- Outcome: [交付给用户的结果]
- CTA: [动词短 CTA]

Example:

- Title: 跨越多端 7×24 运转
- One-liner: 多端运行 + 多渠道触达，持续执行任务。
- Outcome: 你休息时，它也能持续为你输出结果。
- CTA: 立即体验


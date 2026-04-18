## Reference: Design tokens + component variants (baseline)

This file is optional support material for `SKILL.md`. Treat it as a “default baseline” that projects can override.

### Color (baseline)

- **Canvas / page background**: warm off-white (e.g. `#F4F4EF`)
- **Ink / strong text**: near-black (e.g. `#1C1917`)
- **Muted text**: mid-gray (project-specific; ensure WCAG contrast)
- **Border**: very light gray (e.g. `#ECECEC`)
- **Accent**: violet/purple for links/highlights (e.g. `#6541F8`) — use sparingly

### Typography (baseline)

- **Hero H1**: large (≈ 44px), tight line-height, short phrases
- **Section titles**: strong weight; reduce scale for dense pages
- **Body**: 16px; avoid long paragraphs; prefer 1-3 short sentences

### Spacing & layout

- **Grid**: 12-col or responsive CSS grid; sections have generous vertical padding
- **Base spacing unit**: 4px (compose into 8/12/16/24/32/48…)
- **Card rhythm**: consistent gaps; align CTAs across cards

### Buttons

Define these variants (names are suggestions; pick what matches your UI framework):

- **Primary**:
  - background: ink (`#1C1917`)
  - text: off-white (`#FAFAF9`)
  - radius: full (pill)
  - shadow: none
- **Secondary**:
  - background: white (`#FAFAFA`)
  - border: `#ECECEC`
  - text: dark (`#1A1A1A`)
  - radius: full (pill)
- **Tertiary / Link**:
  - text: accent (`#6541F8`) or link color
  - underline on hover; no background

### Cards

- **Purpose**: carry capability / product / scenario content blocks
- **Structure**:
  - title
  - one-line value statement
  - chips/tags (optional)
  - CTA (button or text link)
- **Visual**: light border, subtle hover (border/translateY), minimal shadow

### FAQ (Accordion)

- **Collapsed by default**
- **Deep-linkable**: allow `#faq-<id>`
- **Answer style**: short paragraphs + bullet list; end with a next-step CTA if relevant

### Microcopy patterns (Chinese)

Use concise, action-forward verbs:

- CTA: “免费使用 / 立即下载 / 立即体验 / 开始创建 / 一键部署”
- Feature titles: “跨端运转 / 一站式开发 / 低门槛部署 / 强大集成”
- Value framing: “把结果交付给你 / 让 AI 接管繁杂 / 在你休息时仍持续输出”


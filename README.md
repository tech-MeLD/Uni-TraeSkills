[English](README.md) | [中文](README_CN.md)

# Uni TraeSkills

A focused skill library for AI coding agents, tailored around practical workflows instead of generic prompt dumps.

## Overview

Uni TraeSkills provides a curated collection of skills that guide AI coding agents through structured, repeatable workflows — from requirement analysis to UI design. Each skill is self-contained with clear inputs, deliverables, reference materials, and utility scripts, making it easy to integrate into any AI-powered development environment.

## Skill Categories

### SDLC Pipeline

A four-stage development pipeline that transforms vague ideas into production-ready code:

| Skill | Description |
|-------|-------------|
| **requirement-analyst** | Analyzes and clarifies user requirements, producing a structured `REQUIREMENT.md` |
| **system-architect** | Translates requirements into technical architecture and design specifications, producing `DESIGN.md` |
| **task-planner** | Breaks design specifications into actionable development tasks, producing `TODO.md` |
| **spec-coder** | Implements code according to the finalized specification documents |

### Design & UI

A comprehensive design intelligence system covering brand identity, design tokens, and UI implementation:

| Skill | Description |
|-------|-------------|
| **brand** | Brand voice, visual identity, messaging frameworks, and asset management |
| **design-system** | Token architecture (primitive → semantic → component), CSS variables, scales, and specs |
| **design** | Meta-skill that routes tasks to the appropriate design sub-skills (brand, design-system, ui-styling, etc.) |
| **ui-styling** | Beautiful, accessible UIs with shadcn/ui, Tailwind CSS, and canvas-based visual design |
| **banner-design** | Social media, ad, and website hero banner generation with multiple art direction options |
| **slides** | Strategic HTML presentations with Chart.js, design tokens, and responsive layouts |

### Design Dependency Chain

```
brand (colors, typography)
    ↓
design-system (tokens, specs)
    ↓
ui-styling (components)
    ↓
Application Code
```

## Key Features

- **Workflow-oriented**: Skills are organized around practical development pipelines, not generic templates
- **Self-contained units**: Each skill includes references, scripts, templates, and structured data
- **Rich design intelligence**: Over 67 UI styles, 161 color palettes, 57 font pairings, and 99 UX guidelines across 16 technology stacks
- **Cross-platform**: Templates for 20+ AI coding platforms (Cursor, Copilot, Codex, Claude, Gemini, Windsurf, etc.)

## License

MIT License. See [LICENSE](LICENSE) for details.

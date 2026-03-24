# Design Resource Library

A personal design resource library skill for AI coding agents — curated by [Xiaoyang Hu (Elena)](https://xiaoyanghu.com).

Covers X accounts to follow, portfolio inspiration, UI component libraries, Framer tools, and guidance for vibe coders who want their projects to look good. Every resource was actually used — not just bookmarked.

Skills follow the [Agent Skills](https://agentskills.io/) format.

---

## Available Skills

### design-resource-library

Opinionated design resource recommendations based on real usage. Gives Claude (or any compatible agent) access to Elena's personal curation of tools, references, and portfolio sites that shaped how she designs and builds for the web.

**Use when:**
- "I'm building my first Framer portfolio. Where do I start?"
- "Who should I follow on X to improve my design taste?"
- "I'm vibe coding a landing page. What component libraries should I use?"
- "I want to find portfolio inspiration. What should I look at?"
- "What's a good reference for motion and animation?"
- "I've been staring at my portfolio for months and can't find my style. Help."

**Categories covered:**

- **X Accounts** — designers worth following for daily aesthetic intake (Vercel, Figma, Linear, OpenAI, indie studios)
- **Design Inspiration** — visual reference, interaction inspiration, and aesthetic training
- **UI Component Libraries** — React ecosystem components most designers haven't heard of, essential for web coding and vibe coding
- **Framer Resources** — learning hubs, component wikis, and cursor animations within the Framer ecosystem
- **Portfolio Inspiration** — curated designer portfolios (mostly entry-level and mid-level) focused on visual style and interaction details
- **Portfolio Platforms** — aggregator sites for browsing portfolios at scale

**Who this is for:**
- Designers building their first portfolio
- Entry-level and mid-level product designers
- Anyone learning web coding who wants to improve their aesthetic
- Vibe coders who want their projects to look good without a design background

---

## Installation

```bash
npx skills add Xiaoyang-Hu-96/design-resource-library
```

Works with Claude Code, Cursor, Cline, and 40+ other agents that support the [AgentSkills](https://agentskills.io/) standard.

**Manual install (Claude Code only):**

```bash
mkdir -p ~/.claude/skills/design-resource-library
curl -o ~/.claude/skills/design-resource-library/SKILL.md \
  https://raw.githubusercontent.com/Xiaoyang-Hu-96/design-resource-library/main/skills/design-resource-library/SKILL.md
curl -o ~/.claude/skills/design-resource-library/reference.md \
  https://raw.githubusercontent.com/Xiaoyang-Hu-96/design-resource-library/main/skills/design-resource-library/reference.md
```

---

## Usage

Once installed, the skill activates automatically when you ask design-related questions. The agent will ask a few clarifying questions before giving recommendations — stack, aesthetic direction, experience level — so answers are specific to your situation, not a generic list dump.

**Examples:**

```
I'm building my first Framer portfolio. Where do I start?
```
```
Who should I follow on X to improve my design taste?
```
```
I'm vibe coding a landing page. What component libraries should I use?
```

---

## Skill Structure

```
skills/design-resource-library/
├── SKILL.md        — behavior logic and response instructions
├── reference.md    — the full curated resource library
└── metadata.json   — skill metadata
```

---

## About the Curator

Elena (Xiaoyang Hu) is a UX/Product Designer with a background in landscape architecture and HCI. She built [xiaoyanghu.com](https://xiaoyanghu.com) using Framer with custom code — this resource library is a byproduct of everything she learned along the way.

- Portfolio: [xiaoyanghu.com](https://xiaoyanghu.com)
- X: [@elenahuxy](https://x.com/elenahuxy)
- LinkedIn: [linkedin.com/in/xiaoyanghu](https://linkedin.com/in/xiaoyanghu)

---

## License

MIT

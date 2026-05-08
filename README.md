# AI at Domo — Getting Started

Domo-branded GitHub Pages site for the internal "AI at Domo: Getting Started" guide. A practical walkthrough for using Claude at Domo: download Claude, connect Domo MCP, build a Project, build a Skill, plus reference sections.

**Live:** https://jakeheaps-coder.github.io/ai-at-domo-getting-started/

## Stack

- Single static `index.html` — no build step
- Open Sans + Domo brand tokens (Domo Blue `#99CCEE`, Orange CTA `#FF9922`)
- `localStorage` checklist progress
- Copy-to-clipboard for the `.mcp.json` config

## Local preview

```bash
open index.html
```

## Deploy

Pushed to `main` on this repo; GitHub Pages serves from `main` / root. To make edits, commit to `main` and Pages rebuilds automatically.

## Source content

Authored from `~/Downloads/AI at Domo - Getting Started.{md,html,docx}`. To revise the guide, update those source files first, then sync the changes here and re-publish.

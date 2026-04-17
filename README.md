# benchmark-skill

> 🇰🇷 [한국어 README](./README.ko.md)

**Short, context-alive benchmarking engine. Collapses any target into 5 blocks — definition+success/failure, structure, WHY people use it, adopt-points, and a one-line backbone.**

## Prerequisites

- **Claude Cowork or Claude Code** environment
- *(Optional)* Obsidian vault for `.md` outputs

## Goal

Most benchmarking outputs fail two ways: too long to read, or too shallow (feature lists). This skill enforces HBR-style half-page density with a one-line backbone plus confidence tag, so the sample is instantly reusable in planning.

## When & How to Use

Use before planning, while hunting references, or when you want to steal a mechanism from a different domain.

- **SINGLE** — one target, deep (A4 half-page)
- **MULTI** — 2–5 targets with comparison axes + integrated adopt-points
- **METAPHOR** — borrow mechanism from another domain with mapping + conflict points

## Use Cases

| Scenario | Prompt | What Happens |
|---|---|---|
| One target deep | `"HBR 벤치마킹해줘"` | SINGLE mode — 5 blocks + backbone + confidence |
| Compare N | `"HBR·Substack·Medium 비교"` | MULTI mode — comparison table + integrated adopt-points |
| Cross-domain | `"은행을 스타벅스처럼"` | METAPHOR mode — mapping + conflict points + adopt/reject verdict |

## Key Features

- **3 Modes** — SINGLE / MULTI / METAPHOR auto-detected from input
- **4 Scopes** — Organization·Service·BM / Product·Feature·UX / Campaign·Marketing·Copy / Policy·Institution
- **Fixed 5-Block Template** — definition+success/failure / structure / WHY / adopt-points / one-line backbone
- **Confidence + Evidence Required** — every backbone tagged 높음90/보통70/낮음50/모름30 (UP v37 compliant)
- **WHY as Human Mechanism** — 12 patterns (status goods, ritual, identity signal, etc.) — not feature lists
- **Metaphor Library** — 7 categories × 25+ cross-domain sources

## Works With

- **[biz-skill](https://github.com/jasonnamii/biz-skill)** — 18-axis BM pattern library (downstream call for BM axis)
- **[research-frame](https://github.com/jasonnamii/research-frame)** — invoked when source evidence is insufficient
- **[paper-engine](https://github.com/jasonnamii/paper-engine)** — cascades `.md` output structure/QC
- **[hit-skill](https://github.com/jasonnamii/hit-skill)** — human-mechanism library for the WHY block
- **[copywriting-engine](https://github.com/jasonnamii/copywriting-engine)** — downstream for Scope C (campaign) copy analysis

## Installation

```bash
git clone https://github.com/jasonnamii/benchmark-skill.git ~/.claude/skills/benchmark-skill
```

## Update

```bash
cd ~/.claude/skills/benchmark-skill && git pull
```

Skills placed in `~/.claude/skills/` are automatically available in Claude Code and Cowork sessions.

## Part of Cowork Skills

One of 25+ custom skills. Full catalog: [github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## License

MIT License — feel free to use, modify, and share.

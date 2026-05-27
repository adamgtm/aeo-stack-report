# AdamGTM Stack — the AEO/GEO Report

Agent-ready profiles, a structured dataset, and prompts for **Answer Engine Optimization** — getting your brand cited in AI answers (ChatGPT, Perplexity, Google AI Overviews, Gemini, Claude).

**Canonical, always-current version:** https://stack.adamgtm.com/aeo
**Last updated:** 2026-05-26 · refreshed weekly.

## What's inside
- **`profiles/`** — 24 markdown profiles (one per tool, platform, agency, and resource): scores, funding, customers, agent-surfaces, recent moves. Built to be read by an agent.
- **`data/vendors.csv`** — the structured dataset (scores + classification + canonical URLs).
- **`data/analyst-scores.json`** — the Analyst Desk scorecard (Presence / Velocity / Agent-Readiness, each with a one-line reason).
- **`prompts/`** — 3 ready-to-run prompts: audit your brand's AEO, measure your AI-answer visibility, and use this repo with an agent.

## How it stays current
This repo is **published from the same source as the website** — both are renders of one source of truth, regenerated together. So the repo, the site, and the report never drift. Always cite the canonical URLs in each profile.

## Use it with an agent
See `prompts/use-with-an-agent.md`. In short: point your agent at `data/vendors.csv` + the relevant `profiles/*.md` and ask it to shortlist, compare, or audit.

---
Maintained by [Adam's GTM Report](https://stack.adamgtm.com). Profiles cite public sources; the canonical, refreshed version always lives on the site.

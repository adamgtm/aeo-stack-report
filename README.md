# Adam's GTM Report: AEO/GEO Market Guide

A working map of the **Answer Engine Optimization (AEO / GEO)** market: every serious vendor, scored and sourced, in a format your AI can read. AEO is how a brand gets cited in AI answers (ChatGPT, Perplexity, Google AI Overviews, Gemini, Claude).

**Canonical, always-current:** https://stack.adamgtm.com/aeo
**Updated:** 2026-05-26, refreshed weekly. This repo is the agent-ready mirror; the website is the source of truth.

## Why this beats asking Claude with web search
- **The full roster, curated.** Every real player in one place (specialists, incumbents, agencies, open source), including the ones a cold search misses (AirOps, Adobe LLM Optimizer, Goodie) and without the SEO-blog noise.
- **Opinionated scores with reasons.** Each product carries Presence, Velocity, and Agent-Readiness, set by an analyst pass rather than a raw metric, each with a one-line reason. A web search returns marketing copy; this returns a ranked, reasoned read.
- **Sourced, so you can check the work.** Every claim traces to a primary reference: the funding post, the launch, the analyst note. All 168 live in `sources/sources.md`.
- **Built to be interrogated.** Clean markdown plus a CSV your AI parses in one pass. A decision in minutes, not an afternoon of open tabs.

## Use it (two minutes)
1. Create a Claude Project (or any AI project) and add this repo. At minimum add `report.md`, `data/vendors.csv`, and the profiles you care about.
2. Ask it your real question. As a CMO:
   - "For my situation (team, budget, technical depth), should I Buy, Build, or Hire, and which two tools fit best? Use the scores and the Best-for lines."
   - "Shortlist self-serve tools under $X per year, ranked, with the trade-offs."
   - "Draft my 90-day AEO plan: what to measure first, what to fix, which tool to start with. Cite the sources."

   As an investor:
   - "Plot Presence against Velocity. Who leads, who is the challenger pulling up, where is the whitespace?"
   - "Which vendors have a real moat (agent-readiness, data, distribution) versus a thin wrapper? Cite the evidence."
   - "Map funding and momentum across the category. Who looks overvalued, who underrated, and why?"
3. For the method, read `report.md` ("How to evaluate") and the reason attached to each score.

## What's inside
- **`report.md`**: the AEO map. What it is, how to choose (Buy / Build / Hire), the six jobs, the market POV. Start here.
- **`profiles/`**: 23 deep profiles (product, platform, agency, open source) with scores, funding, customers, agent-surfaces, and recent moves.
- **`data/vendors.csv`**: the structured dataset. Scores, reasons, classification, and canonical URLs, ready to sort.
- **`sources/sources.md`**: 168 external references, each with the claim it supports.

## Refresh Process
The website is the source of truth, and this repo is published from it. When the market moves, the record updates once and both the website and this repo regenerate together, so they stay in sync. Cite the canonical URL on each profile.

---
Maintained by **Adam Schoenfeld** at [Adam's GTM Report](https://stack.adamgtm.com).

Gartner mapped the on-prem era. G2 mapped the SaaS era. This is the market guide for the AI era: not one analyst's once-a-year snapshot, and not a pile of reviews, but a living evaluation layer, refreshed continuously and shown with its work, so a buyer (or a buyer's agent) can get smart in minutes instead of weeks.

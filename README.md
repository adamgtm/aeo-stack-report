# The AEO/GEO Market — an analyst-grade intelligence pack

Everything you need to get smart, fast, on **Answer Engine Optimization (AEO)**, also called **GEO** — getting your brand cited in AI answers (ChatGPT, Perplexity, Google AI Overviews, Gemini, Claude). The full vendor landscape, **scored, sourced, and built to be read by your AI**.

**Canonical, always-current:** https://stack.adamgtm.com/aeo · maintained by [Adam's GTM Report](https://adamgtm.com).
**Updated:** 2026-05-26 · refreshed regularly.

## Why this beats "just ask Claude + search the web"
- **Complete, curated roster.** Every serious player — specialists, incumbents, agencies, and open source — in one place, including the ones a cold web search misses (AirOps, Adobe LLM Optimizer, Goodie) and without the SEO-blog noise.
- **Opinionated scores, with reasons.** Each product carries **Presence / Velocity / Agent-Readiness**, set by a human-style analyst pass (not a raw metric), each with a one-line *why*. Web search hands you marketing copy; this hands you a ranked, reasoned read.
- **Sourced — you can check our work.** Every claim traces to a primary reference (the funding post, the launch announcement, the analyst note); all 162 are compiled in [`sources/sources.md`](sources/sources.md).
- **Structured for interrogation.** Clean markdown + a CSV your AI parses in one pass — a decision in minutes, not an afternoon of tabs.

## Use it (2-minute setup)
1. Create a **Claude Project** (or any AI project) and add this repo — at minimum drop in `report.md`, `data/vendors.csv`, and the `profiles/` you care about.
2. **Interrogate it.** Examples:

**If you're a CMO / marketing leader:**
- "Given my situation — {team size, budget, technical depth} — should I Buy, Build, or Hire for AEO, and which two tools fit best? Use the scores and the 'Best for' lines."
- "Shortlist self-serve tools under ${budget}/yr, ranked, with the trade-offs and what each is best at."
- "Draft my 90-day AEO plan: what to measure first, what to fix, which tool to start with — and cite the sources."

**If you're an investor:**
- "Plot Presence vs Velocity. Who's the leader, who's the challenger pulling up, where's the whitespace?"
- "Which vendors have a real moat — agent-readiness, proprietary data, distribution — vs. a thin wrapper? Cite the evidence in `profiles/` and `sources/`."
- "Map funding and momentum across the category. Who looks overvalued, who's underrated, and why?"

3. Want the method? `report.md` ("how to evaluate") and the per-score reasons in `data/analyst-scores.json`.

## What's inside
- **`report.md`** — the AEO map: what it is, how to choose (Buy / Build / Hire), the six jobs, the market POV. **Start here.**
- **`profiles/`** — 23 deep profiles (product, platform, agency, OSS): scores, funding, customers, agent-surfaces, recent moves.
- **`data/`** — `vendors.csv` (scored dataset + classification + canonical URLs) and `analyst-scores.json` (scores + reasons).
- **`sources/sources.md`** — 162 external references with the claim each supports.
- **`prompts/`** — paste-and-run: audit your brand's AEO, measure your AI-answer visibility, use this repo with an agent.

## How it stays current — and honest
This repo is **published from the same source as the website**, regenerated together, so the report, the dataset, and the site never drift. Scores are *product-overall* judgments; profiles cite public sources; the canonical, always-current version lives at https://stack.adamgtm.com/aeo.

---
Built by [Adam's GTM Report](https://adamgtm.com) — one analyst-curator plus AI-native infrastructure. The thesis: 80% of the intelligence at 1% of the cost.

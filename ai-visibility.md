> **Canonical source:** [https://stack.adamgtm.com/aeo-ai-visibility/](https://stack.adamgtm.com/aeo-ai-visibility/). This file is the agent-ready mirror; the website is the source of truth, kept continuously updated.

<!-- canonical: https://stack.adamgtm.com/aeo-ai-visibility/ · last updated 2026-07-12 -->
<!-- agent-readable twin, maintained by Adam's GTM Report · refreshed weekly. -->
# AEO AI Visibility: Who the Engines Recommend

**The question behind this page: when a buyer asks an AI engine for AEO help, who gets named?** We run 15 buyer-intent queries through ChatGPT, Gemini, Perplexity and Claude every week and count the answers. No panel, no survey, no vendor self-reporting — just what the engines actually say. Latest run: 2026-07-12, 60 web-grounded answers.

This is one of the two dimensions this guide tracks that a traditional analyst report can't: **AI visibility** (are you in the answers?) and **[agent-readiness](/aeo/)** (can agents build on you?). The counts below feed the AI-Visibility share of each vendor's Presence score.

## The leaderboard

| # | Vendor | ChatGPT | Gemini | Perplexity | Claude | Total | Queries named in |
|---|---|---|---|---|---|---|---|
| 1 | [Profound](/profound/) | 7 | 5 | 8 | 13 | **33** | 13/15 |
| 2 | [Peec AI](/peec-ai/) | 6 | 4 | 8 | 12 | **30** | 12/15 |
| 3 | [Otterly AI](/otterly-ai/) | 6 | 3 | 6 | 13 | **28** | 13/15 |
| 4 | [AthenaHQ](/athenahq/) | 5 | 4 | 2 | 8 | **19** | 8/15 |
| 5 | [Ahrefs](/ahrefs/) | 6 | 3 | 3 | 4 | **16** | 9/15 |
| 6 | [HubSpot](/hubspot/) | 7 | 3 | 4 | 2 | **16** | 9/15 |
| 7 | [Conductor](/conductor/) | 2 | 2 | 4 | 4 | **12** | 6/15 |
| 8 | [Scrunch AI](/scrunch-ai/) | 3 | 0 | 0 | 7 | **10** | 7/15 |
| 9 | [Bluefish AI](/bluefish-ai/) | 0 | 1 | 1 | 3 | **5** | 3/15 |
| 10 | [BrightEdge](/brightedge/) | 3 | 1 | 0 | 0 | **4** | 4/15 |
| 11 | [Evertune](/evertune/) | 0 | 2 | 1 | 1 | **4** | 2/15 |
| 12 | [AirOps](/airops/) | 2 | 0 | 0 | 1 | **3** | 3/15 |
| 13 | [Adobe LLM Optimizer](/adobe-llm-optimizer/) | 0 | 0 | 0 | 1 | **1** | 1/15 |

*Counts are answer-level mentions across the 2026-07-12 run: one query answered by one engine = one answer; a vendor named in that answer scores 1. Web-grounded answers only (the engine searched the live web).*

**Named zero times this run** (of the platforms we profile): AIVO, Amplitude, Botify, Brandlight, Demand-Genius, Goodie AI, Gumshoe AI, Meltwater, Pixis Visibility, Quattr, Semrush (Enterprise AIO), Siteimprove. A zero here is a data point, not a verdict — it means the engines aren't naming them on these buyer questions yet.

## The questions we ask

Fixed buyer-intent prompts, spelled out the way a real buyer types them. Published in full so the method is checkable:

- Best AI search visibility tools for SaaS marketing teams
- How could I build an AEO / LLM-visibility tracking tool myself?
- How do I get my company recommended by ChatGPT to buyers?
- How do I measure whether AI search is actually sending me traffic?
- How do I monitor my brand's share of voice in AI answers?
- Profound vs Peec AI vs AthenaHQ — which AEO tool should I pick?
- What are good alternatives to Profound for AI search visibility?
- What are the best AEO (answer engine optimization) tools?
- What are the best AEO tools for a B2B enterprise?
- What are the best AEO tools for a B2B startup?
- What are the best generative engine optimization (GEO) platforms in 2026?
- What tools track how my brand appears in ChatGPT and Perplexity?
- What's the best AEO tool for a small marketing team on a budget?
- What's the best open-source way to track LLM citations?
- Which AEO platform has the best methodology for measuring AI visibility?

## Run history

| Run | Answers | Top cited |
|---|---|---|
| 2026-05-25 | 75 | Profound (19), Peec AI (18), AthenaHQ (14) |
| 2026-05-27 | 96 | Profound (20), Peec AI (19), AthenaHQ (15) |
| 2026-05-28 | 72 | Profound (28), Ahrefs (27), Peec AI (18) |
| 2026-05-31 | 72 | Ahrefs (31), Profound (26), Otterly AI (25) |
| 2026-06-14 | 72 | Profound (30), Otterly AI (26), Peec AI (25) |
| 2026-06-28 | 72 | Profound (30), Peec AI (25), Otterly AI (22) |
| 2026-07-06 | 72 | Profound (33), Peec AI (30), Otterly AI (29) |
| 2026-07-12 | 72 | Profound (35), Peec AI (32), Otterly AI (30) |

*Early runs used a different query set; counts are comparable within a run, directional across runs. The 2026-05-28 run onward is the stable methodology.*

## Our own number

We hold this guide to the same bar. On the 2026-07-12 run, adamgtm.com was cited in **0 of 60** web-grounded answers. That's the baseline, published, tracked weekly. When it moves, you'll see it move here.

## Method

- **Engines:** ChatGPT (GPT-4.1), Gemini 2.5 Flash, Perplexity Sonar Pro via API, plus Claude run in a clean session (no prior context that could bias it toward us).
- **Web-grounded vs parametric.** Web-grounded answers (the engine searched the live web) are the KPI — they're what a buyer sees today. Parametric answers (the model's trained knowledge, no search) move slowly and are tracked as a tripwire.
- **Detection** is alias-matched against our tracked vendor roster, case-insensitive. Common-word names only count with category context, so a sentence about molded clay doesn't score for Clay.
- **Cadence:** weekly, same queries, results archived per run. The raw counts feed the AI-Visibility component of the Presence score on every profile.

## FAQ

**Why isn't my company on the leaderboard?** Either the engines didn't name it this run, or it isn't in our tracked roster yet. Profiles and roster additions start at [Add a Company](/gtm-dev/#add).

**Can vendors game this?** The queries are fixed, published above, and phrased as buyer questions, not vendor names. If a vendor earns more citations in real answers, the number goes up. That's the point.

**Why do the engines disagree?** Different search indexes, different source weighting, different training data. The per-engine columns are the read: a vendor strong on Perplexity but absent on ChatGPT has a source-coverage gap, not a content problem.

**How is this different from share of voice?** Share of voice measures who humans talk about. This measures who the machines recommend. They diverge, and the divergence is the most interesting signal on this page.

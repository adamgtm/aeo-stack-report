# Prompt — Use this repo with an agent

This repo is built to be read by an AI agent. `/profiles` holds one markdown file per tool, platform, and agency (scores, funding, customers, agent-surfaces, recent moves). `/data` holds the structured dataset.

## Load it
Point your agent at this repo (clone it, or feed `/data/vendors.csv` + the relevant `/profiles/*.md`). Then ask things like:

- "Given my situation — {team size, budget, technical depth} — should I Buy, Build, or Hire for AEO, and which 2 vendors fit best? Use the scores and reasons in the profiles."
- "Build me a shortlist of AEO vendors with a public MCP server or API I can build on, ranked by Agent-Readiness."
- "Which vendors have the highest Velocity but lower Presence — the challengers worth watching?"
- "Compare {vendor A} and {vendor B} for an enterprise on Adobe Experience Manager."

## How the scores work
Each product has Presence, Velocity, and Agent-Readiness, each with a one-line reason. Scores are set by an analyst pass (judgment over the data), not a raw rubric — see `/data/analyst-scores.json`. They're product-overall, refreshed regularly. Canonical, always-current version: https://adamgtm.com/stack/aeo

---

*From the AdamGTM Stack — AEO report.*

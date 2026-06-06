> **Canonical source:** [https://stack.adamgtm.com/meltwater/](https://stack.adamgtm.com/meltwater/). This file is the agent-ready mirror; the website is the source of truth, kept continuously updated.

<!-- canonical: https://stack.adamgtm.com/meltwater/ · last updated 2026-06-06 -->
<!-- agent-readable twin, maintained by Adam's GTM Report · refreshed weekly. -->
# Meltwater

Media-intelligence incumbent that bolted AI-answer monitoring onto its listening suite. Taken private by Marlin Equity Partners and Altor in 2023; around 28,000 corporate customers and 1,700 employees. The classic PR, social-listening, and influencer suite now sits alongside GenAI Lens, an AI-visibility tracker across 7 platforms, and Mira, the AI assistant layer. Recent moves: GenAI Lens launch, a Mira API MCP server, and the widely-shared "LinkedIn is the #2 most-cited source in AI" research.


## Scores

| Score | Value | Why |
|---|---|---|
| Presence | 68 | Huge company (~28K customers, ~3.5B NOK rev); AEO is a 2025 bolt-on, not the brand |
| Velocity | 48 | Incumbent cadence; AEO line ships in spurts, not weekly |
| Agent-Readiness | Medium | REST API plus an official Mira MCP server; no SDK/CLI/llms.txt |

*Product-overall scores from the AdamGTM Analyst Desk (floor 50). Canonical, always-current: https://stack.adamgtm.com/aeo*

## The Solution & Approach

Meltwater is the canonical "listening giant pivots to AEO" story. The core business is media monitoring, PR, social listening, and influencer marketing — a global data footprint built over two decades. In July 2025 it bolted AI-answer monitoring onto that base with GenAI Lens (also surfaced as "AI Visibility Tracking"), positioning the new AI layer as one more lens alongside news and social data rather than a standalone product.

The AEO push runs outward from the existing data engine. GenAI Lens runs your custom prompts across ChatGPT, Gemini, Perplexity, Claude, Copilot, Grok, and DeepSeek every 24-48 hours, then reports a competitive "Share of Model" (share of voice in AI answers), sentiment, and source attribution showing which sites and journalists the LLMs cite. Mira, the AI assistant layer, sits on top of the same intelligence engine to track share of voice, sentiment, and narrative momentum in natural language.

This is tracking and monitoring, not execution. The product tells you how often AI answers name your brand, how they feel about it, and where they pulled the claim from — it does not write or push content to move those numbers. The category POV comes through research, not a new role: Meltwater's May 2026 report (9.5M AI citations across 16 B2B categories, run through GenAI Lens) landed the "LinkedIn is the #2 most-cited source in AI answers" finding that traveled widely. The data footprint is doing the marketing.

## Best for

PR and comms teams already on Meltwater for media monitoring and social listening who want AI-answer share-of-voice folded into the same dashboard, rather than buying a separate AEO pure-play. Enterprise-skewed; sales-led.

## Pricing & trial

Sales-led, no public pricing. GenAI Lens is sold as an add-on within a customized Meltwater package; availability varies by plan and you confirm pricing with an account team. Third-party estimates put a multi-module Meltwater contract well into five figures per year. [Pricing](https://www.meltwater.com/en/pricing).

## Agent Experience

How you build on this platform (or wire it into your own agents):

| Surface | Available | Docs |
|---|---|---|
| API | Yes | [docs](https://developer.meltwater.com/docs/meltwater-api/reference/overview/) |
| MCP | Yes (Mira API, remote) | [docs](https://developer.meltwater.com/docs/meltwater-api/mira-api/mcp-server/) |
| SDK | No | — |
| CLI | No | — |
| llms.txt | No | — |

Moderate build-on option. Meltwater exposes a REST API across its listening and search data, and ships an official remote MCP server for the Mira API — configure it in Claude Desktop and Claude can pull Meltwater's news, social, and AI-search insights directly (rate-limited to 60 requests/minute). There is no published official SDK or CLI, and no llms.txt at the root domain.

## Recent moves

- **2026-05-12**: Published "LinkedIn is the #2 most-cited source in AI answers" — 9.5M AI citations analyzed across 16 B2B categories via GenAI Lens. [source](https://www.globenewswire.com/news-release/2026/05/12/3292744/0/en/linkedin-is-the-2-most-cited-source-in-ai-answers-new-meltwater-report-finds.html)
- **2025-07-29**: Launched GenAI Lens, tracking brand representation across ChatGPT, Claude, Gemini, Perplexity, Grok, and DeepSeek with sentiment, citation sourcing, and competitive Share of Model. [source](https://www.meltwater.com/en/about/press-releases/meltwater-debuts-industry-first-genai-lens)



## Company, Financials & Funding History

Founded 2001 in Oslo, Norway, by Jorn Lyseggen, now headquartered with a large San Francisco presence (incorporated in the Netherlands as Meltwater N.V.). Listed on the Oslo Børs from December 2020. Taken private on 2023-08-09 by MW Investment B.V., an entity jointly controlled by Marlin Equity Partners and Altor, at NOK 18.00/share, and delisted from the Oslo Stock Exchange. Around 28,000 corporate customers and 1,700 employees; reported revenue of roughly 3.5B NOK.

| Date | Event |
|---|---|
| 2023-08-09 | Taken private by Marlin Equity Partners + Altor (MW Investment B.V.); delisted from Oslo Børs |
| 2020-12 | IPO on the Oslo Stock Exchange (ticker MWTR) |



## Analyst placement

No AEO-specific analyst placement sourced (e.g. G2 AEO Grid). Meltwater is an established player in adjacent media-monitoring and social-listening analyst coverage; treat its AEO standing as an incumbent extension rather than a category-leader ranking.

## Links

[Homepage](https://www.meltwater.com) · [GenAI Lens](https://www.meltwater.com/en/products/genai-lens) · [AI Visibility Tracking](https://www.meltwater.com/en/capabilities/ai-visibility-tracking) · [Developer Portal](https://developer.meltwater.com/docs/meltwater-api/reference/overview/) · [Pricing](https://www.meltwater.com/en/pricing) · [LinkedIn](https://www.linkedin.com/company/meltwater-group)

*Last updated 2026-06-06 · refreshed weekly*

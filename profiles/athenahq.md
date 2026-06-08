> **Canonical source:** [https://stack.adamgtm.com/athenahq/](https://stack.adamgtm.com/athenahq/). This file is the agent-ready mirror; the website is the source of truth, kept continuously updated.

<!-- canonical: https://stack.adamgtm.com/athenahq/ · last updated 2026-06-07 -->
<!-- agent-readable twin, maintained by Adam's GTM Report · refreshed weekly. -->
# AthenaHQ

AthenaHQ is an AI-Native AEO/GEO platform for measuring and improving how AI search engines cite a brand. Customers include Rootly, Grüns, and AutoRFP. $3M raised. Recent releases: Oracle claims-correction, an OAuth-scoped MCP server, and the State of AI Search 2026 benchmark.


## Scores

| Score | Value | Why |
|---|---|---|
| Presence | 72 | Punches above $2.7M seed on influencer visibility |
| Velocity | 56 | Shipping cadence cooled recently; smaller team |
| Agent-Readiness | Medium | Some API access; no public MCP yet |

*Product-overall scores from the AdamGTM Analyst Desk (floor 50). Canonical, always-current: https://stack.adamgtm.com/aeo*

## The Solution & Approach

AthenaHQ is an AEO/GEO platform that tracks how brands are represented across AI search engines (ChatGPT, Perplexity, Claude, Gemini, Bing Chat, You.com) and then helps fix what those models say. It anchors credibility on proprietary data: a catalog of 3M+ real-world AI responses across 300K+ citation sites, the QVEM query-volume model, and the State of AI Search benchmark.

The product arc moves from measurement to action. The core monitors citations, share of voice, and competitor coverage; Oracle then surfaces incorrect or conflicting claims AI models make about a brand and routes them through a review-and-approve flow. The QVEM model addresses the "dark traffic" problem by estimating prompt volumes where keyword-volume data does not exist.

Its category POV is that AI search resets the playing field. Founder Andrew Yan frames it as a leveler where smaller brands can out-rank deeper-pocketed incumbents, and the company pushes positioning like LinkedIn as a Tier-A LLM citation surface. Partnerships with Noble and Uberall extend the platform from citation intelligence toward placement execution.

## Best for

Teams shifting from traditional SEO to AEO/GEO that want to measure brand citations across multiple AI engines and act on the gaps, including smaller brands competing against larger content libraries.

## Pricing & trial

Self-serve starts at $95/month billed annually (3,600 credits, 8 LLMs, unlimited seats with RBAC; $295 billed monthly) with a custom Enterprise tier; first month is 67% off and no free trial is listed. [Pricing](https://athenahq.ai/pricing).

## Agent Experience

How you build on this platform (or wire it into your own agents):

| Surface | Available | Docs |
|---|---|---|
| API | Yes | [docs](https://docs.athenahq.ai/api-reference/authentication) |
| MCP | No | — |
| SDK | Yes | [docs](https://docs.athenahq.ai/api-reference/introduction) |
| CLI | No | — |
| llms.txt | Yes | [docs](https://athenahq.ai/llms.txt) |

AthenaHQ shipped an OAuth-scoped MCP server alongside an API reference and llms.txt, so its citation data is agent-readable and it is a workable build-on-top option.

## Reference customers

Rootly, Grüns, AutoRFP, Lago, Nuvadermis, Coupons.com, Checkr, Artisan, Ollie.

## Case studies & customer stories

- Nuvadermis 5x'd citation rate and tripled AI-search share of voice [source](https://www.linkedin.com/posts/andrew-yan-200_mr-worldwide-seo-the-good-news-ai-activity-7458512934076526593-EKxx)
- AutoRFP drove 10x ChatGPT traffic; 22.4% of inbound leads attribute ChatGPT [source](https://www.linkedin.com/posts/andrew-yan-200_a-perfect-partnership-how-autorfp-drove-activity-7447636170165022720-ELN4)
- Grüns grew AI SEO citations 23x in two months [source](https://www.linkedin.com/posts/andrew-yan-200_you-need-a-better-way-to-grow-how-gr%C3%BCns-activity-7440748066804006912-1xCM)
- Rootly owns 52.6% of AI Search share of voice [source](https://www.linkedin.com/posts/andrew-yan-200_the-best-feeling-seeing-your-customers-win-activity-7438210343195123713-hL-N)
- Lago drove a 50% increase in demos from AI search [source](https://www.linkedin.com/posts/andrew-yan-200_how-lago-achieved-50-increase-in-demos-from-ugcPost-7421551783296020480-HGUV)

## Recent moves

- **2026-05-08**: Published the Nuvadermis case study, framing AI search as a leveler where a smaller brand 5x'd its citation rate against deeper-pocketed competitors. [source](https://www.linkedin.com/posts/andrew-yan-200_mr-worldwide-seo-the-good-news-ai-activity-7458512934076526593-EKxx)
- **2026-05-04**: Launched Oracle by AthenaHQ, which discovers and actions incorrect or conflicting claims AI models make about a brand (a Canva demo found 87 contradictions in one week). [source](https://www.linkedin.com/posts/andrew-yan-200_that-a-boy-after-writing-what-i-activity-7457052581639536641-_fub)
- **2026-04-22**: Published tracked-data finding positioning LinkedIn owned content as a Tier-A LLM citation surface, with domain authority rivaling top-tier media outlets. [source](https://www.linkedin.com/posts/andrew-yan-200_linkedin-data-is-powering-llms-now-what-activity-7452714061202575360-cpHJ)
- **2026-04-09**: Duane Forrester ranked AthenaHQ the #1 AI Search tool, placing it top-right of the quadrant and first on both coverage and confidence. [source](https://www.linkedin.com/posts/andrew-yan-200_people-trust-specifics-duane-forrester-activity-7447993923194650624-4dai)
- **2026-04-08**: Published the AutoRFP case study showing 22.4% of inbound leads attributing ChatGPT to discovery, AthenaHQ's highest-engagement post tracked that day. [source](https://www.linkedin.com/posts/andrew-yan-200_a-perfect-partnership-how-autorfp-drove-activity-7447636170165022720-ELN4)
- **2026-04-01**: Launched its MCP server with OAuth-scoped authentication, making Athena's data agent-accessible. [source](https://www.linkedin.com/posts/athena-hq_this-week-we-launched-our-mcp-thank-you-ugcPost-7440434599790362624-1oLN)

## Company, Financials & Funding History

Founded in 2024 in San Francisco, with founder Andrew Yan as its public voice. The company was rejected from Y Combinator twice before being accepted into the Winter 2025 batch, then went from a stealth product to a category-defining AEO/GEO platform in roughly 18 months.

| Date | Round | Amount |
|---|---|---|
| 2025-06 | Seed | $2.2M (led by FCVC and Red Bike Capital, Y Combinator participating; angels including former Algolia CMO Ashley Stirrup and Eli Schwartz) |
| 2025-02 | Pre-seed | $500K (Y Combinator, Winter 2025 batch) |

## Analyst placement

Duane Forrester ranked AthenaHQ the #1 AI Search tool, placing it in the top-right of his quadrant and first on both coverage (features and utility) and confidence (credibility, documentation, case studies). [source](https://www.linkedin.com/posts/andrew-yan-200_people-trust-specifics-duane-forrester-activity-7447993923194650624-4dai)

## Links

[Homepage](https://athenahq.ai) · [Pricing](https://athenahq.ai/pricing) · [LinkedIn](https://www.linkedin.com/company/athena-hq)

*Last updated 2026-06-07 · refreshed weekly*

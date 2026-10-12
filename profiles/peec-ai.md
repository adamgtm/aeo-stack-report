> **Canonical source:** [https://stack.adamgtm.com/peec-ai/](https://stack.adamgtm.com/peec-ai/). This file is the agent-ready mirror; the website is the source of truth, kept continuously updated.

<!-- canonical: https://stack.adamgtm.com/peec-ai/ · last updated 2026-08-23 -->
<!-- agent-readable twin, maintained by Adam's GTM Report · refreshed weekly. -->
# Peec Ai

AI search analytics platform in the AEO/GEO category, built for mid-market teams and agencies. Customers include Chanel, Squarespace, and Hugo Boss. About $29M raised, with $10M ARR and 2,500+ customers as of May 2026. Recent releases: Brand Perception, an Ads page tracking competitor placements inside ChatGPT, and AI Shopping Analytics.


## Scores

| Score | Value | Why |
|---|---|---|
| Presence | 74 | Clear #2 specialist; doubled ARR $4M→$10M in 6mo |
| Velocity | 86 | Fast specialist shipping; capable MCP recently added |
| Agent-Readiness | High | Capable MCP server plus monitoring API |

*Product-overall scores set by Adam (floor 50). Canonical, always-current: https://stack.adamgtm.com/aeo*

## The Solution & Approach

Peec AI tracks how often, where, and why AI answer engines cite a brand. It monitors eight engines, with ChatGPT, Perplexity, and Google AI Overviews on every plan and Claude, Gemini, DeepSeek, Grok, Copilot, Llama, and Google AI Mode sold as add-ons at roughly 20 to 30 euros per engine per month. The stated technical differentiator is UI scraping of real interactions rather than the API-only sampling competitors use, plus a data pipeline that filters raw query sets down to brand and purchase questions instead of running generic prompts.

The positioning is volume, not enterprise. CEO Marius Meiners called it "more of a mid-market mass product," with two thirds of customers at 100 to 200 employees, and the company formalized that with dedicated agency tiers, an agency partner program, and multi-client prompt tracking without per-seat fees. The product has widened steadily from a citation tracker: Actions turns visibility data into a prioritized worklist, Crawl Insights and Crawlability cover the technical side, AI Shopping Analytics extends tracking to SKU-level product visibility, and Query Fanouts exposes the underlying searches engines run before answering.

The category POV is a durability bet. Peec stood up a research team to reverse-engineer how answer engines select brands, hiring Metehan Yesilyurt, Tomek Rudzki, and CPO Malte Landwehr, who says "many tactics that currently work well for short-term gains in AI visibility will stop working in a year." Two 2026 launches show where the measurement thesis is going. Brand Perception scores what AI thinks about a brand rather than how often it names one, and the Ads page monitors paid placements inside ChatGPT answers, a concession that earned and paid visibility will sit side by side in the same answer.

## Best for

Mid-market marketing teams and agencies that need multi-client AI visibility tracking with self-serve pricing rather than an enterprise contract.

## Pricing & trial

Public self-serve tiers, reported at 75 euros a month for 25 prompts, 169 euros for 100 prompts, and enterprise from 424 euros, with API access gated to the 499 euro Enterprise plan and separate agency tiers at [peec.ai/pricing-agencies](https://peec.ai/pricing-agencies). No free trial disclosed in public sources. [Pricing](https://peec.ai/pricing).

## Agent Experience

How you build on this platform (or wire it into your own agents):

| Surface | Available | Docs |
|---|---|---|
| API | Yes | [docs](https://docs.peec.ai/api) |
| MCP | Yes | [docs](https://peec.ai/mcp) |
| SDK | No | — |
| CLI | No | — |
| llms.txt | Yes | [docs](https://docs.peec.ai/llms.txt) |

Strong build-on surface for a mid-market vendor: an MCP server with read and write operations and bulk actions across up to 50 entities, a Customer API that exposes Brand Perception and AI Shopping data, public docs with an llms.txt, and a Looker Studio connector for the reporting path.

## Reference customers

Chanel, Squarespace, Hugo Boss, Axel Springer, ElevenLabs, TUI, n8n, Attio, Peak Ace, DEPT.

## Case studies & customer stories

- Momentum: 10x AI search visibility, 2x sessions from AI search [source](https://peec.ai/blog/how-momentum-boosted-ai-search-visibility-by-10x-with-peec-ai)
- Mint Position: 16% ChatGPT visibility lift in 90 days for client Duckfund [source](https://peec.ai/blog/how-mint-position-helps-fintech-clients-unlock-16-more-ai-search-visibility-and-secure-1-search-positions-with-peec-ai)

## Recent moves

- **2026-08-11**: Published research finding AI assistants describe companies more positively when the brand name contains positive-sounding words, an effect that fades once the model has real information about the company. [source](https://peec.ai/blog/ai-assistants-judge-your-company-by-its-name-i-measured-how-much)
- **2026-08-06**: Published research arguing AI search visibility has to be diagnosed in three stages, retrieval, reranking, and generation, since a relevant page can still lose the citation at the reranking gate. [source](https://peec.ai/blog/rerankers-for-geo-aeo-how-ai-search-chooses-passages-and-sources)
- **2026-08-03**: Brand Perception went generally available, scoring what attributes AI associates with a brand and how it holds ground on them, with both scores exposed via the Customer API and MCP server; the Ads page moved to GA in the same release. [source](https://peec.ai/changelog)
- **2026-07-28**: Launched an Ads page that monitors competitor advertising inside ChatGPT responses, covering advertiser identity, ad copy, landing pages, bidding on branded queries, and estimated spend tiers. [source](https://peec.ai/blog/introducing-ads-page)
- **2026-07-06**: Shipped a Query Fanouts page exposing the underlying searches AI engines run before answering, and folded AI Shopping data into the MCP server and Customer API. [source](https://peec.ai/changelog)
- **2026-06-30**: Published a post on pairing server log analysis with citation data to diagnose AI search visibility, breaking AI bot traffic into training, indexing, and user-query types. [source](https://peec.ai/blog/why-server-logs-are-crucial-for-ai-search-strategy)

## Company, Financials & Funding History

Founded in Berlin by Marius Meiners (CEO), Tobias Siwonia (CTO), and Daniel Drabo (CRO), who met in Antler's Berlin Winter 2024 cohort and launched the product in early 2025. Sixteen months later the company reported $10M ARR, 2,500+ customers, 70+ employees, and an open New York office.

| Date | Round | Amount |
|---|---|---|
| 2026-06 | In talks | ~$10M at a ~$200M pre-money valuation, open and unclosed as of Sifted's June 26 report |
| 2025-11 | Series A | $21M (Singular), with Antler, Combination VC, identity.vc, S20; ~$29M total raised at a >$100M post-money valuation |
| 2025-07 | Seed | 5.2M euros (20VC), with Antler, Foreword VC, Identity.VC, Combination VC, S20; closed less than four weeks after the pre-seed |
| 2025-04 | Pre-Seed | 1.8M euros (Antler participating) |

## Analyst placement

Rated 4.9 out of 5 across 11 verified reviews on [G2](https://www.g2.com/products/peec-ai/reviews); the Winter 2026 G2 Grid Leader designation in the AEO category is held by Profound, not Peec. Ranked #2 in Harmonic's Q2 2026 Hot 25 and featured by Ramp as a breakout software vendor, [per the company's May 2026 release](https://www.globenewswire.com/news-release/2026/05/28/3303009/0/en/peec-ai-hits-10m-arr-16-months-after-launch-as-brands-race-to-optimize-for-ai-search.html).

## Links

[Homepage](https://peec.ai) · [Pricing](https://peec.ai/pricing) · [Docs](https://docs.peec.ai/) · [LinkedIn](https://linkedin.com/company/peec-ai)

*Last updated 2026-08-23 · refreshed weekly*

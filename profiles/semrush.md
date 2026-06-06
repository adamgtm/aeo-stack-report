> **Canonical source:** [https://stack.adamgtm.com/semrush/](https://stack.adamgtm.com/semrush/). This file is the agent-ready mirror; the website is the source of truth, kept continuously updated.

<!-- canonical: https://stack.adamgtm.com/semrush/ · last updated 2026-06-06 -->
<!-- agent-readable twin, maintained by Adam's GTM Report · refreshed weekly. -->
# Semrush (Enterprise AIO)

The SEO incumbent extending into AI visibility, now an Adobe company. The classic Semrush keyword, backlink, and rank suite now sits alongside Enterprise AI Optimization (AIO) and the AI Visibility Index, an industry benchmark built on AIO data. AI-specific products reportedly grew to ~$38M ARR (from ~$4M a year earlier). Recent releases: AI Search Forecasting, Query Fan-Out Analysis, and Agent Analytics log-file tracking.


## Scores

| Score | Value | Why |
|---|---|---|
| Presence | 80 | SEO incumbent, ~$444M rev, now an Adobe company; built AIO + AI Visibility Index in-house |
| Velocity | 70 | Real monthly AIO cadence — forecasting, fan-out, agent analytics |
| Agent-Readiness | Medium | Official hosted MCP plus public API; no dedicated SDK/CLI |

*Product-overall scores from the AdamGTM Analyst Desk (floor 50). Canonical, always-current: https://stack.adamgtm.com/aeo*

## The Solution & Approach

Semrush is the incumbent SEO platform — keyword, backlink, rank, and competitive-intelligence tooling at scale — extending that base into the AEO/GEO category. The AI line is **Enterprise AI Optimization (AIO)**, sold inside the enterprise tier, plus the **AI Visibility Index**, a public benchmark of brand performance across AI search platforms built on AIO data.

**Correcting a common misread: Semrush did not acquire an AEO startup.** It *built* AIO and the AI Visibility Index in-house, off its existing crawler and prompt-data infrastructure. The acquisition ran the other way — **Adobe bought Semrush** (announced Nov 2025, closed April 28, 2026, ~$1.9B all-cash, $12.00/share). Semrush is now an Adobe company, folded into Adobe's CX Enterprise stack alongside Adobe LLM Optimizer and Brand Concierge. So the AEO landscape now has two Adobe-owned visibility products sitting next to each other — a consolidation worth watching.

The product runs outward from the SEO base. AIO monitors a large global pool of LLM prompts (Semrush cites 261M+) and ties AI-visibility gaps back to the search signals that feed them — Query Fan-Out Analysis surfaces the Google queries fueling AI answers, Agent Analytics reads server logs to show how AI bots crawl a site, and AI Search Forecasting projects traffic, reach, and mention gains. The AI Visibility Index packages the data as a live microsite plus a downloadable report, which is doing real category-vocabulary work.

## Best for

Enterprise SEO teams already standardized on Semrush who want AI-visibility tracking layered onto their existing keyword, rank, and crawler data — and, increasingly, buyers already inside or moving toward the Adobe Experience Cloud stack.

## Pricing & trial

Sales-led for the enterprise tier. Enterprise AIO and the AI Visibility Index are part of the enterprise platform, not the self-serve Semrush subscriptions; no public self-serve pricing for AIO. [Enterprise AIO](https://enterprise.semrush.com/solutions/ai-optimization/) · [Pricing](https://www.semrush.com/prices/).

## Agent Experience

How you build on this platform (or wire it into your own agents):

| Surface | Available | Docs |
|---|---|---|
| API | Yes | [docs](https://developer.semrush.com/api/) |
| MCP | Yes (hosted, `https://mcp.semrush.com/v1/mcp`) | [docs](https://developer.semrush.com/api/introduction/semrush-mcp/) |
| SDK | No | — |
| CLI | No | — |
| llms.txt | No | — |

Solid build-on option for an incumbent: a mature public API plus an official hosted MCP server (streamable HTTP, OAuth or API-key auth) with documented connectors for Claude, ChatGPT, Cursor, VS Code, Gemini CLI, and Perplexity. No dedicated SDK or first-party CLI — agent integration runs through the MCP connector rather than a packaged library.

## Recent moves

- **2026-04-28**: Adobe completed its ~$1.9B all-cash acquisition of Semrush ($12.00/share), folding it into Adobe's CX Enterprise stack alongside LLM Optimizer and Brand Concierge. [source](https://news.adobe.com/news/2026/04/adobe-completes-semrush-acquisition)
- **2026-02-02**: Added log-file analysis — Bot Analytics in Site Intelligence and Agent Analytics in AIO — to show how search and AI bots crawl and read a site. [source](https://www.semrush.com/news/445236-semrush-enterprise-adds-log-file-analysis-to-site-intelligence-and-ai-optimization/)
- **2026-01-15**: Released Query Fan-Out Analysis in AIO, revealing the Google search queries that fuel AI responses in systems like ChatGPT. [source](https://www.semrush.com/news/442193-query-fan-out-analysis-comes-to-semrush-enterprise-ai-optimization-revealing-the-search-signals-behind-ai-responses/)
- **2025-12-11**: Added AI Search Forecasting to AIO — projecting potential traffic, reach, and brand-mention gains from prompt-level gaps. [source](https://www.semrush.com/news/439224-semrush-enterprise-ai-optimization-adds-new-ai-search-forecasting-capabilities/)
- **2025-11**: Adobe announced the deal to acquire Semrush for ~$1.9B. [source](https://news.adobe.com/news/2025/11/adobe-to-acquire-semrush)
- **2025-09-08**: Launched the AI Visibility Index, an industry benchmark of brand performance across AI search, built on Enterprise AIO data. [source](https://www.semrush.com/news/422790-semrush-launches-ai-visibility-index-the-definitive-industry-benchmark-for-brand-performance-in-ai-search/)

## Company, Financials & Funding History

Founded 2008; was a NYSE-listed public company (SEMR) before the Adobe acquisition. FY2025 revenue of ~$443.6M, up 18% YoY, with total ARR of ~$471M. AI products surpassed ~$38M ARR as of Dec 31, 2025 (up from ~$4M a year prior), and the enterprise platform reached ~$37M ARR across 579 customers. Acquired by Adobe in an all-cash deal that closed April 28, 2026 at ~$1.9B ($12.00/share); now operates as an Adobe company.

| Date | Event | Detail |
|---|---|---|
| 2026-04 | Adobe acquisition closed | ~$1.9B all-cash, $12.00/share |
| 2025-11 | Adobe acquisition announced | ~$1.9B all-cash |
| 2021-03 | IPO | Listed on NYSE as SEMR |

## Analyst placement

Positions the [AI Visibility Index](https://ai-visibility-index.semrush.com/) as its own industry benchmark for brand performance in AI search. Third-party analyst placement for the AIO line specifically is thin in our corpus — flag for follow-up.

## Links

[Homepage](https://www.semrush.com) · [Enterprise AIO](https://enterprise.semrush.com/solutions/ai-optimization/) · [AI Visibility Index](https://ai-visibility-index.semrush.com/) · [Developer / API](https://developer.semrush.com/api/) · [LinkedIn](https://www.linkedin.com/company/semrush)

*Last updated 2026-06-06 · refreshed weekly*

> **Canonical source:** [https://stack.adamgtm.com/scrunch-ai/](https://stack.adamgtm.com/scrunch-ai/). This file is the agent-ready mirror; the website is the source of truth, kept continuously updated.

<!-- canonical: https://stack.adamgtm.com/scrunch-ai/ · last updated 2026-06-21 -->
<!-- agent-readable twin, maintained by Adam's GTM Report · refreshed weekly. -->
# Scrunch AI

Platform for brand optimization in generative AI environments, built around an Agent Experience Platform that serves machine-readable content to AI crawlers. Customers include RunPod, Lenovo, and Crunchbase. About $19M raised before its June 2026 acquisition by Sitecore. Recent moves: Scrunch MCP, Agent Traffic Monitoring, and G2 High Performer status.


## Scores

| Score | Value | Why |
|---|---|---|
| Presence | 66 | Acquired by Sitecore (Jun 2026); G2 High Performer; serve-to-crawlers play |
| Velocity | 40 | Cadence cooled into the acquisition; standalone roadmap now folding into Sitecore |
| Agent-Readiness | Medium | API available; agent surface limited |

*Product-overall scores from the AdamGTM Analyst Desk (floor 50). Canonical, always-current: https://stack.adamgtm.com/aeo*

## The Solution & Approach

Scrunch AI is a platform for brand optimization in generative AI environments. Its angle is serve-side: rather than only measuring how often AI engines cite a brand, Scrunch built an Agent Experience Platform (AXP), CDN-layer infrastructure that detects AI crawler traffic and routes it to a compressed, machine-readable version of the site. The company reports cutting a typical pricing page from roughly 124K tokens to 1.3K tokens, and the AXP works with Akamai, Cloudflare, and Vercel.

That positioning sets it apart from measurement-only AEO/GEO rivals like Profound and Peec AI. Scrunch layers monitoring on top: Agent Traffic Monitoring shows which AI platforms visit, whether they are training, indexing, or retrieving, and which pages draw the most agent attention. A Scrunch MCP server adds a read-and-act interface, letting users query brand presence and trigger audits or optimization workflows from Claude, ChatGPT, or Copilot.

The serve-side bet is what a DXP incumbent bought. Sitecore acquired Scrunch in June 2026 (Bloomberg reported about $225M, terms officially undisclosed), folding the AXP and AI-search insights into SitecoreAI's content products. It was the first major exit in the AEO specialist cohort, alongside Adobe's acquisition of Semrush.

## Best for

Brands that want to do more than measure AI citations and are willing to serve compressed, machine-readable content to AI crawlers at the CDN layer.

## Pricing & trial

Self-serve Core tier at $250/month, Enterprise is contact-sales (adds API plus MCP access and SSO), with a 7-day free trial. [Pricing](https://scrunch.com/pricing).

## Agent Experience

How you build on this platform (or wire it into your own agents):

| Surface | Available | Docs |
|---|---|---|
| API | Yes | [docs](https://developers.scrunch.com) |
| MCP | Yes | [docs](https://developers.scrunch.com/mcp/overview) |
| SDK | No | — |
| CLI | No | — |
| llms.txt | Yes | [docs](https://scrunch.com/llms.txt) |

Strong build-on surface: an API plus an MCP server with write actions (create brands, track prompts and competitors, trigger site audits and optimization workflows), available to all customers on every plan.

## Reference customers

RunPod, Lenovo, BairesDev, Crunchbase, Fictiv, Penn State University.

## Case studies & customer stories

- RunPod turned ChatGPT into a top acquisition channel within 90 days, reporting 4x growth in monthly paying customers [source](https://scrunch.com/blog/2025-07-how-runpod-leveraged-the-scrunch-ai-platform-to-achieve-4x-growth,-turning-chatgpt-into-a-top-performing-acquisition-channel-/)

## Recent moves

- **2026-06-03**: Acquired by Sitecore (Bloomberg reported about $225M, undisclosed); becomes a Sitecore Company with its Agent Experience Platform folding into SitecoreAI content products. [source](https://www.sitecore.com/company/newsroom/press-releases/2026/06/sitecore-acquires-scrunch-and-buying-decisions)
- **2026-05-12**: Launched Scrunch MCP, an MCP server connecting AI-search data to Claude, ChatGPT, and Copilot with read plus write actions, available on all plan levels. [source](https://scrunch.com/blog/scrunch-mcp-talk-to-and-act-on-ai-search-data-in-natural-language)
- **2026-02-02**: Named a High Performer in G2's first AEO Grid, Winter 2026, alongside Otterly.AI, with Profound taking Leader. [source](https://www.prnewswire.com/news-releases/aeo-software-category-grows-over-2000-on-g2-as-half-of-b2b-buyers-start-their-search-with-ai-chatbots-over-google-302674557.html)
- **2026-01-29**: Partnered with Stacker to embed AI search visibility reporting into the Stacker platform, focused on earned-media presence. [source](https://stacker.com/blog/stacker-and-scrunch-team-up-to-make-ai-search-visibility-more-measurable)
- **2026-01-08**: Announced a Noble partnership pairing Scrunch citation-source identification with Noble's automated publisher outreach, closing the monitor-to-act loop. [source](https://scrunch.com/blog/2026-01-partnership-scrunch-noble)
- **2025-10-01**: Agent Traffic Monitoring reached general availability, tracking AI agent visit volume, platform mix, activity type (training, indexing, retrieval), and most-visited pages. [source](https://scrunch.com/blog/agent-traffic-monitoring/)

## Company, Financials & Funding History

Founded in fall 2023 in San Francisco by Chris Andrew (CEO) and Robert MacCloy (CTO), both previously CPO and CTO at Hearsay Systems. Scrunch launched publicly in November 2024 and was acquired by Sitecore in June 2026.

| Date | Round | Amount |
|---|---|---|
| 2025-07 | Series A | $15M (Decibel, with Mayfield and Homebrew), announced alongside the Agent Experience Platform |
| 2024-11 | Seed | $4M (Mayfield / Patrick Salyer), with angels Clara Shih, TJ Parker, and Bryant Chou |

## Analyst placement

Named a High Performer in G2's first AEO (Answer Engine Optimization) Grid, Winter 2026, alongside Otterly.AI, with Profound taking Leader status. [source](https://www.prnewswire.com/news-releases/aeo-software-category-grows-over-2000-on-g2-as-half-of-b2b-buyers-start-their-search-with-ai-chatbots-over-google-302674557.html)

## Links

[Homepage](https://scrunch.com) · [Pricing](https://scrunch.com/pricing) · [Docs](https://scrunch.com/docs/) · [LinkedIn](https://linkedin.com/company/scrunchai)

*Last updated 2026-06-21 · refreshed weekly*

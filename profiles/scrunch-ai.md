> **Canonical source:** [https://stack.adamgtm.com/scrunch-ai/](https://stack.adamgtm.com/scrunch-ai/). This file is the agent-ready mirror; the website is the source of truth, kept continuously updated.

<!-- canonical: https://stack.adamgtm.com/scrunch-ai/ · last updated 2026-09-06 -->
<!-- agent-readable twin, maintained by Adam's GTM Report · refreshed weekly. -->
# Scrunch AI

AI customer experience platform for AEO/GEO, spanning measurement and delivery. Customers include Lenovo, Crunchbase, and RunPod. Raised about $19M before Sitecore acquired it in June 2026, reportedly for roughly $225M. Recent releases: Site Diagnostics, Keyword Volume Estimator, and Scrunch MCP.


## Scores

| Score | Value | Why |
|---|---|---|
| Presence | 66 | Acquired by Sitecore (Jun 2026); G2 High Performer; serve-to-crawlers play |
| Velocity | 40 | Cadence cooled into the acquisition; standalone roadmap now folding into Sitecore |
| Agent-Readiness | Medium | API available; agent surface limited |

*Product-overall scores set by Adam (floor 50). Canonical, always-current: https://stack.adamgtm.com/aeo*

## The Solution & Approach

Scrunch is an AEO/GEO platform that does two jobs. It measures how brands appear in AI answers, and it serves machine-readable content to the agents doing the retrieving. The current line spans Signals, Site Diagnostics, Optimizer, Agent Traffic Monitoring, and an MCP interface that reads and writes.

The delivery layer is the differentiator. The Agent Experience Platform sits at the CDN layer, detects AI crawler traffic, and routes it to a compressed version of the site. Scrunch reported cutting a typical pricing page from roughly 124K tokens to 1.3K. It runs on Akamai, Cloudflare, and Vercel. Site Diagnostics, launched August 2026, added page-by-page remediation without requiring that CDN integration.

The category POV is that measurement alone is not the product. Scrunch positions against measurement-only AEO tools by serving content to agents rather than only counting citations. CEO Chris Andrew frames the July 2026 platform relaunch around AI agents now generating more web traffic than humans. Its own research argues the same point from the data side: across millions of news-search events from February to June 2026, direct AI referrals accounted for just 1.1% of post-conversation visits, so last-click reporting misses most of the path.

## Best for

Brands and agencies that want AI visibility measurement and the serve-side infrastructure to act on it in one platform, especially teams already running a CDN they can integrate at.

## Pricing & trial

Core starts at $250/month for 125 prompts, 5 site audits, and 4 LLMs; Enterprise is contact-sales and adds 9 LLMs, API plus MCP access, and SSO, with a 7-day free trial available. [Pricing](https://scrunch.com/pricing).

## Agent Experience

How you build on this platform (or wire it into your own agents):

| Surface | Available | Docs |
|---|---|---|
| API | Yes | [docs](https://developers.scrunch.com) |
| MCP | Yes | [docs](https://developers.scrunch.com/mcp/overview) |
| SDK | No | — |
| CLI | No | — |
| llms.txt | Yes | [docs](https://scrunch.com/llms.txt) |

Strong: public API reference, an llms.txt, and a Scrunch MCP server that supports write actions like creating brands, tracking prompts, and triggering audits from Claude, ChatGPT, or Copilot, though API and MCP access sit behind the Enterprise tier.

## Reference customers

Lenovo, Crunchbase, BairesDev, Fictiv, Penn State, RunPod.

## Case studies & customer stories

- RunPod turned ChatGPT into a top acquisition channel in 90 days, reporting ~40 new customers/day and 4x growth in monthly paying customers [source](https://scrunch.com/blog/2025-07-how-runpod-leveraged-the-scrunch-ai-platform-to-achieve-4x-growth,-turning-chatgpt-into-a-top-performing-acquisition-channel-/)

## Recent moves

- **2026-08-19**: Launched Site Diagnostics, an always-on product that scores each page for AI retrievability and citability and ranks fixes by predicted impact, with no CDN integration required. [source](https://scrunch.com/blog/site-diagnostics-always-on-action-plan-for-winning-ai-search)
- **2026-08-13**: Published a study of millions of news-search events from February through June 2026 finding that direct AI referrals accounted for only 1.1% of post-conversation news visits. [source](https://scrunch.com/blog/surviving-the-clickpocalypse-ai-eating-the-news)
- **2026-07-28**: Launched Keyword Volume Estimator in beta on all plans, sizing weekly demand for AI-assistant queries from real consumer AI conversations rather than keyword matching. [source](https://scrunch.com/blog/keyword-volume-estimator-measure-ai-search-demand-and-whats-behind-it)
- **2026-07-08**: Relaunched the product line as the Agent Experience Platform, organized into Signals, Site Diagnostics, and Optimizer. [source](https://scrunch.com/blog/agent-experience-platform)
- **2026-06-03**: Sitecore acquired Scrunch and folded the Agent Experience Platform into SitecoreAI's content products; terms were undisclosed, though Bloomberg reported roughly $225M. [source](https://www.sitecore.com/company/newsroom/press-releases/2026/06/sitecore-acquires-scrunch-to-help-brands-influence-discovery--and-buying-decisions)
- **2026-05-12**: Launched Scrunch MCP, connecting its AI-search data to Claude, ChatGPT, and Copilot with both read and write actions, available on all plan levels. [source](https://scrunch.com/blog/scrunch-mcp-talk-to-and-act-on-ai-search-data-in-natural-language)

## Company, Financials & Funding History

Founded in 2023 by Chris Andrew and Robert MacCloy, previously CPO and CTO at Hearsay Systems, and headquartered in San Francisco. The company went from a $4M seed in November 2024 to an acquisition by Sitecore in June 2026, having raised about $19M in total.

| Date | Round | Amount |
|---|---|---|
| 2025-07 | Series A | $15M (Decibel), with Mayfield and Homebrew; announced alongside the Agent Experience Platform at 500+ brands |
| 2024-11 | Seed | $4M (Mayfield), at public launch of the AI-search monitoring product |

## Analyst placement

Named a High Performer in G2's first AEO Grid, Winter 2026, alongside Otterly.AI, with Profound taking Leader status. [PRNewswire](https://www.prnewswire.com/news-releases/aeo-software-category-grows-over-2000-on-g2-as-half-of-b2b-buyers-start-their-search-with-ai-chatbots-over-google-302674557.html)

## Links

[Homepage](https://scrunch.com) · [Pricing](https://scrunch.com/pricing) · [Docs](https://scrunch.com/docs/) · [LinkedIn](https://linkedin.com/company/scrunchai)

*Last updated 2026-09-06 · refreshed weekly*

> **Canonical source:** [https://stack.adamgtm.com/ahrefs/](https://stack.adamgtm.com/ahrefs/). This file is the agent-ready mirror; the website is the source of truth, kept continuously updated.

<!-- canonical: https://stack.adamgtm.com/ahrefs/ · last updated 2026-09-27 -->
<!-- agent-readable twin, maintained by Adam's GTM Report · refreshed weekly. -->
# Ahrefs

Bootstrapped, Singapore-based SEO platform extending into AEO from its own web crawler. Customers include IBM, LinkedIn, Uber, Adidas, and Shopify. No outside funding. Recent releases: the Letaido agent workspace, doubled API and MCP limits on all plans, and an Adaptive traffic model that accounts for AI Overviews.


## Scores

| Score | Value | Why |
|---|---|---|
| Presence | 70 | ~$149M rev, bootstrapped, dominant SEO; AEO bolt-on |
| Velocity | 62 | Steady; AEO is strong add-on not core focus |
| Agent-Readiness | Medium | Official MCP plus mature API |

*Product-overall scores set by Adam (floor 50). Canonical, always-current: https://stack.adamgtm.com/aeo*

## The Solution & Approach

Ahrefs is an SEO platform built on its own web crawler. The core is Site Explorer, Keywords Explorer, Site Audit, and Rank Tracker. In 2026 it pushed that base into AEO. Brand Radar tracks brand visibility across six AI platforms, Custom Prompt Tracking adds metered prompt checks, and the Brand Radar API returns citation state (mentioned, cited, found but not cited, not found) as a queryable field rather than a dashboard number.

The category argument comes from CMO Tim Soulo. Ahrefs already owns the crawler, so AI-visibility data is a marginal query against existing infrastructure, not a new data cost. He has made the case directly against pure-plays like Profound. Ahrefs backs it by giving data away: a free Firehose web-mentions API and a free llms.txt generator built on analysis of 137,000+ domains. In August 2026 it also published how its AI prompt volumes are derived, a Google keyword volume multiplied by a platform-usage ratio. Most of the category has not disclosed its method.

In August 2026 Ahrefs started selling the workflow as well as the data. Letaido, from $99/month, is the agent workspace that previously ran Agent A internally, with always-on hosting and connectors to Slack, HubSpot, WordPress, and Notion. In September it doubled API and MCP limits on every plan. Soulo's stated reason: "The bottleneck isn't code anymore, it's quality data."

## Best for

SEO-led teams that want AI-visibility tracking on the same dataset they already use for search, and teams building their own agents that need broad web data through an API or MCP.

## Pricing & trial

Published seat-based tiers from a $29/month Starter plan to $1,499/month Enterprise (annual), with a free Webmaster Tools tier and metered AEO add-ons (Brand Radar AI Index $199 to $699, Custom Prompts $50 to $250); no general free trial is listed. [ahrefs.com/pricing](https://ahrefs.com/pricing). [Pricing](https://ahrefs.com/pricing).

## Agent Experience

How you build on this platform (or wire it into your own agents):

| Surface | Available | Docs |
|---|---|---|
| API | Yes | [docs](https://docs.ahrefs.com/api/docs/introduction) |
| MCP | Yes | [docs](https://docs.ahrefs.com/mcp/docs/introduction) |
| SDK | No | — |
| CLI | No | — |
| llms.txt | No | — |

One of the stronger build-on options in AEO: a documented API (Standard and up), an official remote MCP server for Claude, ChatGPT, Cursor, Claude Code, and Copilot Studio (Lite and up), a free Firehose mentions API, and API and MCP limits doubled on all plans in September 2026.

## Reference customers

IBM, LinkedIn, Uber, Adidas, Shopify.

## Case studies & customer stories

- Ahrefs on automating its own data-content refresh with Letaido: 14 posts updated monthly, at least 20 hours saved per month [source](https://ahrefs.com/blog/taught-agent-to-refresh-data-content/)

## Recent moves

- **2026-09-22**: Doubled API and MCP limits on all plans, arguing that data, not code, is now the bottleneck for marketers building their own tools. [source](https://x.com/timsoulo/status/2102446325681860710)
- **2026-08-12**: Launched Letaido, a standalone agent workspace from $99/month with native Ahrefs data, always-on hosting, and connectors to Slack, HubSpot, WordPress, and Notion. [source](https://siliconangle.com/2026/08/12/ahrefs-launches-ai-agent-workspace-letaido-marketers-agencies/)
- **2026-08-11**: Shipped Adaptive, a Site Explorer traffic model that factors in 15 SERP features including AI Overviews. [source](https://x.com/ahrefs/status/2087086648404103194)
- **2026-08-08**: Added Brand Radar reports to Report Builder's AI visibility widget, carrying over tracked prompts, tags, and project scope. [source](https://x.com/ahrefs/status/2086090063960563967)
- **2026-08-06**: Rebased Brand Radar prompt volumes from raw Google search volume to a figure adjusted by each AI platform's usage relative to Google. [source](https://x.com/ahrefs/status/2085287428550496326)
- **2026-07-30**: Site Explorer's Top Pages report began showing how many AI responses each page appears in, across platforms. [source](https://ahrefs.com/blog/new-features/)

## Company, Financials & Funding History

Founded in 2010 by Dmytro Gerasymenko, who remains CEO. Headquartered in Singapore, bootstrapped, and still private.


## Links

[Homepage](https://ahrefs.com) · [Pricing](https://ahrefs.com/pricing) · [LinkedIn](https://www.linkedin.com/company/ahrefs)

*Last updated 2026-09-27 · refreshed weekly*

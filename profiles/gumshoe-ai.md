> **Canonical source:** [https://stack.adamgtm.com/gumshoe-ai/](https://stack.adamgtm.com/gumshoe-ai/). This file is the agent-ready mirror; the website is the source of truth, kept continuously updated.

<!-- canonical: https://stack.adamgtm.com/gumshoe-ai/ · last updated 2026-06-06 -->
<!-- agent-readable twin, maintained by Adam's GTM Report · refreshed weekly. -->
# Gumshoe AI

Pure-play AEO/GEO analytics that simulates buyer conversations across AI models to show how a brand gets mentioned, recommended, and cited. $2M pre-seed led by Pioneer Square Labs. Pay-as-you-go pricing ($0.10/conversation) with the first three reports free. Recent work: a joint SparkToro study on how many queries it takes to measure AI visibility with confidence, and a published Gumshoe AI Manual.


## Scores

| Score | Value | Why |
|---|---|---|
| Presence | 55 | Early-stage ($2M pre-seed), but credible founders + real press; broad freemium reach |
| Velocity | 45 | Steady research/content cadence; no major product launches since the raise |
| Agent-Readiness | Low | API in development; no MCP/SDK/CLI; no root llms.txt |

*Product-overall scores from the AdamGTM Analyst Desk (floor 50). Canonical, always-current: https://stack.adamgtm.com/aeo*

## The Solution & Approach

Gumshoe is a measurement-first AEO/GEO tool. It generates representative buyer personas for a market, then runs thousands of structured conversations as those personas across 11 AI models — the GPT family, Gemini, Claude, Perplexity, Grok, DeepSeek, and Google AI Overviews — via direct API connections rather than scraping. The output is a Brand Visibility Score (the share of AI responses that mention a brand), broken down per-model, per-persona, and per-topic, plus share-of-voice against up to 30 competitors and citation tracking that shows which sources and pages AI draws from.

The category POV is statistical, not anecdotal. A single AI answer is noisy and rarely repeats, so Gumshoe's pitch is that visibility only becomes a reliable signal once you run enough conversations for the frequency to converge. The company has leaned into that argument publicly — a joint research piece with SparkToro frames AI visibility as a measurable probability you can estimate with standard statistics, and warns marketers against tracking off one or two queries.

Beyond measurement it has an optimization layer: an AI Optimization (AIO) score across categories like structured data, content clarity, and citation readiness, page audits, and AI-assisted content generation (for example, FAQs written for AI crawlers). The stated ambition is "the operating system for AI visibility," but today the center of gravity is the report.

## Best for

Marketers, PR/comms teams, and agencies who want a low-commitment, pay-per-report way to see how a brand shows up across many AI models — without a seat-based subscription or an enterprise contract.

## Pricing & trial

Pay-as-you-go, not a monthly subscription. Every account gets its first three report runs free (one free report for non-business email domains), then it's roughly $0.10 per conversation, where a conversation is one prompt paired with one model's answer. Enterprise plans are sales-led (hello@gumshoe.ai). [gumshoe.ai/pricing](https://www.gumshoe.ai/pricing).

## Agent Experience

How you build on this platform (or wire it into your own agents):

| Surface | Available | Docs |
|---|---|---|
| API | In development | — |
| MCP | No | — |
| SDK | No | — |
| CLI | No | — |
| llms.txt | No (root 404) | — |

Not a build-on-top platform today. Gumshoe describes its API as "in development," and there is no MCP server, SDK, or CLI. Reports export as JSON (visibility scores, prompts, responses, timestamps), so the data is portable even though programmatic access isn't live yet. There's a reference doc at [resources.gumshoe.ai/llminfo.md](https://resources.gumshoe.ai/llminfo.md), but no hosted `llms.txt` at the root.

## Reference customers

No public named-logo roster. The company reports 7,500+ brands and agencies on the platform — but this reflects freemium signups and report runs (the first three reports are free), not paying or contracted customers, so treat it as reach, not revenue.

## Case studies & customer stories

No published customer case studies found. The most cited external work is research-driven: a joint study with SparkToro on the consistency of AI brand recommendations. [source](https://sparktoro.com/blog/new-research-ais-are-highly-inconsistent-when-recommending-brands-or-products-marketers-should-take-care-when-tracking-ai-visibility/)

## Recent moves

- **2026-02-11**: Published "How Much Data Do You Need to Measure AI Visibility with Confidence?" — a joint study with SparkToro on consistency of AI brand recommendations and the statistics of visibility measurement. [source](https://gumshoe.ai/blog/how-much-data-do-you-need-to-measure-ai-visibility-with-confidence/)
- **2026-01-22**: Published the Gumshoe AI Manual, a guide on AI search visibility and why traditional SEO isn't enough when LLMs answer directly. [source](https://gumshoe.ai/blog/gumshoe-ai-manual-mastering-visibility-growth-in-the-ai-search-era/)
- **2026-01-20**: Published "How APIs Unlock Better Insights Into AI Search Visibility," arguing API responses beat web-interface results for monitoring. [source](https://gumshoe.ai/blog/)
- **2025-05-01**: Announced a $2M pre-seed led by Pioneer Square Labs to help marketers navigate AI search; entered public beta with hundreds of companies and planned a commercial model for summer 2025. [source](https://gumshoe.ai/blog/gumshoe-raises-2m-pre-seed-to-help-marketers-navigate-ai-search/)

## Company, Financials & Funding History

Founded in 2025 at Pioneer Square Labs in Seattle by Todd Sawicki (CEO; previously CEO of content-marketing platform Zemanta and a revenue lead at Cheezburger) and Patrick O'Donnell (co-founder of Urbanspoon, MightyAI, and Fresh Chalk). Early leadership also includes Stan Chang (Head of Product, ex-Redfin/Moloco/Microsoft) and Jim Watson (CRO, ex-Foursquare/Placed).

| Date | Round | Amount |
|---|---|---|
| 2025-05 | Pre-seed | $2M led by Pioneer Square Labs, with Hawke Ventures and angels including Ari Paparo and former execs from Google, LinkedIn, Meta, and X |

## Analyst placement

No G2 Grid placement or analyst recognition found as of this writing. Gumshoe is early-stage and pre-dates the major AEO analyst grids' coverage of long-tail entrants.

## Links

[Homepage](https://gumshoe.ai) · [Pricing](https://www.gumshoe.ai/pricing) · [Blog](https://gumshoe.ai/blog/) · [PSL profile](https://www.psl.com/companies/gumshoe)

*Last updated 2026-06-06 · refreshed weekly*

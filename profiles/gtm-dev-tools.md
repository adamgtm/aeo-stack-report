> **Canonical source:** [https://stack.adamgtm.com/gtm-dev-tools/](https://stack.adamgtm.com/gtm-dev-tools/). This file is the agent-ready mirror; the website is the source of truth, kept continuously updated.

<!-- canonical: https://stack.adamgtm.com/gtm-dev-tools/ · last updated 2026-06-13 -->
<!-- agent-readable twin, maintained by Adam's GTM Report · refreshed weekly. -->
# GTM Developer Tools

**This report maps the developer tools that are becoming GTM tools — the stack a go-to-market team now runs through a coding agent instead of buying as one vertical SaaS.** Continuously updated.

A **coding agent** (Claude Code, Codex, Cursor) sits in the middle. Around it are the primitives it calls to do real GTM work: search and scrape the web, drive UIs that have no API, enrich and score accounts, orchestrate and deploy jobs, persist memory, and pull in open-source skill packs. Below it sits the traditional GTM SaaS — but only the products that grew a real headless interface (MCP, API, CLI, SDK) the agent can actually drive.

## Why this matters in 2026

The workflow layer is moving. The work that used to require a purpose-built GTM SaaS — build a list, enrich it, segment it, write the copy, push the send — is increasingly something an operator assembles by pointing a general-purpose coding agent at a handful of API-first primitives. The agent is the orchestrator; the tools underneath are the muscles.

That reframes the buy decision. The question is no longer "which GTM SaaS do I buy." It is "which work do I orchestrate with an agent over cheap primitives, and which incumbents have a headless interface good enough to keep in the loop." We track that interface directly: of the companies in our index, **179 expose at least one agent surface and 130 expose an MCP server** — the strongest signal that a vendor is building for a world where the buyer is an agent.

The tools that win this transition tend to live in two rows at once: a primitive the agent calls *and* a product with a UI and an MCP server. Clay is the cleanest example — both an enrichment API and a headless SaaS. The borderline cases (BuiltWith, Parallel Web Systems, Browser Use) are where "dev tool" and "GTM tool" stop being different categories.

## How to read the map

Two reads on every tool:

- **Type** — *Broad* (a general developer tool usable in any vertical) or *GTM* (built for go-to-market specifically). The thesis is the blue eating the orange: broad agents and primitives absorbing GTM-specific workflows.
- **Surfaces** — the agent interfaces a tool exposes: **API · MCP · CLI · SDK**. This is the agent-readiness lens. A GTM SaaS with no surface is invisible to the stack above it.

## Six jobs around the agent

- **Web Search & Scraping** — get external data on demand.
- **Computer Use** — drive the UIs that never shipped an API.
- **Enrichment & Signals** — data-as-API: who to reach, and why now.
- **Orchestration & Deployment** — run, schedule, and host the agent's work.
- **Data & Memory** — persist state between runs so the agent stops re-deciding.
- **OSS GTM Agent Skills** — open packages and MCP servers that teach an agent how to do GTM.

## FAQ

**Is this a developer-tools map or a GTM map?** Both, and that is the point. The hub and most primitives are horizontal developer infrastructure; the enrichment box and the entire SaaS foundation are GTM-specific. The story is the overlap.

**What makes a SaaS "headless"?** A real, documented agent surface — MCP, API, CLI, or SDK — that lets an agent operate the product without a human clicking. We read it off each vendor's own docs and track it per company.

**How is this kept current?** The agent-surface flags refresh on the same nightly cadence as the rest of the index, so the foundation bar tracks vendors as they ship MCP servers and APIs.

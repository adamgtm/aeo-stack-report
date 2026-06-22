> **Canonical source:** [https://stack.adamgtm.com/gtm-dev/](https://stack.adamgtm.com/gtm-dev/). This file is the agent-ready mirror; the website is the source of truth, kept continuously updated.

<!-- canonical: https://stack.adamgtm.com/gtm-dev/ · last updated 2026-06-16 -->
<!-- agent-readable twin, maintained by Adam's GTM Report · refreshed weekly. -->
# GTM Developer Tools Map

**The stack you built in 2020 is for a different world.** Coding agents are the new center of the GTM stack. The sales and marketing tools for 2026 are ones an agent can find, access, and use.

I call this new category "GTM Developer Tools."

Agents are now the orchestrator of the stack, and they don't care about human usability ratings or Gartner grids. They care about which tools they can access to hit a goal. And builders are taking over the GTM org: GTM engineers, marketing engineers, applied-AI roles, plus any operator with Claude Code or Codex open. 

## How to read the map

- **Center** — coding agents (Claude Code, Codex, Cursor) and agent builders (LangChain, Lindy, Dust). This is what runs the work. Everything else orbits it.
- **The eight jobs** — the primitives an agent calls: Web Search & Scraping, Computer Use, Data/Enrichment & Signals, Communication Infra, Orchestration, Deployment, Data Storage & Memory, Agent Tooling.
- **SaaS going headless** — traditional GTM SaaS, on the map only where it went headless. A vendor with no surface an agent can call is invisible to the stack above it.

Download it, give it to Claude, make it your own. What's missing from this picture?

## Methodology {: #methodology .methodology-doc }

### What's covered

A tool earns a spot if an agent can access it or call it to do go-to-market work. This include boths GTM-specific tools (e.g. Clay, People Data Labs, Resend,) as well as board dev tools with clear GTM use cases in this new paradigm (e.g. Supabase, Exa, Apify, Parallel Web Systems) Three layers:

- **Center** — the coding agents and agent builders that run the work.
- **The eight jobs** — the primitives the agent calls to get GTM done.
- **SaaS going headless** — traditional GTM SaaS, included only when it exposes a real headless surface: MCP, API, CLI, SDK.

### The categories

To start, this GTM Developer Tools market map covers the following categories. This will likely expand as I monitor the space and update these resources.

- **Coding Agents** — the orchestrator at the center: Claude Code, Codex, Cursor.
- **Agent Builders** — frameworks to build your own: LangChain, Lindy, Dust.
- **Web Search & Scraping** — find and pull external data on demand: Firecrawl, Exa.ai, Apify.
- **Computer Use** — drive the UIs that never shipped an API: Browserbase, Browser Use, Kernel.
- **Data, Enrichment & Signals** — companies, people, events, intent: Clay, People Data Labs, LeadMagic.
- **Communication Infra** — programmatically send email, SMS, voice: Twilio, Resend, ElevenLabs.
- **Orchestration** — coordinate and manage agent workflows: n8n, Temporal, Trigger.dev.
- **Deployment** — run, host, and sandbox the work: Vercel, Railway, Modal.
- **Data Storage & Memory** — persist state between runs: Supabase, Pinecone, Redis.
- **Agent Tooling** — MCP servers and the agent's toolbelt: Composio, Arcade.dev, Smithery.
- **Traditional GTM SaaS** — GTM SaaS that went headless: Salesforce, HubSpot, Gong.

### Scores

Two scores help rank products, both relative across the tracked set.

**Agent Readiness. 0-100 Score, A–F Grade.** Analyst-judged based on deep dive of agent surfaces and documentation: did the vendor actually move for agents? A first-party MCP server, a modern self-serve API or SDK or CLI, docs that expose the core value, and recent agent-era investment all push the grade up. A sales-gated integration API from 2018 does not. The detected surfaces are an input to the judgment, not a checkbox tally.

| Grade | Meaning                                                                    |
| ----- | -------------------------------------------------------------------------- |
| **A** | Genuinely agent-ready. The vendor moved.                                   |
| **B** | Real agent investment with a limiter, often gated access or thin coverage. |
| **C** | Partially callable. Useful surface, not yet agent-native.                  |
| **D** | Legacy or gated. Technically callable, built for a different era.          |
| **F** | UI-only. No usable agent-callable interface.                               |

**Panel Share of Voice (SOV). 0–100 Score.** How much the market talks about a tool, not how much the tool talks about itself. Earned mentions only, across the GTM operators, builders, investors, publications, and podcasts we track on LinkedIn, X, RSS, and podcasts over a trailing six months. A company's own posts are stripped out. Each mention is weighted by engagement, then indexed against the loudest tool in the panel. A 75 means strong earned presence relative to the loudest voice, not 75% share. 

Within each box, logos are sorted by a composite of those two scores plus the company's funding and scale, each scored as a percentile across the tracked set.

### Curation & research depth

Every row is web-verified against the vendor's own docs. Adam curates the entity set and the voice panel; agents do the research fan-out and scoring under analyst review. If a field can't be verified, it stays blank. 

The map is living and refreshes on a cadence as vendors ship MCP servers, APIs, and make moves in the market. 

### Corrections are welcome. 

Send any issues to adam at adamgtm.com. I verify them, write the fix back to the source layer, and regenerate the map.

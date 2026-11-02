> **Canonical source:** [https://stack.adamgtm.com/gtm-dev/](https://stack.adamgtm.com/gtm-dev/). This file is the agent-ready mirror; the website is the source of truth, kept continuously updated.

<!-- canonical: https://stack.adamgtm.com/gtm-dev/ · last updated 2026-10-28 -->
<!-- agent-readable twin, maintained by Adam's GTM Report · refreshed weekly. -->
# GTM Developer Tools

**Agents are the center of the new stack.** Everything else is something an agent uses: tools, skills, context and plumbing.

This is v2 of the map I started in June. It shows what your GTM agents run on.

I call this new category "GTM Developer Tools."

Agents don't care about human usability ratings or Gartner grids. They care about what they can reach: the tools they can call, the context they can read, and where they can run. And builders are taking over the GTM org: GTM engineers, marketing engineers, applied-AI roles, plus any operator with Claude Code or Codex open.

## How to read the map

Tools, skills, agents, context, plumbing.

- **Agents** are the center. Coding agents you build with: Claude Code, Codex, Cursor. Chat and personal agents you work with: ChatGPT, Claude, Gemini, Grok Bot. Custom agents are SDKs and frameworks you run yourself, like the Claude Agent SDK, the OpenAI Agents SDK and LangGraph. Agent builders are hosted harnesses: you build them, they run them. Agentforce, Agent Bricks, Cortex Agents, Swan, Lindy.
- **Agentic Workflows** sit beside them. Agents to build, workflows to run: Clay, n8n, Zapier, OXYGEN, Pancake.
- **Skills** are your playbooks, how your team does the work. They are mostly open source and things you write, so there are no logos here.
- **Tools** are what an agent calls: Data & Signals, Web Search & Scraping, Browsers & Computer Use, Communication. At the base are SaaS Platforms Going Headless: the tools you already pay for, now usable by agents through an API, an MCP server or a CLI.
- **Context** is Context & Memory: your warehouse, GTM context and memory. We know it's important. It's unclear how much you build and own versus buy, rent or integrate. Probably a hybrid.
- **Plumbing** is Connectors & MCP, plus Run & Deploy.

Get the [full dataset](/index/?cat=GTM%20Developer%20Tools#dataset), give it to Claude, make it your own. What's missing from this picture?

## Methodology {: #methodology .methodology-doc }

### What's covered

A tool earns a spot if an agent can access it or call it to do go-to-market work. This includes both GTM-specific tools (e.g. Clay, People Data Labs, Resend) and broad dev tools with clear GTM use cases in this new paradigm (e.g. Supabase, Exa, Apify, Parallel Web Systems). Four layers:

- **Agents** at the center, and the workflows that run alongside them.
- **Tools, context and plumbing** the agent calls to get GTM done.
- **SaaS Platforms Going Headless**: traditional GTM SaaS, included only when it exposes a real headless surface: MCP, API, CLI, SDK.
- **Skills**, which are yours, not a vendor category.

The rule for this map: a tool has to carry GTM Developer Tools (the outside boxes) or Coding Agents & Harnesses for GTM (the center box). AI-Native Challengers are not on this map unless the product itself is a developer tool or a GTM harness. SaaS Platforms Going Headless is the exception: it is SaaS samples with proof of an agent-ready surface, meaning an API, an MCP server or a CLI.

### The boxes

This map has 13 boxes. A tool can sit in more than one. Some are not scored yet: ChatGPT, Claude and Gemini are on the map but not in the tracked set.

- **Coding agents**: Claude Code, Codex, Cursor.
- **Chat & personal agents**: ChatGPT, Claude, Gemini, Grok Bot.
- **Custom agents**: Claude Agent SDK, OpenAI Agents SDK, LangGraph.
- **Agent builders**: Agentforce, Agent Bricks, Cortex Agents, Swan, Lindy.
- **Agentic Workflows**: Clay, n8n, Zapier.
- **Data & Signals**: Clay, People Data Labs, LeadMagic.
- **Web Search & Scraping**: Firecrawl, Exa, Apify.
- **Browsers & Computer Use**: Browserbase, Browser Use, Kernel.
- **Communication**: Twilio, Resend, ElevenLabs.
- **Context & Memory**: Snowflake, Octave, Supermemory.
- **Connectors & MCP**: Composio, Arcade, Smithery.
- **Run & Deploy**: Vercel, Railway, Modal.
- **SaaS Platforms Going Headless**: Salesforce, HubSpot, Gong.

The June map (v1) used different boxes. Each tool's June category is kept in the data.

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

Each box opens with the logos I picked to match the map graphic. The rest are sorted by a composite of those two scores plus the company's funding and scale, each scored as a percentile across the tracked set.

### Curation & research depth

Every row is web-verified against the vendor's own docs. Adam curates the entity set and the voice panel; agents do the research fan-out and scoring under analyst review. If a field can't be verified, it stays blank. 

The map is living and refreshes on a cadence as vendors ship MCP servers, APIs, and make moves in the market. 

### Corrections are welcome. 

Send any issues to adam at adamgtm.com. I verify them, write the fix back to the source layer, and regenerate the map.

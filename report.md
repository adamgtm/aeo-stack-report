> **Canonical source:** [https://stack.adamgtm.com/aeo/](https://stack.adamgtm.com/aeo/). This file is the agent-ready mirror; the website is the source of truth, kept continuously updated.

<!-- canonical: https://stack.adamgtm.com/aeo/ · last updated 2026-05-25 -->
<!-- agent-readable twin, maintained by Adam's GTM Report · refreshed weekly. -->
# AEO Tools, Build Stacks, and Agencies

**This report provides AEO market intelligence for agents and humans to evaluate approaches and options.** This resource is continuously updated and explores 3 options for AEO: Buy, Build, and Hire. 

[Download the full dataset + markdown library →](#download)

**AEO** (answer engine optimization), also called **GEO** (generative engine optimization), is the practice of getting your brand cited in AI-generated answers: ChatGPT, Google AI Overviews, Perplexity, Claude, Gemini. SEO earned blue-link rankings. AEO earns the citation inside the answer.

## Why AEO matters in 2026

The shift is driven by buyer behavior, not vendor roadmaps. Buyers have moved from scanning ten blue links to reading one synthesized answer, and increasingly hand the research to an agent. The academics were early: Princeton and IIT Delhi coined "Generative Engine Optimization" in a peer-reviewed [KDD 2024 paper](https://arxiv.org/abs/2311.09735), built the first benchmark, and measured visibility lifts of up to 40% from the right optimizations.

It now shows up in hiring. Stripe is hiring an [AEO/GEO Marketing Manager](https://stripe.com/jobs/search?gh_jid=7844214); so are Hex, ClickHouse, and OneTrust. We count 59 such roles across 49 companies in our jobs tracker. Brex is hiring a [Director of Organic Growth & Discoverability](https://www.brex.com/careers/8522918002?gh_jid=8522918002) to "own how Brex shows up in ChatGPT, Perplexity, Gemini." When companies that don't sell AEO budget headcount for it, the category is real.

### Market POV & conversations

The clearest sign AEO is a real category, not jargon, is that serious people are arguing about it, and the argument has moved out of the SEO world into GTM strategy. The split:

- **Evolution, extend your SEO.** Guy Yalif (Webflow): "Your SEO resources are your AEO resources. This is an evolution, not a reset." Backed by Aleyda Solis and Jason Lemkin's [SEO-to-AI-search correlation data](https://www.linkedin.com/pulse/sem-rush-you-get-top-10-seo-probably-ai-search-too-jason-m-lemkin-vpfwc).
- **Reset, different game.** Mike King (iPullRank) reframes it as "relevance engineering." Rand Fishkin [publicly changed his mind](https://www.linkedin.com/posts/randfishkin_getting-your-brand-into-chatgpt-claude-activity-7421651332899631105-dXW-) after watching King present. Eli Schwartz calls the SEO-vs-AEO comparison "a trap... closer to brand marketing."

And it's in the GTM conversation, not just SEO Twitter:

- **Kyle Poyar** asked 195 B2B GTM leaders where they're betting in 2026; the [top two answers](https://www.linkedin.com/posts/kyle-poyar_i-asked-195-b2b-go-to-market-leaders-about-activity-7434235692605509632-P58A) were AI discovery (AEO) and intent-based outbound.
- **Dave Gerhardt** (Exit Five): "[Teams that rely on MQLs and content downloads to nurture leads are in big trouble.](https://www.linkedin.com/posts/davegerhardt_i-dont-think-people-realize-how-big-of-a-activity-7461007518966779904-Qh-t)"
- **Eric Linssen** (Demand Collective), names AEO [one of only two AI use cases](https://www.linkedin.com/posts/eric-linssen-b2985b132_a-pickle-im-seeing-marketers-in-right-now-activity-7448432368962531328-h4Ov) actually driving pipeline.
- **Ethan Smith** (Graphite) on Lenny's Podcast: Webflow saw [a 6x conversion difference](https://www.lennysnewsletter.com/p/the-ultimate-guide-to-aeo-ethan-smith) between LLM traffic and Google traffic, and early-stage companies can win citations quickly.



## How to evaluate (Buy vs Build vs Hire)

The real question is not which vendor fits. It's which *approach* fits, then which player within it. A quick read:

- **Buy** if you want time-to-value and a managed surface, and you have budget for a platform.
- **Build** if you have a technical or GTM-engineering team and want control plus lower cost.
- **Hire** if you want outcomes without staffing it, or want senior strategy on top of a tool.

We score the players on three axes built for this market (not Gartner's static snapshot):

- **Presence**: where they stand in the consensus now (share of voice, mentions, funding, logos).
- **Velocity**: how fast they're moving (shipping cadence from our evidence trail). The dimension a yearly analyst snapshot can't capture.
- **Agent-Readiness**: how well you can build on them (API, MCP, SDK, CLI, docs). The lens that matters when your buyers are agents.

## Buy: specialist platforms

| Vendor                       | Founded | Raised       | Best for                 | The angle                                       | Try it     |
| ---------------------------- | ------- | ------------ | ------------------------ | ----------------------------------------------- | ---------- |
| [Profound](/profound/) | 2023    | $155M        | Enterprise, full-stack   | Measurement + automation + citation marketplace | Sales-led  |
| [Bluefish](/bluefish-ai/)                     | 2024    | $68M         | Fortune 500 brands       | Brand protection / claim verification           | Sales-led  |
| [Evertune](/evertune/)                     | 2024    | $19M         | Stats-grade measurement  | 100K+ prompts/report; adtech DNA                | Sales-led  |
| [Scrunch](/scrunch-ai/)                      | 2023    | $19M         | Getting served to agents | Optimization for how AI fetches you             | Self-serve |
| [Peec](/peec-ai/)                         | 2025    | $29M         | Mid-market, fast         | Analytics + competitor benchmarking             | Self-serve |
| [AthenaHQ](/athenahq/)                     | 2024    | ~$3M         | Mid-market entry         | Lean SEO + GEO services platform                | Self-serve |
| [AirOps](/airops/)                          | 2022    | $62M         | Content + AEO workflows  | Build AI content workflows; agent-ready         | Sales-led  |
| [Goodie AI](/goodie-ai/)                    | 2023    | Bootstrapped | Commerce + model breadth | 11 engines tracked + agentic fixes              | Self-serve |
| [OtterlyAI](/otterly-ai/)                    | 2024    | Bootstrapped | Solo marketer / SMB      | "Semrush for AI search," $29/mo                 | Free trial |

Or let a tool you already own absorb it: HubSpot, [Adobe (LLM Optimizer)](/adobe-llm-optimizer/), and the SEO incumbents retrofitting (Ahrefs, BrightEdge, Conductor, Siteimprove, Botify).

**Who's getting picked.** G2's first AEO Grid (Dec 2025) named Profound the lone Leader, with Otterly and Scrunch as High Performers. Gartner named Otterly a Cool Vendor; Forrester gave Botify a Strong Performer.

## Build: on primitives, with agents and OSS

A real third option in 2026. The edge is control and cost; the cost is you own the upkeep. Start with one job, usually measurement, prove it, then expand. Four ways in:

- **Build on managed primitives.** [Clay's AEO playbook](https://www.clay.com/blog/how-clay-uses-clay-for-seo-and-aeo) is the blueprint: an AI-visibility dashboard assembled on Clay, Supabase, Claude Code, and Vercel. You get the B2B data and orchestration without writing the hard parts.
- **Drop skills into your coding agent.** Skill packs like [seo-geo-claude-skills](https://github.com/aaron-he-zhu/seo-geo-claude-skills) (1,761★) and [gtm-engineer-skills](https://github.com/onvoyage-ai/gtm-engineer-skills) (961★, MIT) add AEO audits and content workflows straight into Claude Code, Cursor, or Codex.
- **Run your own measurement.** [OpenRouter](https://openrouter.ai) gives you one API across GPT, Gemini, Perplexity, and Claude, enough to query the answer engines yourself and track who gets cited. It is how we built our own tracker for this guide.
- **Audit on the research.** [geo-optimizer-skill](https://github.com/Auriti-Labs/geo-optimizer-skill) (432★) implements the Princeton KDD 2024 methodology, the most academically grounded option.

The open-source space is moving fast. These are the projects worth knowing, grouped by what they do:

| Project | ★ | Type | What it does |
| ------- | - | ---- | ------------ |
| [seo-geo-claude-skills](https://github.com/aaron-he-zhu/seo-geo-claude-skills) | 1,761 | Skill pack | 20 SEO + GEO skills for Claude Code / Cursor / Codex |
| [gtm-engineer-skills](https://github.com/onvoyage-ai/gtm-engineer-skills) | 961 | Skill pack | GTM + AEO agent workflows, MIT-licensed |
| [codex-seo](https://github.com/AgriciDaniel/codex-seo) | 170 | Skill pack | Codex-first SEO suite; DataForSEO integration |
| [geo-optimizer-skill](https://github.com/Auriti-Labs/geo-optimizer-skill) | 432 | Audit | Implements the Princeton KDD 2024 AEO/GEO methodology |
| [geo-optimizer (Go)](https://github.com/geo-team-red/geo-optimizer) | 218 | Framework | Pluggable AEO/GEO framework for embedding in Go services |
| [geo-lint](https://github.com/IJONIS/geo-lint) | 22 | Audit | First open-source AEO/GEO linter; 92 rules, drops into CI |
| [geo-aeo-tracker](https://github.com/danishashko/geo-aeo-tracker) | 132 | Tracker | Local-first AI-visibility dashboard; "the simple Profound" |
| [elmo](https://github.com/elmohq/elmo) | 113 | Tracker | Open-source AI-visibility tracking |
| [oneglanse](https://github.com/aryamantodkar/oneglanse) | 61 | Tracker | Free, open-source AEO/GEO tracker across the major engines |
| [dualmark](https://github.com/dodopayments/dualmark) | 66 | Publisher-side | Serves markdown twins to agents alongside HTML, via content negotiation |
| [aeo-god-mode](https://github.com/AEO-God-Mode/aeo-god-mode) | 23 | Publisher-side | WordPress plugin: schema, llms.txt, AI-crawler controls |
| [AutoGEO](https://github.com/cxcscmu/AutoGEO) | 152 | Research | ICLR'26 framework that learns AEO/GEO strategies automatically |

The full landscape, 40+ projects including the academic papers and curated awesome-lists, lives on the [Open Source AEO Projects & Resources](/aeo-open-source/) page, and ships in the [downloadable library](#download).

## Hire: agencies

Two kinds: the SEO old guard repointing a decade of muscle, and the AI-native upstarts. Most run a platform underneath (their own build, or Profound / AirOps), so you are paying for the expertise on top. Two questions to ask any of them: what platform do you run underneath, and do we keep the system when the engagement ends?

| Agency                              | Lead                | Origin               | The pitch                                                                     |
| ----------------------------------- | ------------------- | -------------------- | ----------------------------------------------------------------------------- |
| [Graphite](/graphite/)     | Ethan Smith         | Growth / SEO         | Operator method; controlled testing; the "6x LLM-vs-Google conversion" data   |
| [iPullRank](/ipullrank/)   | Mike King           | Technical SEO        | "Relevance engineering"; runs SEO Week; 2025 AI Search Marketer of the Year   |
| [Animalz](/animalz/)       | —                   | B2B SaaS content     | Premium expert-interview content; AEO audit → 90-day roadmap                  |
| [Foundation](/foundation/) | Ross Simmonds       | Content distribution | Distribution-led AEO/GEO; "Create Once, Distribute Forever"                       |
| [daydream](/daydream/)     | Thenuka Karunaratne | AI-native            | Agency-as-product: agents plus a human lead; $21M raised, YC's #3 most-wanted |

## AEO is six jobs, not one

Most platforms nail one or two. Measurement is already commoditizing. Source acquisition (getting cited by the publishers and review corpora the models trust) is the piece with real network effects, because citations compound.

1. Measure
2. Diagnose
3. Optimize content
4. Optimize infrastructure
5. Source acquisition
6. Automate the loop

## Get the full library

Deep dives on every platform, build resource, and agency: scores, funding, customers, pricing, analyst placement, and the claim each one makes. Plus the raw dataset (CSV) and an agent-readable markdown library.

[Download the full library (.zip)](/downloads/aeo-stack-library.zip) · [raw dataset (CSV)](/downloads/vendors.csv)

## FAQ

**What is AEO?** Getting your brand cited in AI-generated answers (ChatGPT, Perplexity, Claude, Google AI Overviews) the way SEO earned blue-link rankings.

**AEO vs GEO?** Used interchangeably. GEO is the term Princeton's KDD 2024 paper coined; AEO is what most marketers say. Same job: be the source the model cites.

**Should I buy, build, or hire?** Buy for time-to-value, build if you have a technical team and want control, hire for outcomes without staffing it. Most teams start by measuring, then pick.

**What are the best AEO tools?** G2's AEO Grid (Dec 2025): Profound (Leader), Otterly and Scrunch (High Performers). Specialists: Profound, Bluefish, Evertune, Scrunch, Peec, AthenaHQ, Otterly.

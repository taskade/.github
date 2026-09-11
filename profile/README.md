```
╔══════════════════════════════════════════════════════════════════════════╗
║                                                                          ║
║   ████████  █████  ███████ ██   ██  █████  ██████  ███████               ║
║      ██    ██   ██ ██      ██  ██  ██   ██ ██   ██ ██                    ║
║      ██    ███████ ███████ █████   ███████ ██   ██ █████                 ║
║      ██    ██   ██      ██ ██  ██  ██   ██ ██   ██ ██                    ║
║      ██    ██   ██ ███████ ██   ██ ██   ██ ██████  ███████               ║
║                                                                          ║
║              One prompt → one app. Build without permission.             ║
║                                                                          ║
╚══════════════════════════════════════════════════════════════════════════╝
```

<p align="center">
  <a href="https://taskade.com"><b>Website</b></a> · <a href="https://docs.taskade.com"><b>API Docs</b></a> · <a href="https://www.taskade.com/docs"><b>Developer docs</b></a> · <a href="https://www.taskade.com/blog"><b>Blog</b></a> · <a href="https://www.taskade.com/apps"><b>Apps</b></a> · <a href="https://reddit.com/r/taskade"><b>Forum</b></a> · <a href="https://youtube.com/taskade"><b>YouTube</b></a> · <a href="https://x.com/taskade"><b>X / Twitter</b></a>
</p>

---

<div align="center">
  <img src="https://raw.githubusercontent.com/taskade/taskade/main/media/genesis/create-app.gif" alt="Taskade Genesis — Build AI apps from a single prompt" width="720">
  <br><br>
  <b>150,000+ apps generated</b> · <b>500K+ agents deployed</b> · <b>3M+ automation runs</b><br>
  Trusted by teams at <b>3M</b> · <b>Nike</b> · <b>Tesla</b> · <b>Netflix</b> · <b>Airbnb</b> · <b>Disney</b> · <b>Adobe</b> · <b>ESPN</b> · Rated <b>4.8/5</b> across 9,300+ reviews
</div>

> **TL;DR:** Taskade Genesis turns one prompt into a live, multiplayer app — projects as memory, agents as intelligence, automations as execution. **150,000+ apps generated.** No code, no deploy step: clone a ready kit at [taskade.com/apps](https://www.taskade.com/apps) or build from scratch at [taskade.com/create](https://www.taskade.com/create).

---

## What is Taskade?

Taskade is the **execution layer for ideas** — a real-time collaborative workspace where AI agents build, automate, and run live applications from a single prompt. No code. No deployment. No permission required.

```
   Describe what you want
          │
          ▼
  ┌───────────────┐       ┌───────────────┐       ┌───────────────┐
  │   GENERATE    │──────▶│    BUILD      │──────▶│     RUN       │
  │               │       │               │       │               │
  │  AI interprets│       │  App assembles│       │  Live at a    │
  │  your intent  │       │  in real time │       │  shareable URL│
  └───────────────┘       └───────────────┘       └───────────────┘
```

### FAQ

| Question | Answer |
|----------|--------|
| **What is Taskade Genesis?** | One prompt becomes a live app — memory, agents, and automations already wired. Start at [taskade.com/create](https://www.taskade.com/create). |
| **What is Workspace DNA?** | Memory + Intelligence + Execution — the loop every Taskade app runs on. |
| **Does Taskade have an MCP server?** | Yes. Official server: [taskade/mcp](https://github.com/taskade/mcp). Install with `npx @taskade/mcp-server@latest`. |
| **What's free vs Pro?** | Free is $0 with 2 workspace members and 1 agent. Pro is **$10/seat/mo billed annually**, capped at 10 seats. Full matrix: [taskade.com/pricing](https://www.taskade.com/pricing). |
| **Can I build a client portal from a prompt?** | Yes. Describe it; Genesis builds it live. Clone examples at [taskade.com/apps](https://www.taskade.com/apps). |
| **Where do I clone apps?** | [taskade.com/apps](https://www.taskade.com/apps). |

---

## Workspace DNA — How It Works

Every Taskade workspace is a living system built on three pillars:

```
┌─────────────────────────────────────────────────────────────────────────┐
│                       WORKSPACE DNA                                     │
│               The architecture behind every Taskade app                 │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                         │
│   ┌───────────────────┐  ┌───────────────────┐  ┌───────────────────┐   │
│   │      MEMORY       │  │   INTELLIGENCE    │  │    EXECUTION      │   │
│   │    ┌─────────┐    │  │    ┌─────────┐    │  │    ┌─────────┐    │   │
│   │    │Projects │    │  │    │   AI    │    │  │    │Workflows│    │   │
│   │    │   as    │    │  │    │ Agents  │    │  │    │   that  │    │   │
│   │    │  live   │    │  │    │  that   │    │  │    │  run    │    │   │
│   │    │databases│    │  │    │  think  │    │  │    │24 / 7   │    │   │
│   │    └─────────┘    │  │    └─────────┘    │  │    └─────────┘    │   │
│   │                   │  │                   │  │                   │   │
│   │ • Structured data │  │ • Reasoning       │  │ • Triggers        │   │
│   │ • Real-time sync  │  │ • Planning        │  │ • Actions         │   │
│   │ • Version history │  │ • Context-aware   │  │ • 100+ services   │   │
│   │ • OT conflict res │  │ • Multi-model     │  │ • Durable engine  │   │
│   └───────────────────┘  └───────────────────┘  └───────────────────┘   │
│            ▲                      ▲                      ▲              │
│            └──────────────────────┴──────────────────────┘              │
│                         Continuous Feedback Loop                        │
│                    Results → Memory → Smarter Agents                    │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

| Pillar | What it does | In practice |
|--------|-------------|-------------|
| **Memory** | Projects are live, queryable databases — not static docs | Your data powers your apps in real time |
| **Intelligence** | AI agents that reason, plan, and act across your workspace | Agents handle updates, research, and decisions autonomously |
| **Execution** | Workflows that connect [100+ services](https://www.taskade.com/integrations) and run themselves | Automations trigger on events and adapt over time |

---

## Taskade Genesis — Build Apps from Prompts

[Genesis](https://www.taskade.com/create) turns natural language into fully functional applications:

```
┌─────────────────────────────────────────────────────────────────────────┐
│                       GENESIS APP BUILDER                               │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                         │
│   PROMPT                        APP                                     │
│   ──────                        ───                                     │
│                                                                         │
│   "Build a customer             ┌──────────────────────────────┐       │
│    dashboard with               │  Customer Dashboard    [Live] │       │
│    live metrics"                │                              │       │
│         │                       │  ┌────────┐  ┌────────┐      │       │
│         │   ┌──────────┐        │  │ Active │  │Revenue │      │       │
│         └──▶│ Genesis  │───────▶│  │  142   │  │ $48.2K │      │       │
│             │  Engine  │        │  └────────┘  └────────┘      │       │
│             └──────────┘        │                              │       │
│                                 │  ┌──────────────────────┐    │       │
│                                 │  │ ████████░░░░  67%    │    │       │
│                                 │  │ Satisfaction Score   │    │       │
│                                 │  └──────────────────────┘    │       │
│                                 │                              │       │
│                                 │  Recent Activity             │       │
│                                 │  ├─ New signup: Acme Corp    │       │
│                                 │  ├─ Ticket resolved: #1042   │       │
│                                 │  └─ Agent completed task     │       │
│                                 └──────────────────────────────┘       │
│                                                                         │
│   Features:                                                             │
│   • Custom domains (yourapp.taskade.host)                               │
│   • Real-time data from your workspace                                  │
│   • AI agents handle ongoing updates                                    │
│   • Version history + instant rollback                                  │
│   • Publish to global edge network                                      │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## What You Can Build

| Client Portal | CRM Dashboard | Storefront |
|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/taskade/taskade/main/media/apps/client-portal.gif" width="280" alt="Client portal built with Taskade Genesis"> | <img src="https://raw.githubusercontent.com/taskade/taskade/main/media/apps/crm-dashboard.gif" width="280" alt="CRM for sales teams built with Taskade Genesis"> | <img src="https://raw.githubusercontent.com/taskade/taskade/main/media/apps/storefront.gif" width="280" alt="Storefront built with Taskade Genesis"> |

Explore and clone ready-made AI app kits from **[Taskade Apps](https://www.taskade.com/apps)**:

| Category | Examples | How It Works |
|----------|----------|-------------|
| [**Dashboards**](https://www.taskade.com/apps/dashboards) | KPI trackers, analytics panels, team metrics | Projects sync as live data sources |
| [**Tools**](https://www.taskade.com/apps/tools) | CRM views, inventory systems, admin panels | AI agents keep data current |
| [**Websites**](https://www.taskade.com/apps/websites) | Landing pages, portfolios, status pages | Shareable URLs with custom domains |
| [**Projects**](https://www.taskade.com/apps/projects) | Task boards, roadmaps, sprint plans | Real-time collaborative project management |
| [**Workflows**](https://www.taskade.com/apps/workflows) | Lead routing, content pipelines, approval chains | Durable automation across [100+ services](https://www.taskade.com/integrations) |
| [**Forms**](https://www.taskade.com/apps/forms) | Surveys, applications, feedback collectors | Submissions flow into live project databases |
| [**Commerce**](https://www.taskade.com/apps/commerce) | Storefronts, order trackers, product catalogs | End-to-end commerce powered by AI |
| [**Quick Apps**](https://www.taskade.com/apps/quick-apps) | Calculators, converters, mini-tools | Instant single-purpose apps from a prompt |

---

## AI Agents — Your Autonomous Workforce

<div align="center">
  <img src="https://raw.githubusercontent.com/taskade/taskade/main/media/agents/model-selector.gif" alt="Pick your AI model per agent — 15+ frontier models from OpenAI, Anthropic, and open-weight providers" width="600">
</div>

<br>

```
 ┌──────────────────────────────────────────────────────────────────┐
 │                      AI AGENT SYSTEM                             │
 │                                                                  │
 │   ┌──────────┐    ┌──────────┐    ┌──────────┐    ┌──────────┐ │
 │   │ Research │    │  Write   │    │ Automate │    │  Build   │ │
 │   │  Agent   │    │  Agent   │    │  Agent   │    │  Agent   │ │
 │   │          │    │          │    │          │    │          │ │
 │   │ Web      │    │ Content  │    │ Workflow │    │ App      │ │
 │   │ search,  │    │ drafts,  │    │ triggers,│    │ genesis, │ │
 │   │ analyze, │    │ reports, │    │ actions, │    │ iterate, │ │
 │   │ summarize│    │ refine   │    │ connect  │    │ deploy   │ │
 │   └──────────┘    └──────────┘    └──────────┘    └──────────┘ │
 │         │               │               │               │      │
 │         └───────────────┴───────────────┴───────────────┘      │
 │                              │                                  │
 │                     ┌────────┴────────┐                         │
 │                     │  Your Workspace │                         │
 │                     │    (Memory)     │                         │
 │                     └─────────────────┘                         │
 │                                                                  │
 │   • Multi-agent collaboration — agents work together            │
 │   • Context-aware — reads your entire workspace                 │
 │   • Multi-model — 15+ frontier models                           │
 │   • Custom tools — web search, project management, code exec    │
 │   • Always learning — results feed back into workspace memory   │
 │                                                                  │
 └──────────────────────────────────────────────────────────────────┘
```

---

## Open Source

Taskade builds in the open. Star the repos that are useful to you:

| Repository | Description | |
|------------|-------------|---|
| [`taskade/mcp`](https://github.com/taskade/mcp) | Official MCP server + OpenAPI-to-MCP codegen. Connect Taskade to Claude, Cursor, and more. | ![GitHub stars](https://img.shields.io/github/stars/taskade/mcp?style=flat-square) |
| [`taskade/docs`](https://github.com/taskade/docs) | API documentation and developer guides | ![GitHub stars](https://img.shields.io/github/stars/taskade/docs?style=flat-square) |
| [`taskade/awesome-vibe-coding`](https://github.com/taskade/awesome-vibe-coding) | Curated list of tools and resources for vibe coding | ![GitHub stars](https://img.shields.io/github/stars/taskade/awesome-vibe-coding?style=flat-square) |
| [`taskade/taskade`](https://github.com/taskade/taskade) | Docs, guides, honest comparisons, and the clone-ready App Kits Gallery. | ![GitHub stars](https://img.shields.io/github/stars/taskade/taskade?style=flat-square) |
| [`taskade/temporal-parser`](https://github.com/taskade/temporal-parser) | ISO 8601 / RFC 3339 / IXDTF lexer+parser (pair with uri-parser). By [@lxcid](https://github.com/lxcid). | ![GitHub stars](https://img.shields.io/github/stars/taskade/temporal-parser?style=flat-square) |
| [`taskade/uri-parser`](https://github.com/taskade/uri-parser) | RFC 3986 URI lexer+parser — lossless AST, host-path, no-scheme (pair with temporal-parser). By [@lxcid](https://github.com/lxcid). | ![GitHub stars](https://img.shields.io/github/stars/taskade/uri-parser?style=flat-square) |
| [Integration Kit](https://github.com/taskade/integrations) | Public source-of-truth for Taskade actions & triggers (Zapier, n8n) built on the public API | ![GitHub stars](https://img.shields.io/github/stars/taskade/integrations?style=flat-square) |
| [Genesis Sample App](https://github.com/taskade/taskade-sample-app) | A Workspace DNA template for building AI-powered Taskade Genesis apps — one prompt to a working app | ![GitHub stars](https://img.shields.io/github/stars/taskade/taskade-sample-app?style=flat-square) |

<p align="center">
  <a href="https://github.com/taskade"><b>⭐ Star our repos on GitHub →</b></a>
</p>

### MCP Server — Connect Taskade to Any AI Tool

```
┌────────────────────────────────────────────────────────────────────┐
│                                                                    │
│   Claude Desktop ─┐                                                │
│                   │     ┌──────────────────┐     ┌─────────────┐   │
│   Cursor IDE ─────┼────▶│   taskade/mcp    │────▶│   Taskade   │   │
│                   │     │                  │     │  Workspace  │   │
│   Any MCP Client ─┘     │  Official MCP    │     │             │   │
│                         │  Server          │     │  Projects   │   │
│                         │                  │     │  Agents     │   │
│                         │  + OpenAPI-to-   │     │  Workflows  │   │
│                         │    MCP codegen   │     │  Genesis    │   │
│                         └──────────────────┘     └─────────────┘   │
│                                                                    │
│   Install:  npx @taskade/mcp-server@latest                         │
│                                                                    │
└────────────────────────────────────────────────────────────────────┘
```

---

## Developer Quick Start

### REST API

```bash
# Create a project
curl -X POST https://www.taskade.com/api/v1/projects \
  -H "Authorization: Bearer YOUR_API_TOKEN" \
  -H "Content-Type: application/json" \
  -d '{"title": "My Project", "folder_id": "FOLDER_ID"}'
```

### MCP Integration

```bash
# Install and configure
npx @taskade/mcp-server@latest
```

### Resources

| Resource | Link |
|----------|------|
| API Reference | [docs.taskade.com](https://docs.taskade.com) |
| Developer docs | [taskade.com/docs](https://www.taskade.com/docs) |
| Learn Taskade | [taskade.com/learn](https://www.taskade.com/learn) |
| MCP Server | [github.com/taskade/mcp](https://github.com/taskade/mcp) |
| Help Center | [help.taskade.com](https://help.taskade.com) |
| Genesis Guide | [Create Your First App](https://help.taskade.com/en/articles/11957643-create-your-first-app) |
| Workspace DNA | [How Genesis Works](https://help.taskade.com/en/articles/12578949-how-genesis-works-workspace-dna) |
| Custom AI Agents | [Agent Documentation](https://help.taskade.com/en/articles/8958457-custom-ai-agents) |
| Workflow Automation | [Automation Guide](https://help.taskade.com/en/articles/8958467-getting-started-with-automation) |
| Apps | [taskade.com/apps](https://www.taskade.com/apps) |
| Forum (Reddit) | [r/taskade](https://reddit.com/r/taskade) |

---

## Platform

```
 ┌─────────┐  ┌─────────┐  ┌─────────┐  ┌─────────┐  ┌─────────┐
 │   Web   │  │  macOS  │  │ Windows │  │   iOS   │  │ Android │
 │         │  │         │  │         │  │         │  │         │
 │ taskade │  │ Desktop │  │ Desktop │  │  App    │  │  App    │
 │  .com   │  │  App    │  │  App    │  │  Store  │  │  Store  │
 └─────────┘  └─────────┘  └─────────┘  └─────────┘  └─────────┘

 ┌─────────┐  ┌─────────┐  ┌─────────┐
 │ Chrome  │  │ Firefox │  │  Edge   │
 │         │  │         │  │         │
 │  Ext.   │  │  Ext.   │  │  Ext.   │
 └─────────┘  └─────────┘  └─────────┘
```

<p align="center">
  <a href="https://taskade.com/downloads">Download Taskade</a>
</p>

---

## Pricing

| Free | Pro | Business | Max | Enterprise |
|:---:|:---:|:---:|:---:|:---:|
| **$0** | **$10/seat/mo** | **$25/seat/mo** | **$100/seat/mo** | **$250/seat/mo** |

*Billed annually. Free includes 2 members. Pro is capped at 10 seats. [Compare all plans →](https://www.taskade.com/pricing)*

---

<p align="center">
  <b>Software should be built by everyone.</b><br>
  Creation should be instant. Apps should be alive.<br><br>
  <a href="https://www.taskade.com/create"><b>Build without permission →</b></a>
</p>

<p align="center">
  <a href="https://taskade.com">Website</a> · <a href="https://www.taskade.com/about">About</a> · <a href="https://docs.taskade.com">API</a> · <a href="https://www.taskade.com/docs">Developer docs</a> · <a href="https://www.taskade.com/apps">Apps</a> · <a href="https://reddit.com/r/taskade">Forum</a> · <a href="https://www.taskade.com/blog">Blog</a> · <a href="https://youtube.com/taskade">YouTube</a> · <a href="https://x.com/taskade">X / Twitter</a> · <a href="https://www.taskade.com/contact">Contact</a>
</p>

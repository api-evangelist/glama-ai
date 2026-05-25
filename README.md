# Glama (glama-ai)

Glama is an all-in-one AI workspace combining an MCP server marketplace and registry, a managed MCP gateway, one-click MCP server hosting, an OpenAI-compatible LLM gateway routing 90+ models across OpenAI, Anthropic, Google, DeepSeek, Mistral, xAI and other providers, and Glama Chat with built-in projects, memory, web tools, and automations. Glama positions itself as a superset of the official MCP Registry, with maintainer verification, continuous rebuilds, and capability-level quality scoring across 23,000+ MCP servers, 4,000+ managed connectors, and 169,000+ tools.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/glama-ai/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- AI, Artificial Intelligence, MCP, Model Context Protocol, LLM Gateway, MCP Gateway, MCP Marketplace, AI Workspace, Multi-Provider, OAuth, Observability

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Glama AI Gateway
OpenAI-compatible LLM gateway exposing 90+ models from OpenAI, Anthropic, Google, DeepSeek, Mistral, xAI, Moonshot, Alibaba (Qwen), Cohere, and Perplexity behind a single base URL. Drop-in replacement for any OpenAI SDK with prompt caching, load balancing, fallbacks, reasoning-effort presets, web search/fetch tools, real-time cost analytics, consolidated billing, and no rate limits under 1B tokens/day.

**Base URL:** `https://gateway.glama.ai/v1`

**Human URL:** [https://glama.ai/ai/gateway](https://glama.ai/ai/gateway)

- [Documentation — AI Gateway](https://glama.ai/ai/gateway)
- [Documentation — Models](https://glama.ai/ai/models)

### Glama MCP Gateway
Reverse-proxy MCP gateway fronting hosted, remote, and custom MCP servers under a per-user endpoint of the form `https://glama.ai/endpoints/<connection-profile>/mcp`. Provides full JSON-RPC payload logging, per-tool access control with approval flows, upstream tool-definition rewriting, managed OAuth 2.1 with automatic refresh, audit log export, and session lifecycle tracking.

**Human URL:** [https://glama.ai/mcp/gateway](https://glama.ai/mcp/gateway)

- [Documentation — MCP Gateway](https://glama.ai/mcp/gateway)
- [Documentation — MCP FAQ](https://glama.ai/mcp/faq)

### Glama MCP Server Registry
Comprehensive index of 23,000+ MCP servers, 4,000+ managed connectors, and 169,000+ tools across 86 curated categories. Every server is maintainer-verified, continuously rebuilt from source, and scored for quality and safety. Browser-based testing, one-click install or deploy, and tool-level search.

**Human URL:** [https://glama.ai/mcp/servers](https://glama.ai/mcp/servers)

- [Documentation — MCP Servers](https://glama.ai/mcp/servers)
- [Documentation — MCP Connectors](https://glama.ai/mcp/connectors)
- [Documentation — MCP Tools](https://glama.ai/mcp/tools)
- [Documentation — MCP Clients](https://glama.ai/mcp/clients)
- [Documentation — Registry Methodology](https://glama.ai/mcp/methodology)

### Glama MCP Hosting
One-click managed hosting for any MCP server. Submit a GitHub repository, Glama indexes every tool, schema, and annotation, then deploys onto Glama's managed infrastructure with SSE security, persistent storage, automatic rebuilds, and per-tool access controls. Free for open-source servers.

**Human URL:** [https://glama.ai/mcp/hosting](https://glama.ai/mcp/hosting)

- [Documentation — MCP Hosting](https://glama.ai/mcp/hosting)
- [Blog — One-Click Deployment for Any MCP Server](https://glama.ai/blog/2025-09-10-glama-mcp-server-hosting)
- [Blog — MCP Hosting with Persistent Storage](https://glama.ai/blog/2025-12-06-mcp-hosting-with-persistent-storage)

### Glama MCP Inspector
Browser-based MCP debugger that spins up an ephemeral sandbox from a server URL. Exercise tools with structured inputs, view raw JSON-RPC, complete OAuth flows, test prompts and resources, and share debug sessions via a URL.

**Human URL:** [https://glama.ai/mcp/inspector](https://glama.ai/mcp/inspector)

- [Documentation — MCP Inspector](https://glama.ai/mcp/inspector)
- [Blog — Using MCP Inspector](https://glama.ai/blog/2025-07-24-using-mcp-inspector-to-test-tools-prompts-and-resources)
- [Blog — Inspector with Remote MCP Servers](https://glama.ai/blog/2025-07-27-how-to-use-mcp-inspector-with-remote-or-cloud-hosted-mcp-servers)

### Glama Chat and Playground
All-in-one AI workspace chatting with any MCP server the user owns, routed through the Glama Gateway with every tool call visible and controllable. Supports file uploads (PDFs), projects, memory, web fetch and web search tools, persistent storage, and routing across 90+ models.

**Human URL:** [https://glama.ai](https://glama.ai)

### Glama Automations
Workflow automation primitive composing MCP servers, the AI gateway, and Glama Chat into scheduled or event-triggered jobs (e.g., GitHub pull-request security checks).

**Human URL:** [https://glama.ai/blog/2025-10-22-what-are-automations](https://glama.ai/blog/2025-10-22-what-are-automations)

- [Blog — What are Automations?](https://glama.ai/blog/2025-10-22-what-are-automations)
- [Blog — Automating GitHub PR Security Checks](https://glama.ai/blog/2025-09-15-automating-git-hub-pull-request-security-checks-with-glama-ai-automation-feature)

## Common Properties

- [Portal — glama.ai](https://glama.ai)
- [Pricing](https://glama.ai/pricing)
- [Blog](https://glama.ai/blog)
- [ChangeLog — Release Notes](https://glama.ai/release-notes)
- [StatusPage](https://glama.ai/status)
- [Support](https://glama.ai/support)
- [Newsletter](https://glama.ai/newsletter)
- [Careers](https://glama.ai/careers)
- [TermsOfService](https://glama.ai/policies/terms-of-service)
- [PrivacyPolicy](https://glama.ai/policies/privacy-policy)
- [SecurityPolicy — Vulnerability Disclosure](https://glama.ai/policies/vulnerability-disclosure)
- [Forum — Discord](https://discord.gg/glama)
- [Forum — Reddit /r/glama](https://www.reddit.com/r/glama)
- [GitHubOrganization](https://github.com/glama-ai)
- [SDK — Lightport (open-source AI gateway)](https://github.com/glama-ai/lightport)
- [Tool — rjsf-validator-cfworker](https://github.com/glama-ai/rjsf-validator-cfworker)
- [Documentation — MCP FAQ](https://glama.ai/mcp/faq)
- [Documentation — Models](https://glama.ai/ai/models)
- [Documentation — Model Context Protocol](https://modelcontextprotocol.io)

## Plans

| Plan | Price | AI Credits | Fast Hosted MCP Servers | Logs / Month | Log Retention |
|---|---|---|---|---|---|
| Starter | $9 / user / month | $9 | 3 ($4 per additional) | 100k ($9 per add'l 100k) | 30 days |
| Pro | $26 / user / month | $26 | 10 ($3 per additional) | 100k ($6 per add'l 100k) | 90 days |
| Business | $80 / user / month | $80 | 30 ($2 per additional) | 100k ($3 per add'l 100k) | 180 days |
| Open-Source Hosting | Free | — | Unlimited (for OSS MCP servers) | — | — |

## Models (Selected, via AI Gateway)

Glama's gateway routes 90+ models across OpenAI, Anthropic, Google, DeepSeek, Mistral, xAI, Moonshot (Kimi), Alibaba (Qwen), Cohere, and Perplexity. Glama applies no markup — listed prices match upstream provider prices. Sample entries:

| Provider | Model | Input $/MTok | Output $/MTok |
|---|---|---|---|
| Anthropic | `claude-opus-4-6` | 5.00 | 25.00 |
| Anthropic | `claude-sonnet-4-5` | 3.00 | 15.00 |
| Anthropic | `claude-haiku-4-5` | 1.00 | 5.00 |
| OpenAI | `gpt-5-2025-08-07` | 1.30 | 10.00 |
| OpenAI | `gpt-4o-2024-11-20` | 2.50 | 10.00 |
| Google | `gemini-2.5-pro` | 1.30 | 10.00 |
| Google | `gemini-2.0-flash-001` | 0.15 | 0.60 |
| DeepSeek | `deepseek-r1` | 0.55 | 2.20 |
| Mistral | `mistral-large-2411` | 2.00 | 6.00 |

Full list: [https://glama.ai/ai/models](https://glama.ai/ai/models).

## Features

- MCP server registry indexing 23,000+ servers, 4,000+ connectors, and 169,000+ tools across 86 categories
- Maintainer-verified and continuously rebuilt MCP servers with quality and safety scoring
- Browser-based MCP Inspector with ephemeral sandbox, JSON-RPC trace, OAuth flow handling, and shareable sessions
- One-click MCP server hosting from any GitHub repository, with persistent storage and SSE security
- Free open-source MCP server hosting
- MCP Gateway with per-user endpoint, full JSON-RPC payload logging, per-tool access control, OAuth 2.1 credential management, audit log export, and session lifecycle tracking
- Upstream tool-definition rewriting at the gateway layer
- OpenAI-compatible AI gateway at `https://gateway.glama.ai/v1`
- 90+ models across OpenAI, Anthropic, Google, DeepSeek, Mistral, xAI, Moonshot, Alibaba (Qwen), Cohere, and Perplexity
- Drop-in SDK compatibility with OpenAI SDKs and LangChain
- Prompt caching, load balancing, automatic fallbacks, and reasoning-effort presets (low / medium / high)
- Web search and web fetch tools across the gateway
- Real-time cost analytics and consolidated billing with no markup on listed provider prices
- ~40ms median gateway latency and stated 99% uptime
- No rate limits under 1B tokens/day; higher quotas negotiable within 48 hours
- Glama Chat playground with file uploads (PDFs), projects, memory, persistent storage, custom exports, and any MCP server the user owns
- Automations primitive composing MCP servers, the AI gateway, and Chat into scheduled or triggered workflows
- MCP Sampling support, progress notifications, audio/image responses, and elicitations
- Lightport, an open-source lightweight gateway that makes LLM providers OpenAI-compatible
- Three commercial plans (Starter $9, Pro $26, Business $80) bundling AI credits and fast hosted MCP servers

## Maintainers

- **FN:** Kin Lane
- **Email:** info@apievangelist.com
- **X:** apievangelist
- **URL:** [https://apievangelist.com](https://apievangelist.com)

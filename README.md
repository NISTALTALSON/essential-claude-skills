<div align="center">

# AI Engineering Skills

**A curated collection of battle-tested skills for AI-powered coding, agent engineering, cybersecurity, and modern software development.**

[![Skills](https://img.shields.io/badge/skills-127-4f46e5?style=flat-square)](./skills)
[![License](https://img.shields.io/badge/license-MIT-22c55e?style=flat-square)](./LICENSE)
[![Categories](https://img.shields.io/badge/categories-8-0ea5e9?style=flat-square)](#-skill-categories)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-f59e0b?style=flat-square)](./CONTRIBUTING.md)

*Built for developers who use AI agents as daily coding companions.*

</div>

---

## Why This Exists

AI coding agents are only as good as the instructions you give them. Skills are reusable, structured instructions that tell an agent *exactly* how to approach a task — whether that is designing a PostgreSQL schema, auditing an LLM application for security issues, or building a multi-agent orchestration pipeline.

This repository collects the most practical skills across the full stack of modern development: vibe coding, software engineering, AI/ML engineering, agentic systems, cybersecurity, and developer productivity. Every skill here was reviewed, selected, and organized by hand. Nothing was included just to inflate the count.

**Compatible with:** Claude Code · Antigravity IDE · Cursor · Windsurf · any agent that loads skill files from a `.agents/skills/` directory.

---

## Table of Contents

- [Skill Categories](#-skill-categories)
- [Highlighted Skills](#-highlighted-skills)
- [Using Skills with AI Agents](#-using-skills-with-ai-agents)
- [Installation and Setup](#-installation-and-setup)
- [Adding New Skills](#-adding-new-skills)
- [Security and Attribution](#-security-and-attribution)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)

---

## Skill Categories

### Vibe Coding `skills/vibe-coding/` — 16 skills

Frontend development, UI/UX, design systems, and modern web interfaces.

| Skill | Description |
|-------|-------------|
| `react-patterns` | React component architecture, hooks, performance, and testing patterns |
| `nextjs-turbopack` | Next.js App Router, server components, Turbopack, and deployment |
| `vite-patterns` | Vite build tool configuration, plugins, HMR, and optimization |
| `vue-patterns` | Vue 3 Composition API, Pinia, Vue Router, and Nuxt SSR |
| `frontend-design` | Practical UI design decisions for developer-built interfaces |
| `frontend-patterns` | Component architecture, state, and layout patterns |
| `frontend-a11y` | Accessibility patterns for WCAG compliance |
| `make-interfaces-feel-better` | Micro-polish details that elevate UI quality |
| `design-system` | Design token systems, component libraries, and theming |
| `frontend-slides` | Browser-native HTML presentations with animation |
| `liquid-glass-design` | Glassmorphism and translucent UI aesthetic patterns |
| `design-an-interface` | Generate multiple radically different API/interface designs in parallel |
| `web-performance-optimization` | Core Web Vitals, bundle analysis, and runtime performance |
| `react-testing` | React Testing Library, mocking, and integration test patterns |
| `react-performance` | Profiling, memoization, and rendering optimization |
| `react-native-patterns` | Expo Router, NativeWind, TanStack Query, and native APIs |

---

### Software Engineering `skills/software-engineering/` — 33 skills

Backends, databases, testing, DevOps, Git, and production-readiness patterns.

| Skill | Description |
|-------|-------------|
| `python-patterns` | Idiomatic Python patterns, typing, async, and project structure |
| `python-testing` | pytest, fixtures, mocking, and coverage strategies |
| `rust-patterns` | Ownership, error handling, traits, and concurrency in Rust |
| `rust-testing` | Rust unit, integration, and property-based testing |
| `golang-patterns` | Idiomatic Go — packages, interfaces, concurrency, and error handling |
| `golang-testing` | Go testing, table-driven tests, benchmarks, and fuzz testing |
| `backend-patterns` | Service layer design, middleware, queues, and resilience patterns |
| `fastapi-patterns` | FastAPI routing, dependency injection, auth, and async patterns |
| `django-patterns` | Django project structure, ORM, views, and forms best practices |
| `django-tdd` | Test-driven Django with pytest-django and factory_boy |
| `api-design` | REST API conventions, versioning, pagination, and error contracts |
| `database-migrations` | Safe schema migrations — zero-downtime, rollbacks, and production safety |
| `postgres-patterns` | Query optimization, indexing, RLS, and schema design |
| `redis-patterns` | Caching, distributed locks, rate limiting, and pub/sub |
| `docker-patterns` | Dockerfiles, Compose, multi-stage builds, and container security |
| `kubernetes-patterns` | Deployments, RBAC, probes, autoscaling, and kubectl debugging |
| `tdd` | Red-green-refactor philosophy, vertical slices, and behavior-first testing |
| `tdd-workflow` | Full TDD workflow from plan to 80%+ coverage |
| `e2e-testing` | Playwright E2E patterns, Page Object Model, and CI integration |
| `error-handling` | Typed errors, retries, circuit breakers in TypeScript, Python, Go |
| `deployment-patterns` | CI/CD pipelines, health checks, rollback, and production readiness |
| `git-workflow` | Branching, commit conventions, PR review, and merge strategies |
| `git-guardrails-claude-code` | Claude Code hooks to block destructive git operations |
| `github-ops` | GitHub Actions, issue triage, release automation, and project management |
| `hexagonal-architecture` | Ports and adapters — decoupling business logic from infrastructure |
| `improve-codebase-architecture` | Find architectural friction and propose deep-module refactors |
| `codebase-onboarding` | Generate structured onboarding guides for unfamiliar codebases |
| `code-tour` | Create CodeTour `.tour` files for codebase walkthroughs |
| `coding-standards` | Language-agnostic coding standards and review checklists |
| `architecture-decision-records` | Write ADRs that are actually read and maintained |
| `setup-pre-commit` | Configure pre-commit hooks for code quality automation |
| `web-artifacts-builder` | Build complete web artifacts from scratch |
| `webapp-testing` | Full-stack web application testing strategies |

---

### AI Engineering `skills/ai-engineering/` — 20 skills

LLM integration, ML pipelines, evaluation, RAG, and production AI architecture.

| Skill | Description |
|-------|-------------|
| `ai-first-engineering` | Engineering principles for AI-native applications |
| `prompt-optimizer` | Analyze and rewrite prompts for accuracy and token efficiency |
| `context-budget` | Audit context window consumption and recover headroom |
| `token-budget-advisor` | Real-time token budget guidance during agent runs |
| `mle-workflow` | Production ML engineering: data contracts, training, deployment, monitoring |
| `benchmark` | Performance baseline measurement and regression detection |
| `recsys-pipeline-architect` | Design recommendation and ranking pipelines using the 6-stage pattern |
| `iterative-retrieval` | Multi-hop retrieval strategies for complex RAG queries |
| `exa-search` | Neural web search via Exa MCP for research and code discovery |
| `deep-research` | Systematic multi-source research with evidence synthesis |
| `agent-eval` | Benchmark coding agents head-to-head on reproducible tasks |
| `agent-architecture-audit` | Full-stack diagnostic for agent and LLM application stacks |
| `agent-self-evaluation` | Agents that evaluate their own outputs against defined criteria |
| `eval-harness` | Build evaluation harnesses for LLM applications |
| `cost-aware-llm-pipeline` | Design LLM pipelines with token cost tracking and optimization |
| `regex-vs-llm-structured-text` | Choose between regex and LLM for structured text extraction tasks |
| `pytorch-patterns` | PyTorch training loops, data pipelines, and model deployment |
| `safety-guard` | Safety guardrails and content policy enforcement for LLM apps |
| `gateguard` | Gate-based approval workflows for sensitive agent actions |
| `unified-memory` | Cross-session memory architectures for persistent agent contexts |

---

### AI Agents `skills/ai-agents/` — 17 skills

Agentic workflows, orchestration, multi-agent systems, and autonomous loops.

| Skill | Description |
|-------|-------------|
| `agentic-engineering` | Core patterns for building production-grade agentic systems |
| `agentic-os` | Build persistent multi-agent OS on Claude Code with memory and scheduling |
| `continuous-agent-loop` | Patterns for autonomous, long-running agent pipelines |
| `autonomous-agent-harness` | Test harness for evaluating autonomous agent behavior |
| `team-agent-orchestration` | Multi-agent team coordination with specialist roles |
| `parallel-execution-optimizer` | Run independent tasks concurrently across agent worktrees |
| `blueprint` | Turn a one-line objective into a multi-session construction plan |
| `plan-orchestrate` | Bridge plan documents to orchestration agent chains |
| `dynamic-workflow-mode` | Adaptive workflow selection based on task complexity |
| `operator-approval-loop` | Human-in-the-loop approval gates for agent actions |
| `verification-loop` | Self-verification loops for agent output quality assurance |
| `council` | Multi-perspective review using a council of specialized agents |
| `council-multi-model` | Cross-model council for adversarial review and consensus |
| `agent-harness-construction` | Build evaluation harnesses for agent tasks |
| `agent-introspection-debugging` | Debug agent reasoning and tool call failures |
| `write-a-skill` | Create new agent skills with correct structure and documentation |
| `skill-creator` | Iteratively build, test, and optimize skills with eval support |

---

### MCP `skills/mcp/` — 2 skills

Model Context Protocol server development and integration patterns.

| Skill | Description |
|-------|-------------|
| `mcp-builder` | Build MCP servers in Python (FastMCP) or TypeScript (MCP SDK) |
| `mcp-server-patterns` | MCP tools, resources, prompts, Zod validation, and transport selection |

---

### Cybersecurity `skills/cybersecurity/` — 10 skills

Security review, vulnerability assessment, compliance, and application hardening. All skills are scoped to authorized testing, education, and defense.

| Skill | Description |
|-------|-------------|
| `security-review` | Security checklist for auth, input handling, secrets, APIs, and payments |
| `security-scan` | Scan Claude Code configuration for misconfigurations and injection risks |
| `security-bounty-hunter` | Hunt for remotely reachable vulnerabilities suitable for responsible disclosure |
| `django-security` | Django authentication, CSRF, SQL injection, and XSS prevention |
| `laravel-security` | Laravel auth, Eloquent safety, CSRF, XSS, and API hardening |
| `hipaa-compliance` | HIPAA entrypoint for PHI handling, BAAs, and US healthcare compliance |
| `healthcare-phi-compliance` | PHI/PII classification, audit logging, encryption, and leak prevention |
| `defi-amm-security` | Solidity AMM security: reentrancy, oracle manipulation, and slippage |
| `llm-trading-agent-security` | Security for autonomous agents with wallet and transaction authority |
| `gateguard` | Approval gates and policy enforcement for sensitive agent actions |

---

### Research and Automation `skills/research-and-automation/` — 8 skills

Web research, scraping, data collection, and automated discovery workflows.

| Skill | Description |
|-------|-------------|
| `deep-research` | Multi-source research with structured evidence synthesis |
| `research-ops` | Evidence-first research workflow combining Exa and local context |
| `exa-search` | Neural web and code search via Exa MCP |
| `scrape` | Web scraping via Bright Data Web Unlocker — bypasses bot detection |
| `documentation-lookup` | Fetch live docs via Context7 MCP instead of stale training data |
| `github-triage` | GitHub issue and PR triage automation |
| `data-scraper-agent` | Agent-driven data scraping and extraction workflows |
| `iterative-retrieval` | Multi-hop retrieval for complex information needs |

---

### Productivity `skills/productivity/` — 21 skills

Developer tooling, documentation, planning, and content creation.

| Skill | Description |
|-------|-------------|
| `write-a-skill` | Create new skills with correct structure and progressive disclosure |
| `skill-creator` | Build, test, and iteratively optimize skills with eval benchmarks |
| `context-budget` | Audit and recover context window headroom |
| `blueprint` | Multi-session project planning with dependency graphs |
| `repo-scan` | Cross-stack source code asset audit and dead code discovery |
| `code-tour` | Create CodeTour walkthroughs for onboarding and architecture reviews |
| `codebase-onboarding` | Generate structured guides for unfamiliar codebases |
| `documentation-lookup` | Live documentation lookup via Context7 MCP |
| `improve-codebase-architecture` | Find architectural friction and propose refactors |
| `make-interfaces-feel-better` | Micro-polish details for more professional UIs |
| `frontend-slides` | Zero-dependency HTML presentations with animations |
| `pdf` | PDF generation, manipulation, and content extraction |
| `xlsx` | Excel/XLSX file processing and generation |
| `pptx` | PowerPoint generation and manipulation |
| `docx` | Word document processing and generation |
| `triage-issue` | Structured issue triage and prioritization |
| `prd-to-issues` | Convert PRDs to structured GitHub issues |
| `prd-to-plan` | Convert PRDs to step-by-step implementation plans |
| `write-a-prd` | Write clear product requirements documents |
| `article-writing` | Structured technical article and blog post creation |
| `seo` | SEO analysis, optimization, and content recommendations |

---

## Highlighted Skills

These are the strongest entries in the collection — the ones worth loading first.

| Skill | Why It Stands Out |
|-------|-------------------|
| `agentic-engineering` | Comprehensive, production-tested patterns for building AI agent systems |
| `agent-architecture-audit` | Uniquely valuable — diagnoses the full 12-layer agent stack systematically |
| `mcp-builder` | Clear, opinionated guide for building real MCP servers quickly |
| `tdd-workflow` | One of the most thorough TDD skill implementations available |
| `security-bounty-hunter` | Practical vulnerability discovery focused on real exploitability |
| `postgres-patterns` | Supabase-informed, production-grade PostgreSQL best practices |
| `blueprint` | Turns vague goals into concrete, multi-session engineering plans |
| `context-budget` | Solves a real pain point — context bloat in large agent setups |
| `parallel-execution-optimizer` | Non-obvious but high-leverage: run independent tasks concurrently |
| `deep-research` | Systematic research with evidence synthesis, not just search |
| `council-multi-model` | Cross-model adversarial review — genuinely useful for critical decisions |
| `e2e-testing` | Best-practice Playwright patterns that work in CI from day one |

---

## Using Skills with AI Agents

### Claude Code

Place skills in your repository under `.agents/skills/` or reference them from your global skills directory. Claude Code picks them up automatically.

```bash
# Use a skill in a conversation
@skill:agentic-engineering Build me a multi-step research pipeline

# Or via slash command
/skill security-review
```

### Antigravity IDE

Copy or symlink skills into `~/.gemini/config/skills/`. The IDE discovers them at startup.

### Cursor / Windsurf / Other Agents

Copy the `SKILL.md` contents into your system prompt, rules file, or `.cursorrules` as needed. The structured format works well as a system-prompt block.

### Manual Use

Open any `SKILL.md` and paste its contents into a conversation with your AI assistant of choice.

---

## Installation and Setup

### Option A — Full Clone

```bash
git clone https://github.com/NISTALTALSON/AI-Engineering-Skills.git
cd AI-Engineering-Skills
```

### Option B — Selective Skill Copy

```bash
# Copy only the skills you want
cp -r skills/ai-agents/agentic-engineering ~/.agents/skills/
cp -r skills/software-engineering/tdd-workflow ~/.agents/skills/
```

### Option C — Symlink for Claude Code (macOS/Linux)

```bash
ln -s /path/to/AI-Engineering-Skills/skills ~/.agents/skills
```

No package installation is required. Skills are plain Markdown files.

---

## Adding New Skills

See [CONTRIBUTING.md](./CONTRIBUTING.md) for the full guide. The short version:

1. Create `skills/<category>/<skill-name>/SKILL.md`
2. Add YAML frontmatter with `name`, `description`, and `metadata.origin`
3. Update `docs/SKILL-CATALOG.md`
4. Open a pull request

---

## Security and Attribution

**No secrets.** This repository was scanned before publishing. No API keys, tokens, passwords, or personal configuration files are included. If you discover an accidental exposure, please open a private security report rather than a public issue.

**Attribution.** Many skills originate from or are derived from the Empowered Coding Collective (ECC) open-source project and community contributors. Individual skill directories carry their own license notices where present. See [docs/SOURCES.md](./docs/SOURCES.md) for per-skill attribution.

**Cybersecurity scope.** Security skills in this collection are scoped to authorized penetration testing, security education, defensive development, and responsible disclosure. They are not tools for unauthorized access or harm.

---

## Roadmap

**Near term**
- [ ] Add Langchain / LangGraph integration skill
- [ ] Add OpenAI Agents SDK patterns
- [ ] Add OWASP Top 10 comprehensive skill
- [ ] Add Burp Suite workflow skill for web app pen testing
- [ ] Add CTF toolkit skill for learning environments

**Medium term**
- [ ] Add skills index search (fuzzy search over skill names and descriptions)
- [ ] Structured YAML skill registry for programmatic discovery
- [ ] Skill versioning and changelog tracking
- [ ] CI workflow to validate SKILL.md frontmatter format

**Stretch goals**
- [ ] Automated compatibility checks against multiple agent runtimes
- [ ] Community voting on skill quality
- [ ] Integration with Model Context Protocol skill server

---

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](./CONTRIBUTING.md) before submitting a pull request. The bar is quality, not quantity.

---

<div align="center">

**Built by developers, for developers.**

If a skill here saves you time or teaches you something useful, consider contributing one back.

[Browse Skills](./skills) · [Skill Catalog](./docs/SKILL-CATALOG.md) · [Sources](./docs/SOURCES.md) · [Contribute](./CONTRIBUTING.md)

</div>

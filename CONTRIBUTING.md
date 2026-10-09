# Contributing to Essential Claude Skills

Thank you for your interest in improving this collection. The goal is a curated, high-quality set of skills that genuinely help developers ship better software and AI systems.

## Before You Contribute

1. **Search first.** Check whether an equivalent skill already exists before adding a new one.
2. **Quality over quantity.** One well-documented skill is worth more than five half-finished ones.
3. **Read existing skills.** Understand the structure and tone before adding your own.

## Adding a New Skill

### Directory Structure

```
skills/<category>/<skill-name>/
├── SKILL.md          ← Required. The skill instructions.
└── ...               ← Optional: scripts/, examples/, references/
```

### SKILL.md Frontmatter

Every SKILL.md must begin with YAML frontmatter:

```yaml
---
name: your-skill-name
description: >-
  One or two sentences. What does this skill do?
  When should an AI agent activate it?
license: MIT
metadata:
  origin: your-name-or-source
  version: "1.0.0"
---
```

### Writing Good Skill Instructions

- Be specific about when to activate. Vague triggers lead to over-triggering.
- Use code examples. Concrete examples are more useful than abstract descriptions.
- Separate concerns. If a skill exceeds 300 lines, split reference material into references/ or examples/ directories.
- State prerequisites clearly. If a skill needs an MCP server or external tool, say so upfront.

### Categories

| Directory | Contents |
|-----------|----------|
| vibe-coding/ | Frontend, UI/UX, React/Next.js, design systems |
| software-engineering/ | Backend, databases, testing, DevOps, Git |
| ai-engineering/ | LLMs, ML pipelines, evaluation, RAG |
| ai-agents/ | Agentic workflows, orchestration, autonomous loops |
| mcp/ | Model Context Protocol servers and integrations |
| cybersecurity/ | Security review, pen testing, compliance, hardening |
| research-and-automation/ | Web research, scraping, data pipelines |
| productivity/ | Developer tooling, documentation, planning |

## Security Guidelines

Never include in a skill:
- Real API keys, tokens, passwords, or secrets
- Personal information (names, emails, IP addresses)
- Credentials embedded as "examples"
- Instructions that bypass security boundaries

## Pull Request Process

1. Fork the repository and create a feature branch: feat/skill-name or fix/skill-name.
2. Follow the skill structure above.
3. Update docs/SKILL-CATALOG.md with your new entry.
4. Open a pull request with a clear title and description.

## Code of Conduct

This project follows the Contributor Covenant v2.1. Be respectful, constructive, and inclusive.


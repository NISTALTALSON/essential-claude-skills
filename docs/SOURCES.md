# Sources and Attribution

This document records the origin, license, and attribution for skills in this collection.

## Primary Source: Empowered Coding Collective (ECC)

The majority of skills in this collection originate from or are derived from the **Empowered Coding Collective (ECC)** open-source skills ecosystem.

- **Repository:** The ECC skills are distributed across the community `awesome-claude-skills` ecosystem.
- **License:** Skills marked `metadata.origin: ECC` carry MIT license unless their individual `SKILL.md` or `LICENSE.txt` specifies otherwise.
- **Attribution:** ECC skills are used with attribution per their open-source terms.

## Community Skills

Some skills are contributed by individual community members. These are identified by `metadata.author` or `metadata.origin: community` in their frontmatter.

| Skill | Author / Origin | License | Notes |
|-------|----------------|---------|-------|
| `prompt-optimizer` | YannJY02 (community) | See SKILL.md | Prompt analysis and optimization |
| `blueprint` | community | See SKILL.md | Multi-session planning skill |
| `recsys-pipeline-architect` | mturac (community) | MIT | Pattern inspired by xAI For You algorithm (Apache 2.0); code is independent reimplementation |
| `make-interfaces-feel-better` | linus707 (community) | See SKILL.md | Salvaged from stale community PR #1659 |

## Skills with Explicit License Files

Some skills include a `LICENSE.txt` or `LICENSE.md` in their directory. Those files take precedence over the collection-level MIT license for that specific skill. Always check the skill directory before redistribution.

## ECC-Direct-Port Adaptations

Skills marked `metadata.origin: ECC direct-port adaptation` are implementations ported directly from ECC patterns:

- `defi-amm-security` — v1.0.0
- `llm-trading-agent-security` — v1.0.0
- `hipaa-compliance` — v1.0.0
- `security-bounty-hunter` — v1.0.0

## Curation Notes

**Curator:** Nistal Talson (NISTALTALSON)
**Curation date:** October 2026
**Method:** Manual inspection of 343 skill directories from a personal collection. Skills were selected based on documentation quality, practical value, clarity of purpose, and compatibility with Claude Code / Antigravity IDE.

### Exclusion Criteria

Skills were excluded if they were:
- **Domain-specific business tools** (logistics, carrier management, customs compliance, energy procurement, etc.) with no general developer utility
- **Advertising/marketing tools** (brand discovery, investor outreach, marketing campaigns, competitive analysis)
- **Abandoned or bootstrapper stubs** (skills containing only a pointer to install another tool, with no actual instructions)
- **Duplicates or deprecated aliases** (`autonomous-loops` is superseded by `continuous-agent-loop`; excluded the former)
- **Highly platform-specific without portable value** (Blender motion inspection, Manim video, Slack GIF creator, etc.)
- **Incomplete or empty** — skills where the SKILL.md contained only a stub or placeholder
- **Specialized framework patterns with limited audience** (Kotlin Ktor, Quarkus, CSharp testing, FSharp testing, etc. — useful but niche)

Approximately 216 skills from the original 343 were excluded.

## Third-Party Tool Dependencies

Some skills depend on external services or tools:

| Skill | Dependency | Required? |
|-------|-----------|-----------|
| `exa-search` | Exa MCP server + API key | Yes |
| `scrape` | Bright Data API key + Unlocker zone | Yes |
| `documentation-lookup` | Context7 MCP server | Yes |
| `security-scan` | AgentShield (github.com/affaan-m/agentshield) | For full scan |
| `repo-scan` | External repo-scan tool (pinned commit) | For install step |

## License Summary

| Origin | License | Count (approx.) |
|--------|---------|----------------|
| ECC (explicit MIT) | MIT | ~85 |
| ECC (no explicit license, assumed MIT) | MIT assumed | ~25 |
| Community (explicit) | MIT or as stated | ~10 |
| Other (verified open source) | Various | ~7 |

When in doubt about a specific skill, check the `SKILL.md` frontmatter and any `LICENSE.txt` in the skill directory.

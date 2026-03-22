# context-engineering-skill

> **Also available as part of [claude-code-skills](https://github.com/arturseo-geo/claude-code-skills)** — a collection of 12 production-tested skills for Claude Code.

> Built by **[Artur Ferreira](https://github.com/arturseo-geo)** @ **[The GEO Lab](https://thegeolab.net)**
> [X @TheGEO_Lab](https://x.com/TheGEO_Lab) · [LinkedIn](https://linkedin.com/in/arturgeo) · [Reddit](https://www.reddit.com/user/Alternative_Teach_74/)

![Licence](https://img.shields.io/badge/licence-MIT-green)
![Claude Code](https://img.shields.io/badge/Claude_Code-skill-blueviolet)

Manage, optimize, and debug Claude Code context windows. Covers autocompaction, context rot, token budgets, CLAUDE.md optimization, progressive disclosure, caching strategies, and extending session longevity.

## Install

```bash
git clone https://github.com/arturseo-geo/context-engineering-skill.git ~/.claude/skills/context-engineering
```

## File Structure

```
SKILL.md                                — Core skill: context window management, compaction, budgets, session optimization
references/
  autocompaction.md                     — Deep dive into compaction mechanics, triggers, and configuration
  optimization-patterns.md              — 8 proven patterns for extending session life
  debugging.md                          — Symptom-based diagnosis and recovery workflows
  budgets.md                            — Token budget allocation strategies
.github/
  ISSUE_TEMPLATE/
    bug-report.md                       — Bug report template
    platform-update.md                  — Claude Code update template
  pull_request_template.md              — PR template
CONTRIBUTING.md                         — Contribution guidelines
SECURITY.md                             — Security policy
```

## Related Repos

- [claude-code-skills](https://github.com/arturseo-geo/claude-code-skills) — Full collection of 12 skills
- [mcp-wordpress-setup](https://github.com/arturseo-geo/mcp-wordpress-setup) — WordPress MCP server setup

## Acknowledgments

Built following the open-source best practice approach — reading community work for inspiration, writing original content, and crediting every source.

**Based on:**
- [Agent Skills specification](https://github.com/anthropics/skills) by Anthropic (Apache 2.0)

All skill content is original writing. No files were copied or adapted from any source.

## Author

Built and maintained by **[Artur Ferreira](https://github.com/arturseo-geo)** @ **[The GEO Lab](https://thegeolab.net)**

## License

[MIT](LICENSE)

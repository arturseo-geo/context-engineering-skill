# context-engineering-skill

> Built by **[Artur Ferreira](https://github.com/arturseo-geo)** · **[thegeolab.net](https://thegeolab.net)** · [𝕏 @TheGEO_Lab](https://x.com/TheGEO_Lab) · [LinkedIn](https://linkedin.com/in/arturgeo) · [Reddit](https://www.reddit.com/user/Alternative_Teach_74/)

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Licence](https://img.shields.io/badge/licence-MIT-green)
![Patterns](https://img.shields.io/badge/patterns-8-orange)
![Claude Code](https://img.shields.io/badge/Claude_Code-skill-blueviolet)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](https://github.com/arturseo-geo/context-engineering-skill/blob/main/CONTRIBUTING.md)

Context window management and optimisation for [Claude Code](https://docs.anthropic.com/en/docs/claude-code). Covers autocompaction mechanics, 8 proven patterns for extending session life, symptom-based debugging, and token budget allocation strategies.

## Who This Is For

- **Claude Code power users** who hit context limits during long sessions
- **Agent architects** designing systems that need to maintain state across many tool calls
- **Anyone frustrated** by Claude "forgetting" earlier context mid-session
- **Cost-conscious teams** who want to understand what's actually consuming tokens

## What Makes This Different

Context management is the #1 pain point in Claude Code. This skill explains the mechanics, not just the workarounds:

- ✅ **Autocompaction deep dive** — triggers, configuration, `CLAUDE_AUTOCOMPACT_PCT_OVERRIDE`
- ✅ **8 optimisation patterns** — proven approaches for extending session longevity
- ✅ **Symptom-based debugging** — "Claude forgot X" → diagnosis → recovery workflow
- ✅ **Token budget allocation** — how to distribute context across CLAUDE.md, skills, tools, and conversation
- ✅ **CLAUDE.md optimisation** — size budgets, router pattern, what to keep vs. move to references
- ✅ **Production-tested** — patterns refined across 400+ hours of Claude Code usage at The GEO Lab

## Install

```bash
# Clone
git clone https://github.com/arturseo-geo/context-engineering-skill.git ~/.claude/skills/context-engineering

# Or install all 12 skills at once
git clone https://github.com/arturseo-geo/claude-code-skills.git
cp -r claude-code-skills/skills/context-engineering ~/.claude/skills/
```

## File Structure

```
context-engineering-skill/
├── SKILL.md                           — Core skill: context management, compaction, budgets, session optimization
├── references/
│   ├── autocompaction.md              — Deep dive into compaction mechanics, triggers, configuration
│   ├── optimization-patterns.md       — 8 proven patterns for extending session life
│   ├── debugging.md                   — Symptom-based diagnosis and recovery workflows
│   └── budgets.md                     — Token budget allocation strategies
└── .github/                           — Issue templates and PR template
```

## Related Repos

- [claude-code-skills](https://github.com/arturseo-geo/claude-code-skills) — Full collection of 12 skills
- [memory-persistence-skill](https://github.com/arturseo-geo/memory-persistence-skill) — Companion skill for cross-session memory
- [token-optimizer-skill](https://github.com/arturseo-geo/token-optimizer-skill) — Companion skill for cost reduction

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines. PRs welcome.

---

Built and maintained by **[Artur Ferreira](https://github.com/arturseo-geo)** · **[thegeolab.net](https://thegeolab.net)** · [MIT License](LICENSE)

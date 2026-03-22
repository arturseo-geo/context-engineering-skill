# Contributing to context-engineering-skill

Thank you for your interest in improving this skill. Context engineering for Claude Code is a fast-moving area — contributions that keep the guidance accurate and practical are valuable.

## What We Accept

- **Accuracy fixes** — Correcting token counts, setting names, or behavior descriptions that are wrong or outdated
- **Platform updates** — Reflecting changes in Claude Code's context handling, compaction, or configuration
- **New patterns** — Proven optimization techniques with clear before/after evidence
- **Better examples** — Clearer, more realistic code snippets and configuration samples
- **Bug reports** — Issues where the skill gives wrong or harmful advice

## What We Don't Accept

- **Speculative techniques** — All patterns must be tested and verified in Claude Code
- **Copied content** — All writing must be original. Credit sources in Acknowledgments if inspired by external work
- **Vendor-specific MCP guidance** — This skill covers general context engineering, not specific MCP server setup
- **Prompt injection techniques** — No content designed to manipulate or bypass Claude's behavior

## How to Contribute

### For Small Fixes

1. Fork the repository
2. Make your changes on a new branch
3. Submit a pull request using the PR template
4. Include verification steps (e.g., `/tokens` output showing corrected numbers)

### For New Content

1. Open an issue first describing what you want to add and why
2. Wait for feedback before writing the full content
3. Follow the existing file structure:
   - General guidance goes in `SKILL.md`
   - Deep dives go in `references/`
   - Keep `SKILL.md` concise — it loads into the context window

### For Platform Updates

1. Use the "Claude Code Platform Update" issue template
2. Include the Claude Code version and a link to the changelog or documentation
3. Describe which files need updating

## Style Guide

- **Be concise** — Every token in SKILL.md costs context space. Write tight.
- **Use tables** for comparisons and quick-reference data
- **Use code blocks** for commands, settings, and file content
- **Prefer concrete examples** over abstract explanations
- **Test everything** — Run commands, verify token counts, confirm settings work

## File Structure

```
SKILL.md                           — Core skill (loaded on trigger)
references/
  autocompaction.md                — Compaction deep dive
  optimization-patterns.md         — Proven patterns
  debugging.md                     — Diagnosis guide
  budgets.md                       — Token budget strategies
```

- `SKILL.md` should stay under 200 lines. If adding content would push it over, put the detail in `references/` and add a one-line pointer in SKILL.md.
- Reference files have no hard limit but should be scannable (use headers, tables, bullet points).

## Testing Your Changes

1. Install the modified skill: `cp -r . ~/.claude/skills/context-engineering/`
2. Start a new Claude Code session
3. Trigger the skill with a relevant question (e.g., "How do I manage my context window?")
4. Verify the guidance is accurate by testing the recommended commands/settings
5. Check token overhead with `/tokens`

## Code of Conduct

Be respectful, constructive, and focused on making the skill better for everyone. This is a technical project — keep discussions on-topic and evidence-based.

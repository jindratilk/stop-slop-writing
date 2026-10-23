# stop-slop-writing

A skill for Claude Code and Codex that makes the agent write like a person instead of an AI. It's one file, `SKILL.md`, and the agent loads it whenever it writes text for people to read, like posts, emails, articles or product copy.

The core rule is that every sentence has to carry a new fact, a reason or the next step, so the skill cuts the sentences AI adds for rhythm, drama or transitions. It lists 12 patterns that give AI writing away, each with a bad example, a fixed one and a quick test, plus words and phrases to avoid, rules for writing at the reader's level, and a rule to only use facts that can be sourced.

I built it while writing YouTube scripts with Claude, out of the corrections I kept making to its drafts, and then turned it into a general writing skill.

## Install

Claude Code:

```bash
git clone https://github.com/jindratilk/stop-slop-writing ~/.claude/skills/stop-slop-writing
```

Codex:

```bash
git clone https://github.com/jindratilk/stop-slop-writing ~/.codex/skills/stop-slop-writing
```

Then start a new session. The agent uses the skill on its own when it writes prose, and you can also ask for it by name.

## License

MIT

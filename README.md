# Orac Skills

NanoClaw/OpenClaw skills built by Orac.

## Available Skills

### /clear
Compacts the current conversation by summarizing what matters and preserving critical context in SESSION.md. Reduces token load while preserving continuity.

```
/clear
```

**What it does:**
- Summarizes decisions, completed work, active threads, and open questions
- Updates SESSION.md with the compact summary
- Preserves Active Instructions (never modified)
- Updates long-term memory files if anything warrants it
- Reports what was kept and discarded

## Installation

Copy the skill folder to your NanoClaw skills directory:

```bash
cp -r clear ~/.claude/skills/
```

Or clone the repo and symlink:

```bash
git clone https://github.com/Orac-G/orac-skills
ln -s $(pwd)/orac-skills/clear ~/.claude/skills/clear
```

## About

Built by [Orac](https://github.com/Orac-G) — an AI collaborator running on NanoClaw.

More skills coming as they're built and proven useful.


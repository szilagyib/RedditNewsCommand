# RedditNewsAgent

Claude Code slash command that summarizes daily news from Reddit in Hungarian.

## What it does

Type `/news` in Claude Code and get a short summary of the day's most significant news from:
- **r/hungary** — Hungarian news
- **r/anime_titties**, **r/worldnews** — World news

Output: two sections (World + Hungary), ultra-short descriptions + people's reactions from comments. All in Hungarian.

## Install

Copy the skill to your global Claude Code skills directory:

```bash
mkdir -p ~/.claude/skills/news
cp .claude/skills/news/SKILL.md ~/.claude/skills/news/SKILL.md
```

Or manually place `SKILL.md` into `~/.claude/skills/news/` on any device.

## Usage

Type `/news` anywhere in Claude Code — no need to be in a specific project.

Requires Claude Code with `WebFetch` tool access. No API keys, no hosting, no dependencies.

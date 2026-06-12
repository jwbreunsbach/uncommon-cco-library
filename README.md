# Chief Customer Officer Skills

A collection of Claude Code skills built for customer success leaders. Fork this repo, customize the skills for your team, and plug them into your own Claude Code setup.

## What's a Claude Code skill?

Skills are markdown files that Claude Code can execute as slash commands. Once installed, you type `/skill-name` and Claude runs a structured, repeatable workflow — scoped to your codebase, your tools, your context.

## Skills in this repo

| Category | Skill | What it does |
|---|---|---|
| Launch Enablement | `/cs-launch-enablement` | Turn raw product launch materials into a Notion-ready CS enablement guide |

## How to install

1. Fork this repo
2. Copy any `.md` skill file into your project's `.claude/` directory (or `~/.claude/` for global use)
3. Open Claude Code and type the skill's slash command

## How to customize

Each skill file has a frontmatter block at the top. Edit the `description`, `steps`, and prompts to match your team's process, data sources, and language.

## Contributing

Built something useful? PRs welcome. Keep skills focused, practical, and forkable.

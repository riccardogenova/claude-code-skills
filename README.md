# Claude Code Skills

A growing collection of custom skills for [Claude Code](https://docs.anthropic.com/en/docs/claude-code) that I use daily while building [NinjaBiz](https://ninjabiz.ai).

> **Work in progress** — I'll be adding new skills as I refine my workflow. Contributions and suggestions are welcome.

## Inspiration

This project is inspired by [Matt Pocock](https://github.com/mattpocock)'s excellent [skills](https://github.com/mattpocock/skills/) collection. If you're looking for a comprehensive set of skills covering TDD, PRD writing, codebase architecture and more, check out his repo.

## Skills

### Planning & Design

| Skill | Description |
|-------|-------------|
| **[challenge-my-plan](./skills/challenge-my-plan/)** | Pressure-test a feature plan before writing any code. Claude acts as a senior staff engineer, questioning your assumptions, uncovering edge cases, and pushing back on vague answers — one question at a time — until a structured PRD emerges. |

## Installation

1. Clone the repo or copy the skill folder into your project:

```
cp -r skills/challenge-my-plan .claude/skills/challenge-my-plan
```

2. Open Claude Code in your project and describe the feature you want to build. Claude will pick up the skill and start challenging your plan.

## How I use it

Before every new feature on NinjaBiz, I run `challenge-my-plan` instead of writing the PRD from scratch. Claude systematically covers edge cases, failure modes, scope boundaries, and technical dependencies — things I'd normally catch only mid-implementation.

The output is a structured PRD outline that becomes the single source of truth for development.

## Coming soon

More skills from my daily workflow — stay tuned.

## License

MIT
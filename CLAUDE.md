# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a documentation-only repository containing a personal management handbook for remote team leadership. It consists of Markdown files covering communication practices, career growth, meetings, processes, product management, reviews, strategy, and team dynamics.

## Development Commands

No build or test commands exist. Quality is enforced through pre-commit hooks that run automatically on commit:

- **Markdown linting** with auto-fix
- **Spellcheck** via codespell
- **Trailing whitespace** and EOF fixes
- **YAML validation**

To run hooks manually before committing:

```bash
pre-commit run --all-files
```

## Content Structure

- `communication/` - Async messaging guidance
- `growth/` - Career development plans, SMART goals
- `meetings/` - One-on-ones, retrospectives
- `process/` - Task sizing
- `product/` - Product management approaches
- `reviews/` - Review conversation frameworks
- `strategy/` - Goals and strategy documentation
- `team/` - Competencies, team sizing, states, offboarding
- `templates/` - Reusable document templates

## Writing Guidelines

- Keep tone friendly, direct, and practical
- Favor examples over theory
- Use PRs/issues for updates and questions

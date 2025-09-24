# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a Remote Manager Playbook - a collection of living documents outlining management philosophy, team practices, and templates for remote engineering teams. It's a pure documentation repository written in Markdown, focused on handbook-first remote management approaches.

## Repository Structure

The playbook is organized into thematic directories:

- `communication/` - Async messaging and communication patterns
- `growth/` - Career development and goal-setting resources
- `meetings/` - Meeting formats and best practices
- `process/` - Development process documentation (sizing, etc.)
- `product/` - Product management approaches
- `reviews/` - Performance review conversations
- `strategy/` - Strategic planning and goal-setting
- `team/` - Team management (competencies, sizing, states, parting ways)
- `templates/` - Reusable document templates for common scenarios

## Development Commands

This is a pure documentation repository with no build process. The only automation is:

### Linting

```bash
# The repository uses GitHub Actions for Markdown linting
# To check locally, you can use markdownlint with the config:
npx markdownlint "**/*.md" --config .markdownlint.json
```

The markdownlint configuration disables line length restrictions (MD013) and allows duplicate headings if not siblings.

## Key Files

- `README.md` - Main entry point explaining the playbook's purpose and the author's management philosophy
- `.markdownlint.json` - Markdown linting rules
- `.github/workflows/markdown.yml` - GitHub Action for automated Markdown linting on push/PR

## Contributing Guidelines

When modifying or adding content:

1. Keep the tone friendly, direct, and practical
2. Favor examples over theory
3. All documents should support remote, distributed, and asynchronous teams
4. Link documents appropriately to maintain the handbook-first approach
5. Remember this is a living document collection meant to be updated as practices evolve

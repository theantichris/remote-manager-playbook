# CLAUDE.md

This file provides guidance for working with this repository.

## Project Overview

This is a public, documentation-only repository containing a personal management playbook for remote team leadership. It includes Markdown guidance on communication, growth, meetings, team practices, strategy, and reusable templates.

## Development Commands

There is no application build or test suite. The repository uses pre-commit hooks for Markdown linting, spelling, whitespace, and YAML validation. The pre-commit configuration also contains Go hooks, but this repository does not have Go source files.

Run the configured checks with:

```bash
pre-commit run --all-files
```

## Content Structure

- `communication/`: Async messaging guidance.
- `growth/`: Career growth and SMART goals.
- `meetings/`: One-on-ones and retrospectives.
- `process/`: Project ownership and task sizing.
- `product/`: Product management approaches.
- `reviews/`: Review conversation frameworks.
- `strategy/`: Goals and strategy documentation.
- `team/`: Competencies, team sizing, states, and offboarding.
- `templates/`: Public, reusable Markdown templates.

## Writing Guidelines

- Write in Christopher's voice: friendly, direct, practical, and candid.
- Prefer clear outcomes, responsibilities, examples, and trade-offs over abstract rules.
- Keep the playbook broadly applicable to remote and distributed teams.
- Treat examples as illustrative, not as actual internal company incidents.
- Don't include private employee, personal, or company information from other sources.
- Add new public documents and templates to the README index.

## Template Management

The public Markdown templates in `templates/` are maintained in this repository. They are not an automatic mirror of a personal notes vault.

Personal note-taking templates may use `clin` and its TOML format. The two formats serve different purposes. When practices overlap, reconcile the underlying guidance deliberately; do not copy private notes or run the obsolete `nb` template synchronization commands.

When changing a shared practice, review the public guidance and any relevant public template together so they do not contradict each other.

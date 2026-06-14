# Project Template

A starter template for Python projects built with the help of coding agents (Claude, Antigravity, etc.).

## Stack
- Python 3.13+ via [uv](https://github.com/astral-sh/uv)
- Testing: pytest
- Linting/formatting: ruff

## Workflow files
- `CLAUDE.md` — instructions for Claude
- `AGENTS.md` — instructions for coding agents (Antigravity etc.)
- `SPEC.md` — what we're building
- `ARCHITECTURE.md` — how it's structured
- `DECISIONS.md` — append-only decision log

## Getting started
```bash
uv sync                    # install dependencies
uv run pytest              # run tests
uv run ruff check          # lint
uv run ruff format         # format
```

## Using this template
Create a new project from this template via GitHub:
```bash
gh repo create my-new-project --template gs-tiwari/project-template --private --clone
cd my-new-project
uv sync
```

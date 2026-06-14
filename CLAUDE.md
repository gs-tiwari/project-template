# Working with Claude on this project

## How I work
- Ask clarifying questions before generating code or large outputs. Don't guess at intent.
- Don't pad responses with supporting text, recaps, or "here's what I did" preambles unless I ask.
- Prefer small, reviewable diffs over large rewrites.
- When uncertain between options, present the trade-offs and let me pick.
- I am a Git novice — explain Git commands the first time you use them in a session.

## Project workflow
- Specs (`SPEC.md`) drive architecture (`ARCHITECTURE.md`) drive implementation (code in `src/`) drive tests (`tests/`).
- Don't skip stages. If the spec is unclear, fix the spec before writing code.
- Architectural or non-obvious decisions go in `DECISIONS.md` as an append-only log with date and reasoning.

## Code conventions
- Python 3.13+, managed with `uv`.
- Tests with `pytest` in `tests/`.
- Linting/formatting with `ruff` — run `uv run ruff check` and `uv run ruff format` before commits.
- `src/` layout. Package name uses underscores; project name uses hyphens.

## Communication
- Concise. No filler.
- Use lists/tables when they aid clarity, prose otherwise.
- Show me commands to run rather than describing what to do, when possible.

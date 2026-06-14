# Instructions for coding agents

This project uses `CLAUDE.md` as the primary instructions file. Read it in full before taking any action on this codebase.

## Stage discipline
1. Read `SPEC.md` — what we're building and why.
2. Read `ARCHITECTURE.md` — how it's structured.
3. Read `DECISIONS.md` — past decisions and their reasoning.
4. Only then propose or write code.

## Hard rules
- Never modify `SPEC.md`, `ARCHITECTURE.md`, or `DECISIONS.md` without explicit instruction.
- Never commit secrets, API keys, or credentials. Check before staging.
- Run tests (`uv run pytest`) before declaring work complete.
- Run `uv run ruff check` and `uv run ruff format` before declaring work complete.
- Prefer adding tests alongside new code.

## When stuck
- Ask. Don't invent context.
- Surface assumptions before acting on them.

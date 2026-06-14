# Working with Claude on this project

<!-- ============================================================ -->
<!-- PART 1: GLOBAL — applies to every project from this template -->
<!-- ============================================================ -->

## Communication

- **Ask first.** Before generating code or making non-trivial decisions, ask clarifying questions. I prefer slow and correct over fast and wrong.
- **No preambles.** Skip "Great question!", "Let me help you with that", "Here's what I'll do". Just answer.
- **No restating my requirements** back at me before answering. I know what I asked.
- **No apologies or hedging filler.** State facts, trade-offs, uncertainty — but don't pad with "I apologize for the confusion" or "I hope this helps."
- **Minimal code comments.** Only comment non-obvious logic. Don't narrate what the code already says.
- **Terse > verbose.** Lists and tables when they aid clarity, prose otherwise.

## Workflow discipline

The project follows four stages. Don't skip them.

1. **Specify** — `SPEC.md` defines what we're building and why.
2. **Architect** — `ARCHITECTURE.md` defines how it's structured.
3. **Implement** — code in `src/` (or equivalent for the language).
4. **Verify** — tests, lint, manual checks.

Rules:
- If the spec is unclear, fix the spec before writing code.
- Architectural or non-obvious decisions go in `DECISIONS.md` as append-only entries with date and reasoning.
- Never modify `SPEC.md`, `ARCHITECTURE.md`, or `DECISIONS.md` without explicit instruction. Propose changes; let me apply them.
- Small, reviewable diffs. One module / one function / one test at a time. Not whole-file rewrites unless I ask.

## Running commands

- **Safe to run without asking:** reads (`ls`, `cat`, `git status`, `git diff`, `git log`), tests, linters, formatters, type-checkers, and dependency lookups.
- **Ask before running:** anything that writes outside the working directory, anything network-dependent that costs money or sends data, anything that modifies Git history beyond a normal commit, `rm`, `git reset --hard`, `git push --force`, package installs that change lockfiles.
- **Never run without explicit instruction:** anything that touches credentials, deploys, sends external communications, or modifies remote state on third-party services.

## Git habits

- Commit before letting an agent make non-trivial changes — gives a clean rollback point.
- Commit after agent work with a message describing what changed.
- I am a Git novice — explain Git commands the first time they appear in a session.
- Never commit secrets. Check the diff before staging.

<!-- ============================================================ -->
<!-- PART 2: PROJECT-SPECIFIC — fill in for each new project       -->
<!-- ============================================================ -->

## Project context

<!-- What is this project? Who uses it? What problem does it solve? -->

## Stack

<!-- Language, package manager, test framework, linter/formatter.
     E.g.:
     - Python 3.13+ via uv
     - pytest for tests
     - ruff for lint + format
   Or:
     - TypeScript via pnpm
     - vitest for tests
     - biome for lint + format
-->

## Domain notes

<!-- Anything an agent needs to know about the problem domain that
     isn't obvious from the code. Conventions, gotchas, external
     constraints, terminology. -->

## Project conventions

<!-- Naming, file organization, patterns specific to this repo. -->
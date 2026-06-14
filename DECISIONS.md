# DECISIONS

> Append-only log of architectural and design decisions.
> Newest at the top. Never edit old entries — supersede them with new ones.

## Template

### YYYY-MM-DD — Title of decision
**Context:** What problem or choice prompted this?
**Options considered:** What were the alternatives?
**Decision:** What did we pick?
**Reasoning:** Why?
**Consequences:** What does this make easier? Harder? What did we trade away?

---

<!-- Example:

### 2026-06-13 — Use uv instead of Poetry for dependency management
**Context:** New project, need to pick a Python dep manager.
**Options considered:** uv, Poetry, plain pip+venv.
**Decision:** uv.
**Reasoning:** Faster, simpler single-tool replacement for pip+venv+pyenv, has become the modern default.
**Consequences:** Easier onboarding, but uv is younger than Poetry — some tooling integrations may lag.

-->

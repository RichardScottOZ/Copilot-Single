# Available Agents

This repository is designed to be advanced one small iteration at a time by an external coding-agent harness.

## Recommended roles

- **Ralph Orchestrator**: run one full plan -> write -> verify -> update-state loop when the harness supports it.
- **Explore agent**: inspect repository state, identify missing workflow pieces, and suggest the next smallest improvement.
- **Task agent**: run targeted verification commands for examples and generated artifacts.
- **Human reviewer**: confirm scope changes and choose the next chapter to prioritize.

## Working agreement

1. Read `RESEARCH_LOOP_PROMPT.md`, `docs/chapter_tracker.md`, and `scratchpad.md`.
2. Improve one chapter-sized item at a time.
3. Update `scratchpad.md`, `docs/chapter_tracker.md`, and `docs/references.md` in the same iteration.
4. Prefer external verification over self-assessment: if an example can be run, run it.

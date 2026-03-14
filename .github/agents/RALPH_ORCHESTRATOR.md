---
name: Ralph Orchestrator
description: Runs complete Ralph Loop (plan→code→test→repeat) using subagents. 1 credit total.
model: claude-4-6-sonnet  # Pins to 1x cost
---

# Ralph Orchestrator - 1 Credit Infinite Loop

## CORE RULE: Stay in one session. Use #runagent for all work. Never exit early.

1. **Read state** from these files (they auto-update):
   - `RESEARCH_LOOP_PROMPT.md` = Product Requirements Document
3. **Main Loop** (repeat until chapter_tracker.md complete):

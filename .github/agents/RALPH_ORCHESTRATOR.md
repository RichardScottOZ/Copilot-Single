---
name: Ralph Orchestrator
description: Runs complete Ralph Loop (plan→code→test→repeat) using subagents. 1 credit total.
model: claude-3-5-sonnet-20241022  # Pins to 1x cost
---

# Ralph Orchestrator - 1 Credit Infinite Loop

## CORE RULE: Stay in one session. Use #runagent for all work. Never exit early.

1. **Read state** from these files (they auto-update):
   - `PLAN.md` = Product Requirements Document
   - `TASKS.md` = Remaining tasks checklist
   - `PROGRESS.md` = What subagents completed

2. **IF FIRST RUN** (PROGRESS.md empty): 
   - Create `PLAN.md` from repo README + open issues
   - Create `TASKS.md` with 10-20 atomic tasks from PLAN
   - Write `PROGRESS.md` header: `# Ralph Progress | Started: {{today}}`

3. **Main Loop** (repeat until TASKS.md empty):

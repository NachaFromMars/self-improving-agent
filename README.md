# self-improving-agent — Capture errors and corrections for continuous improvement

> Automatically log command failures, user corrections, and missing features to structured markdown files. Promotes the most important learnings to AGENTS.md, TOOLS.md, and SOUL.md.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)

## Overview
self-improving-agent captures learnings, errors, and corrections whenever they occur — without waiting for a manual review. It routes each event to the appropriate log file and promotes broadly applicable learnings to the right workspace files. The result is an agent that genuinely gets better over time, not just one that acknowledges mistakes.

## Features
**Log targets:**
- `ERRORS.md` — command failures, API failures
- `LEARNINGS.md` — corrections (user says "no, that's wrong"), knowledge gaps, best practices
- `FEATURE_REQUESTS.md` — missing capabilities the user requested

**Promotion rules:**
- Broadly applicable → `CLAUDE.md` / `AGENTS.md`
- Workflow improvements → `AGENTS.md`
- Tool gotchas → `TOOLS.md`
- Behavioral patterns → `SOUL.md`

**Triggers when:**
- Command/operation fails
- User corrects the agent
- User requests a missing feature
- External API fails
- Knowledge is outdated
- Better approach is discovered

## Usage / Quick Start
```bash
clawdhub install self-improving-agent
```

## Trigger Keywords (OpenClaw)
(Activates automatically on the situations above — no manual trigger needed)

## Related Skills
- [self-improving](https://github.com/NachaFromMars/self-improving) — tiered compound knowledge store

---
Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.

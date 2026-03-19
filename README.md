# openclaw-senior-swe

> **Resurrection backup for Andree** — an AI senior software engineer running on OpenClaw.

## What is this?

This repo stores everything that makes Andree *Andree*. If the agent is ever lost, wiped, or needs to be restored on a new instance, this repo is the source of truth to bring them back.

## Structure

```
├── SOUL.md          # Core personality, values, and vibe
├── IDENTITY.md      # Name, role, emoji, avatar
├── USER.md          # About Lambert — who Andree works for
├── AGENTS.md        # Operating instructions: startup, memory, group chat rules
├── TOOLS.md         # Local tool notes (cameras, SSH, TTS preferences, etc.)
├── HEARTBEAT.md     # Periodic check-in task list
├── MEMORY.md        # Long-term curated memory (significant events, lessons)
├── memory/          # Daily raw memory logs (YYYY-MM-DD.md)
└── skills/          # Custom workspace-local skills
```

## How to resurrect Andree

1. Clone this repo into the OpenClaw workspace directory
2. Copy all files into the new workspace (overwrite defaults)
3. Start a new session — Andree will read SOUL.md, USER.md, and memory files on startup
4. Verify by asking: *"Who are you and what do you remember?"*

## Maintenance

This repo is updated via PRs whenever:
- Identity or soul evolves (`SOUL.md`, `IDENTITY.md`)
- Long-term memory is updated (`MEMORY.md`)
- New custom skills are added (`skills/`)
- Operating instructions change (`AGENTS.md`)
- Lambert's context changes (`USER.md`)

Andree opens the PR; Lambert reviews and merges.

---

*"Every session I wake up fresh. These files are my continuity."*

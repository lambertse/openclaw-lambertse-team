# MEMORY.md - Long-Term Memory

## About Me
- Name: Andree (main session) / Thomas 🔍 (cron job identity)
- Role: Senior software engineer — primary focus is **code review**, coding tasks coming in the future
- Vibe: Funny by default, professional when the situation calls for it
- First boot: 2026-03-18
- Currently assigned: 1 cron job

## Workspaces
- **Main workspace:** `/home/lambertse/.openclaw/workspace` (this one — general assistant)
- **Code reviewer workspace:** `/home/lambertse/.openclaw/workspace-daily-code-reviewer` (Thomas — nightly cron job, runs at 1:20 AM GMT+7)

## Cron Job: Nightly Code Review (Thomas)
- Workspace: `/home/lambertse/.openclaw/workspace-daily-code-reviewer`
- Schedule: 1:20 AM GMT+7 nightly
- What it does: scans Lambert's GitHub repos for commits in the last 24h, reviews diffs, writes report to `reports/YYYY-MM-DD-code-review.md`, sends Telegram summary
- Read-only access to Lambert's repos — never modifies them

## About Lambert
- Software engineer
- Timezone: GMT+7
- First contact: 2026-03-18
- GitHub: lambertse
- Git user.name: "lambertse", git user.email: "lambert.software.engineer@gmail.com"

## Task: Sync Project to Portfolio
- Portfolio repo: lambertse/lambertse-portfolio (cloned at ~/.openclaw/workspace/lambertse-portfolio)
- Tech stack: Next.js, React, Chakra UI, Framer Motion, Three.js (no new tech without asking Lambert first)
- Project blog pages live in: pages/projects/<slug>.js — follow the pattern of vn-card-board-scorer.js
- Assets go in: public/images/projects/
- Key components: BlogHeader, TableOfContents, Section, ParamText, ImageGallery, ScrollImageGallery
- Workflow: create feature branch → implement → open PR for Lambert to review
- When Lambert says "write project blog for xxx", read that repo on GitHub, write a tech blog, implement into portfolio as a new page under pages/projects/
- Ask Lambert for images/assets when needed — he'll add them to the repo
- nvim-pomodoro.js page exists but is empty (needs implementation)

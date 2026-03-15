# DEX Personal Operating System — Setup Plan

## What it is
DEX is an open-source "personal operating system" for Claude Code built by Dave Killeen (CPO at Pendo).
It turns Claude Code + Cursor into a self-compounding AI chief of staff.
No coding required. Built for PMs and non-engineers.

## Key repos
- DEX: https://github.com/davekilleen/Dex
- claude-os (alternative): https://github.com/knnymrls/claude-os
- Pendo blog post (written guide): https://www.pendo.io/pendo-blog/building-a-personal-operating-system-with-claude-code/

## Prerequisites (install first)
1. Cursor — https://cursor.sh (free tier works)
2. Claude Code — already installed ✅ (claude is at /Users/markmerl/.local/bin/claude)
3. Node.js — already installed ✅
4. Granola (optional but great for meeting notes) — https://granola.ai
5. SuperWhisper or WhisperFlow.ai — voice-to-text so you talk instead of type

## Setup Steps (30-45 min)

### Step 1: Clone DEX
```
git clone https://github.com/davekilleen/Dex.git ~/Projects/dex
cd ~/Projects/dex
```

### Step 2: Open in Cursor
Open Cursor → File → Open Folder → ~/Projects/dex

### Step 3: Run setup
In Cursor chat (Claude):
```
/setup
```
It will ask: your name, role (pick Product Manager), company size, goals.
Takes ~5 minutes.

### Step 4: Connect your data (do as many as you can)
- **Calendar** — connects via MCP (Google Calendar or Apple Calendar)
- **Email** — Gmail MCP
- **Meeting notes** — Granola integration (auto-imports 30min after each meeting)
- **GitHub** — for tracking repos/PRs
- **LinkedIn** — via PhantomBuster (optional, for lead tracking)

### Step 5: Customize your CLAUDE.md
Tell Claude:
- Your role: PM at CAIS (alternative investments fintech)
- Your goals: ship great product, build $10k/mo side projects, stay ahead on AI
- Your working style preferences
- Key stakeholders at CAIS
- Current projects and priorities

### Step 6: Run your first daily plan
Each morning in terminal:
```
claude
/daily-plan
```

## Key commands to know
- `/daily-plan` — morning briefing (calendar + priorities + intel)
- `/health-score` — account/project health check
- `/prd [idea]` — generates a PRD from a rough idea
- `/weekly-plan` — sets up your week
- `/dex-improve` — self-improves the system using latest Claude/Anthropic releases
- `/x-ray [command]` — explains how any command works with a diagram

## What to connect for CAIS PM work
- Jira/Linear (ticket MCP) — auto-reads your backlog
- Confluence/Notion (docs MCP) — ingests your PRDs and specs
- Slack (read-only MCP) — listens for signals from stakeholders
- Customer calls (Granola) — meeting notes auto-injected

## The compounding magic
Every time you use it:
- Mistakes get logged → never repeated
- Learnings get captured → inform future decisions
- Meeting notes → appended to project files
- Weekly feedback → feeds career tracker

After 30 days, it knows your work better than any colleague.

## Resources
- YouTube demo (the video Mark watched): https://youtu.be/0v8U-0aSb-g
- Pendo blog post: https://www.pendo.io/pendo-blog/building-a-personal-operating-system-with-claude-code/
- @davekilleen on X for updates

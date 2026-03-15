# PMPilot — AI Operating System for Product Managers

## Status: Concept — Build Queued for Later

---

## The Problem

Product managers at mid-market companies spend ~40% of their time on admin:
- Writing PRDs from scratch
- Summarizing meeting notes into action items
- Drafting stakeholder update emails
- Maintaining status reports across Jira/Notion/Slack
- Preparing for meetings by pulling context from 5 different tools

The DEX personal operating system (built by Dave Killeen, CPO at Pendo) solves this brilliantly — but requires technical setup (terminal, git, Node.js). **No working PM at a real company will set this up themselves.** There is a massive gap between "this is possible with Claude Code" and "this is productized and available to every PM."

PMPilot is "DEX as a Service" — the same pattern, fully hosted, no-code, plug-and-play.

---

## Market Size

### Total Addressable Market
- **Product Management Software market: $5.1B in 2024**, growing to $12.3B by 2033 (10.5% CAGR)
- **~1 million product managers** in the US alone
- Average PM team tool spend: $2,000-$10,000/year per person

**TAM: ~$5-10B** (global PM software market)

### Serviceable Addressable Market
- ~300,000 PMs at Series B+ companies (50-5000 employees) in the US
- These companies pay for tools and have budget authority
- Target price: $49/user/month

**SAM: ~$1.7B** (300k PMs × $49/mo × 12)

### Serviceable Obtainable Market (Year 1-2)
- Target: PMs at fintech/SaaS companies (Mark's direct network)
- Head of Product at 10-20 companies = 50-200 seats
- Goal: 200 individual PMs or 10 teams

**SOM: ~$120K ARR** (200 PMs × $49/mo × 12) → scales with team sales

---

## Competitive Landscape

| Company | What They Do | Gap |
|---------|-------------|-----|
| Jira / Linear | Issue tracking | Not AI-native, not PM-workflow focused |
| Notion | Docs + wikis | General purpose, no AI OS pattern |
| Productboard | Product discovery | Roadmapping only, no daily workflow |
| Aha! | Roadmapping | Strategic planning, not daily execution |
| DEX (open source) | Personal OS for Claude Code | Requires technical setup, not for non-engineers |
| Dovetail | User research | Research only |
| **PMPilot** | Hosted AI OS for PMs | **The gap: zero-setup, plug-and-play DEX for every PM** |

---

## Solution

A fully-hosted, no-code version of the DEX personal OS pattern for product managers:

1. **Daily Plan** — Every morning: AI pulls calendar, priorities, PRDs in flight, stakeholder updates needed → generates your day plan
2. **PRD Generator** — Input a rough idea → get a full structured PRD with vision, goals, user stories, success metrics, non-goals
3. **Meeting Digest** — Paste transcript → get action items, decisions, follow-ups, stakeholder updates
4. **Stakeholder Tracker** — Who owes you what, who you owe, relationship health across your key stakeholders
5. **Project Health** — Kanban view of all active initiatives with AI health scores and next best actions
6. **Career Compass** — Track your wins, feedback, and progress toward your career goals

---

## Target Customer — ICP

**Primary:**
- Senior PM or Lead PM at Series B-D SaaS/fintech company
- 50-500 employees
- Uses Jira + Notion + Slack + Google Calendar
- Spends 2+ hours/day on admin work they hate

**Secondary:**
- Head of Product / VP Product at growing company who wants to roll it out to their team
- PMs at fintech companies (Mark's direct network at CAIS)

---

## Product Vision

*"The AI chief of staff for product teams — built on your tools, learning from your work, getting smarter every day."*

---

## Strategy

**Phase 1 — Core Workflow Tools (Month 1-2)**
PRD generator + meeting digest as standalone tools. Free tier to build audience. No auth/account needed initially.

**Phase 2 — Daily Plan (Month 3-4)**
Connect Google Calendar via OAuth. Generate personalized daily plan. First paid tier: $29/mo solo.

**Phase 3 — Full OS (Month 5-6)**
Jira + Linear integration. Project health dashboard. Stakeholder tracker. $49/mo.

**Phase 4 — Team Tier (Month 7+)**
Team dashboard, shared knowledge base, manager view of team priorities. $49/user/mo.

---

## Roadmap

| Month | Milestone | Revenue |
|-------|-----------|---------|
| 1 | PRD generator + meeting digest live (free) | $0 |
| 2 | 1000 free users, 50 paying | $1.5k/mo |
| 3 | Daily plan live, calendar integration | $5k/mo |
| 4 | 200 paying users | $10k/mo |
| 6 | Full OS + Jira integration | $25k/mo |
| 12 | Team tier, 50 companies | $100k/mo |

---

## Path to $10k/month
**200 PMs × $49/mo = $9,800**
Or: 4 teams of 5 PMs at $49/user = $980/team × 10 teams = $9,800

---

## Distribution Strategy
- Product Hunt launch (PMs are heavy Product Hunt users)
- Lenny's Newsletter / Shreyas Doshi communities
- LinkedIn content from Mark's PM expertise
- CAIS internal — test with Mark's own team first
- Partner with DEX (open source) — offer as the hosted version

---

## Why Mark Is Uniquely Positioned
- IS a product manager — understands the pain intimately
- Works in fintech — knows what fintech PMs specifically need
- Can test it on himself first and use it as a case study
- Direct connection to PM communities through CAIS network

---

## Why Now
- DEX proved the pattern works — now it needs productization
- Claude Code + MCP made the technical foundation possible
- PMs are early adopters of AI tools — high willingness to pay
- No one has launched a proper "hosted personal OS for PMs" yet

---

## Build Notes
- App repo: mjm1327/pm-pilot (created, empty)
- Stack: Next.js + Tailwind + shadcn/ui
- Core features: PRD generator, meeting digest, daily plan, project kanban
- Key differentiator: Zero-setup, connects via OAuth (no terminal needed)
- Build when: After RaiseOS MVP, or in parallel as a personal productivity tool for Mark

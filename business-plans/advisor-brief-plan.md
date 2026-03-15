# AdvisorBrief — AI Morning Intelligence for Financial Advisors

## Status: Concept — Build Queued for Later

---

## The Problem

Financial advisors managing alternative investments receive a firehose of information daily — fund manager PDFs, market updates, client emails, macro news — with no unified intelligence layer. They waste 1-2 hours every morning just gathering context before they can do real work. CAIS and iCapital solved the distribution problem for RIAs (getting access to alts). Nobody has solved the **intelligence problem** — helping advisors understand and act on those investments.

Most advisors are using Bloomberg for equities, scattered PDFs for alts, and their own memory for client context. There is no "morning briefing" product built for the alternatives-focused advisor.

---

## Market Size

### Total Addressable Market
- **15,000+ SEC-registered RIAs** in the US
- RIAs projected to manage **33% of all advisor-managed assets** by 2026
- Combined AUM under RIA management: **$8+ trillion**
- Average RIA spends $15,000-$50,000/year on technology tools

**TAM: ~$1.5B** (15,000 RIAs × $100/mo average)

### Serviceable Addressable Market
- ~5,000 RIAs with meaningful alternatives exposure (20%+ of book in alts)
- These advisors spend MORE on tech and have higher willingness to pay

**SAM: ~$300M** (5,000 RIAs × $50/mo)

### Serviceable Obtainable Market (Year 1-2)
- Target: advisors already using CAIS (Mark's direct network)
- CAIS has ~6,000 advisor relationships
- Goal: 500 paying advisors at $99/mo

**SOM: ~$600K ARR** → scales to $5M+ with product-led growth

---

## Competitive Landscape

| Company | What They Do | Gap |
|---------|-------------|-----|
| Bloomberg Terminal | Institutional market data | $24k/year, equities-focused, no alts narrative |
| Morningstar Advisor | Fund research + portfolio tools | Traditional mutual fund focus, no AI |
| Orion / Riskalyze | Portfolio analytics | No daily intelligence, no alts focus |
| SmartAsset / Broadridge | Advisor marketing | Not intelligence/workflow |
| Nothing | AI morning brief for alts advisors | **The gap** |

---

## Solution

A daily AI-generated briefing delivered to financial advisors every morning:

- **Portfolio snapshot:** What moved in their clients' alts holdings overnight
- **Alts narratives:** Key themes in PE, hedge funds, real estate, credit relevant to their book
- **Market signals:** Macro events that affect their allocations
- **Client talking points:** What to say on calls today about market events
- **Action items:** Which clients need a proactive call based on their holdings

Delivered via: Telegram, email, or web dashboard (advisor's choice).

---

## Target Customer — ICP

**Primary:**
- Independent RIA, $100M–$1B AUM
- 20-50% alternatives exposure
- 1-5 person IR/advisor team
- Currently using CAIS or iCapital for alts access
- Paying $15k-$50k/year on disconnected tools

**Secondary:**
- Wirehouse advisors at Morgan Stanley, Merrill, UBS with alts books
- Family office investment staff

---

## Product Vision

*"The Bloomberg Terminal morning brief, built for the independent alternatives advisor, powered by AI."*

---

## Strategy

**Phase 1 — Newsletter/Telegram (Month 1-2)**
No app. Just a daily AI-generated brief delivered via Telegram/email. Manual + semi-automated. Validate willingness to pay. Start free for 10 beta advisors.

**Phase 2 — Personalization (Month 3-4)**
Connect to advisor's book (via CRM API or manual input). Brief becomes specific to their holdings. Charge $49-99/mo.

**Phase 3 — Dashboard (Month 5-6)**
Web app where advisors manage preferences, see historical briefs, drill into narratives.

**Phase 4 — Platform (Month 7+)**
Deep integrations with CAIS, iCapital, Orion, Redtail CRM. White-label for RIA firms.

---

## Roadmap

| Month | Milestone | Revenue |
|-------|-----------|---------|
| 1 | 10 free beta users, manual briefs | $0 |
| 2 | Automate brief pipeline, first paid users | $1k/mo |
| 3 | Personalization live, 50 paying users | $5k/mo |
| 4 | 101 paying users | $10k/mo |
| 6 | Dashboard + CAIS integration | $25k/mo |
| 12 | 500 users + team tier | $75k/mo |

---

## Path to $10k/month
**101 advisors × $99/mo = $10k**

---

## Why Now
- Alts allocations at RIAs growing 20%+ per year
- AI can now summarize and synthesize across hundreds of data sources in seconds
- The "AI morning brief" pattern is proven (Dave Khaled's DEX, our own morning brief)
- Mark has direct distribution through CAIS advisor network

---

## Build Notes
- App repo: mjm1327/advisor-brief (created, empty)
- Stack: Next.js + Tailwind + shadcn/ui
- Core feature: Daily brief generator + advisor dashboard
- Build when: After RaiseOS MVP is validated

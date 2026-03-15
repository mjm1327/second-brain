# PolicyPilot — AI Insurance Risk Manager for Startups & Scale-ups

## Status: Concept — Build Queued for Later

---

## The Problem

Startups and scale-ups ($1M-$50M revenue) are massively underserved on insurance. Traditional brokers are commission-driven generalists who don't understand tech businesses. Founders buy the wrong coverage, overpay, and only discover the gaps at claims time. As JD Ross (OpenDoor/WithCoverage) noted: "Insurance is where C students make money."

The specific pain:
- Founders don't know what they need (cyber? E&O? D&O? product liability?)
- Brokers don't understand their business model
- Coverage rarely gets updated as the business changes (new product, new headcount, new country)
- Claims are a nightmare — no one helps you through it
- Paying commission to a broker who does nothing after the sale

WithCoverage is solving this for enterprise ($10M+ revenue). **Nobody is solving it well for early/growth stage.**

---

## Market Size

### Total Addressable Market
- **Global insurance brokerage market: $359B in 2026**, growing to $562B by 2031 (9.38% CAGR)
- **US insurance brokerage market: $70B+**
- **US SMB commercial insurance market: ~$110B** (Oliver Wyman)
- Brokers earn 10-15% commission on premiums = $15-20B in broker fees on SMB alone

**TAM: $15-20B** (US SMB commercial insurance broker fees)

### Serviceable Addressable Market
- ~500,000 US startups and scale-ups with $1M-$50M revenue
- Average commercial insurance spend: $15,000-$75,000/year
- Broker fee: ~$2,000-$10,000/year per company

**SAM: ~$2B** (500k companies × $4k average broker fee)

### Serviceable Obtainable Market (Year 1-2)
- Target: Seed to Series B tech startups (fintech, AI, SaaS)
- Entry via YC, Product Hunt, startup communities
- Goal: 100 startup clients at $299/mo

**SOM: ~$360K ARR** → scales with broker license acquisition

---

## Competitive Landscape

| Company | What They Do | Gap |
|---------|-------------|-----|
| Embroker | Digital insurance for startups | Good product but limited AI, coverage-focused not risk advisory |
| Vouch Insurance | Insurance for startups | Specific to VC-backed tech, limited coverage types |
| Newfront | Modern broker | Human-led, not AI-native, mid-market focus |
| WithCoverage | AI broker for enterprise | $10M+ revenue minimum, not for early stage |
| Traditional brokers | Generalist | Expensive, slow, not tech-forward |
| **PolicyPilot** | AI risk co-pilot for startups | **The gap: AI-first, early stage, proactive risk management** |

---

## Solution

An AI-powered insurance co-pilot for startups that:

1. **Risk Audit** — Input your business model → get a prioritized list of coverage gaps and risks
2. **Policy Comparison** — Plain English comparison of policy options across carriers
3. **Proactive Monitoring** — Alerts when your coverage needs updating (hired employee #50? Time to review D&O. Launched in EU? Need GDPR coverage.)
4. **Claims Support** — AI guides you through the claims process step by step
5. **Broker Mode** — Licensed broker earns commission + charges SaaS fee for the platform

---

## Target Customer — ICP

**Primary:**
- Seed to Series B startup
- 10-100 employees
- $1M-$20M revenue
- Fintech, AI, SaaS, marketplace
- Currently using a random broker their lawyer recommended

**Secondary:**
- YC/a16z/Sequoia portfolio companies (warm distribution via investor intros)
- Solo founders / early teams who have never thought about insurance

---

## Product Vision

*"Ramp for insurance risk — the automated CFO for your commercial coverage."*

---

## Strategy

**Phase 1 — Free Risk Audit Tool (Month 1-2)**
No brokerage yet. Free tool: input your business → get a risk report. Lead gen funnel. Builds brand as the expert.

**Phase 2 — Paid Monitoring (Month 3-4)**
$99-299/mo for ongoing risk monitoring + proactive alerts. Partner with an MGA or wholesale broker for carrier access.

**Phase 3 — Full Broker (Month 5-6)**
Get licensed as a surplus lines broker (or acquire a licensed entity). Earn full commission + platform fee.

**Phase 4 — Claims & Renewals (Month 7+)**
AI-guided claims management. Annual renewal automation. Expand to more coverage types.

---

## Roadmap

| Month | Milestone | Revenue |
|-------|-----------|---------|
| 1 | Free risk audit tool live, 100 signups | $0 |
| 2 | Partner broker deal, first paid users | $2k/mo |
| 3 | 30 paying companies at $299/mo | $9k/mo |
| 4 | 34 companies | $10k/mo |
| 6 | Broker license + full commission | $25k/mo |
| 12 | 200 companies + claims product | $75k/mo |

---

## Path to $10k/month
**34 startups × $299/mo = $10k**
Or with broker commission: 20 clients with avg $500/mo commission = $10k

---

## Why Now
- AI can now understand complex policy documents and translate to plain English
- Startups are increasingly digital-first — they expect a modern experience
- WithCoverage proved the model works at enterprise — early stage is wide open
- Insurance complexity is increasing (cyber, AI liability, new regulations)

---

## Build Notes
- App repo: mjm1327/policy-pilot (created, empty)
- Stack: Next.js + Tailwind + shadcn/ui
- Core feature: Risk audit onboarding flow + risk report generator
- Key page: Multi-step onboarding → AI risk report with coverage gap analysis
- Build when: After RaiseOS MVP is validated

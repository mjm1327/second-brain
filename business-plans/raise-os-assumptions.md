# RaiseOS — Product Assumptions to Validate

## How to Use This Doc
Each assumption has a validation method and status. As we talk to customers, update the status:
- 🔴 Unvalidated
- 🟡 Partially validated (some evidence)
- 🟢 Validated (multiple sources confirm)
- ❌ Invalidated (assumption was wrong)

---

## GP (Fund Manager) Assumptions

### Problem Assumptions
| # | Assumption | Validation Method | Status |
|---|-----------|------------------|--------|
| GP-P1 | IR teams spend 40-50% of time on admin tasks (data entry, chasing docs, status tracking) | Interview 10 IR professionals | 🔴 |
| GP-P2 | Average fund raise takes 18+ months and most of that is process friction not relationship building | Industry reports + 5 GP interviews | 🔴 |
| GP-P3 | GPs use 4-6 disconnected tools and hate the fragmentation | Survey 20 emerging managers | 🔴 |
| GP-P4 | DDQ responses are the single most time-consuming manual task | Interview IR teams | 🔴 |
| GP-P5 | Emerging managers ($100M-$500M) are most underserved — too small for Allvue/eFront, too complex for spreadsheets | Competitive analysis + interviews | 🟡 |
| GP-P6 | Current tools (Dynamo, Allvue) are seen as expensive and too complex | Review G2/Capterra reviews | 🟡 |

### Solution Assumptions
| # | Assumption | Validation Method | Status |
|---|-----------|------------------|--------|
| GP-S1 | GPs will pay $1,500-5,000/mo for an all-in-one platform | Willingness-to-pay interviews | 🔴 |
| GP-S2 | AI DDQ auto-responder would save 10+ hours per fund raise | Time study with IR teams | 🔴 |
| GP-S3 | GPs want AI to tell them what to do next (next best action) not just show data | Product concept test | 🔴 |
| GP-S4 | Voice meeting logging would be used daily by IR teams | Prototype test with 5 users | 🔴 |
| GP-S5 | GPs will share their LP data with a third-party platform | Privacy/trust interviews | 🔴 |
| GP-S6 | The "IR skills library" (/meeting-prep, /ddq, /follow-up) would replace current ad-hoc AI usage | Usage observation study | 🔴 |

### Go-to-Market Assumptions
| # | Assumption | Validation Method | Status |
|---|-----------|------------------|--------|
| GP-G1 | Mark's CAIS network provides direct access to 50+ warm GP prospects | Map CAIS relationship database | 🟡 |
| GP-G2 | Placement agents are willing to recommend RaiseOS to their GP clients | Interview 5 placement agents | 🔴 |
| GP-G3 | Industry conferences (iConnections, SALT) are cost-effective acquisition channels | Test with 1 conference | 🔴 |
| GP-G4 | GPs will switch from existing tools if onboarding takes <1 day | Migration time study | 🔴 |
| GP-G5 | A free 90-day trial converts to paid at 40%+ rate | Run pilot program | 🔴 |

---

## LP (Investor) Assumptions

### Problem Assumptions
| # | Assumption | Validation Method | Status |
|---|-----------|------------------|--------|
| LP-P1 | LPs make allocation decisions narrative-first (macro thesis) before selecting managers | Interview 10 family office CIOs | 🔴 |
| LP-P2 | LPs have no single view of their public + private portfolio | Survey 20 LP contacts | 🔴 |
| LP-P3 | LP due diligence process is fragmented across email, Dropbox, and phone calls | Shadow 3 LPs through a DD process | 🔴 |
| LP-P4 | LPs feel overwhelmed by inbound GP pitches and struggle to filter signal from noise | Interview 10 LPs | 🟡 |
| LP-P5 | Family offices ($50M-$500M) are the most underserved LP segment for technology | Market research + interviews | 🔴 |
| LP-P6 | LPs want benchmarking data — "what are peers like me allocating to?" | Survey LPs | 🔴 |

### Solution Assumptions
| # | Assumption | Validation Method | Status |
|---|-----------|------------------|--------|
| LP-S1 | LPs will connect their public brokerage accounts to a private markets platform | Privacy/trust interviews | 🔴 |
| LP-S2 | Narrative-first discovery drives higher-quality fund selection than catalog browsing | A/B test two discovery flows | 🔴 |
| LP-S3 | Reverse bidding (LPs publish mandates, managers bid) is preferred over cold outreach | Concept test with 10 LPs | 🔴 |
| LP-S4 | LPs will complete digital KYC/subscription in <30 minutes if the UX is good | Prototype usability test | 🔴 |
| LP-S5 | LPs will pay $500/mo for premium intelligence + mandate visibility | Willingness-to-pay test | 🔴 |
| LP-S6 | "KYC once, invest anywhere" meaningfully reduces friction vs. current process | Time study + interview | 🔴 |
| LP-S7 | AI portfolio gap analysis generates "aha moments" that drive investment decisions | Prototype demo with 10 LPs | 🔴 |

### Network Effect Assumptions
| # | Assumption | Validation Method | Status |
|---|-----------|------------------|--------|
| NE-1 | GP quality improves LP engagement (more LPs join when more quality GPs are on platform) | Track correlation in pilot | 🔴 |
| NE-2 | LP capital availability attracts more GPs (GPs join when they see active LP mandates) | Track conversion in pilot | 🔴 |
| NE-3 | Anonymized LP benchmarking data becomes more valuable as LP count grows | Model data value at 10/50/100/500 LPs | 🔴 |
| NE-4 | Transaction data (who invested in what, at what terms) creates defensible moat | Competitive analysis | 🟡 |

---

## Business Model Assumptions

| # | Assumption | Validation Method | Status |
|---|-----------|------------------|--------|
| BM-1 | GPs will pay a transaction fee (0.1-0.25%) on capital raised through platform | Interview 10 GPs | 🔴 |
| BM-2 | CAC for GP is <$2,000 via warm intro/conference channel | Track in pilot | 🔴 |
| BM-3 | Average GP LTV is $60,000+ (3yr relationship) | Model with churn assumptions | 🔴 |
| BM-4 | GPs stay on platform after fund close (for LP reporting, next fund raise) | Interview existing tool users on retention | 🔴 |
| BM-5 | Gross margin is 85%+ at scale | Unit economics model | 🟡 |

---

## Highest Priority to Validate First

### Week 1-2 (Do Immediately)
1. **GP-P3** — Do GPs really use 4-6 tools? (easiest to validate, just ask)
2. **GP-P1** — How much time is actually wasted on admin?
3. **LP-P1** — Is allocation really narrative-first?
4. **LP-S1** — Will LPs connect public brokerage? (potential dealbreaker)
5. **GP-S1** — Willingness to pay $1,500-5,000/mo

### How to Validate Quickly
- **5 GP interviews** — Mark has direct access via CAIS. Ask: current tools, time on admin, biggest pain, WTP
- **5 LP interviews** — Same network. Ask: how do you make allocation decisions, do you have a portfolio view, WTP
- **G2/Capterra scrape** — Read 100 reviews of Dynamo/Allvue/Juniper Square for pain points
- **LinkedIn posts** — Post about the problem, see who engages and DMs

---

## Assumptions That Could Kill The Business

🚨 **Watch these carefully:**

1. **LP-S1 (Public portfolio connection)** — If LPs won't connect brokerage accounts due to privacy/security concerns, the full picture feature dies. Mitigation: manual CSV upload as fallback, read-only OAuth with no trading permissions.

2. **GP-S5 (GPs sharing LP data)** — If GPs won't put their LP relationships on a third-party platform, the marketplace never gets liquidity. Mitigation: start as GP-only SaaS tool, marketplace layer added later once trust is built.

3. **BM-1 (Transaction fee)** — If GPs resist paying a carry on capital raised, the big revenue model breaks. Mitigation: SaaS revenue alone is still a viable business, transaction fee is upside.

4. **NE-1/NE-2 (Network effects)** — Classic chicken-and-egg. Need both sides. Mitigation: start GP-only, build LP side with Mark's personal network before opening marketplace.

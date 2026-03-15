# RaiseOS — AI-Native Capital Raising Platform for Asset Managers

## The Problem (Mark's Unique Insight)

Asset managers today cobble together 4-6 disconnected tools to run their capital raising:
- **CRM:** Salesforce, Affinity, or Dynamo (relationship tracking)
- **OMS:** Allvue, eFront, or Investran (order/subscription management)  
- **Investor Portal:** Juniper Square, iCapital, or a PDF email (LP reporting)
- **Data Room:** Dropbox, Box, or DocSend (due diligence docs)
- **Fund Admin:** SS&C, State Street, or Apex (back office)
- **Marketing:** Canva + email + manual deck distribution

None of these talk to each other. IR teams spend enormous time on data re-entry, reconciliation, and manual status tracking. The fundraise lifecycle from first LP contact to capital call is fragmented, opaque, and painful.

**The insight:** CAIS and iCapital solved the distribution problem for RIAs (the buy side). Nobody has solved the *production* problem for asset managers (the sell side) with a truly integrated, AI-native platform built for the whole capital raising lifecycle.

---

## Competitive Landscape

### Platforms serving the buy-side (RIA distribution)
| Company | Focus | Valuation | Gap |
|---------|-------|-----------|-----|
| **iCapital** | RIA access to alternatives | $6B | Focused on distribution, not manager ops |
| **CAIS** | RIA marketplace + education | $1B+ | Same — distribution focused |
| **Opto Investments** | RIA alts allocation | Private | Same |
| **Yieldstreet / Fundrise** | Retail alts access | Private | Retail focused |

### Platforms serving the sell-side (asset manager ops)
| Company | Focus | Gap |
|---------|-------|-----|
| **Juniper Square** | RE fund IR + investor portal | Real estate focused, limited AI, no OMS |
| **Allvue Systems** | PE/credit deal + fund mgmt | Complex, expensive, not AI-native |
| **Dynamo Software** | PE CRM + IR | Old UX, limited integrations, no AI |
| **Navatar** | Alts CRM | Basic, Salesforce-dependent |
| **Investran (SS&C)** | Fund accounting + LP mgmt | Back-office only, not capital raising |
| **eFront (BlackRock)** | PE/RE fund mgmt | Enterprise only, $500k+ contracts |
| **Agora** | RE fund raising | Real estate niche only |
| **WealthBlock** | Investor portal | Limited scope, no full lifecycle |

### The Gap
**There is no modern, AI-native, full-lifecycle capital raising platform for emerging and mid-market asset managers** ($100M–$5B AUM). They're too small for eFront/Allvue, underserved by Dynamo/Navatar, and completely ignored by iCapital/CAIS (which serve their LPs, not them).

---

## The Opportunity

**Target market:**
- ~5,000 registered investment advisers managing private funds in the US
- ~15,000 emerging managers globally ($50M–$2B AUM)
- Each spends $50k–$500k/year on cobbled-together technology

**Revenue model:**
- $2,000–$5,000/month per fund manager (all-in platform)
- Path to $10k/mo: 3-5 clients
- Path to $1M ARR: 20-50 clients

---

## Capital Raising Lifecycle — Full User Map

### Phase 1: Strategy & Fund Setup
```
Fund Manager
├── Define fund strategy, terms, target size
├── Build fund marketing materials (deck, tear sheet, DDQ)
├── Set up data room (PPM, LPA, financials)
└── Configure fund structure (GP/LP, fees, hurdle, carry)
```

### Phase 2: Prospect Development
```
IR Team
├── Build target LP list (family offices, endowments, pension, RIAs)
├── Research LP preferences, mandate, AUM, prior commitments
├── Outreach campaign (email sequences, LinkedIn, warm intros)
├── Track engagement (open rates, doc views, meeting requests)
└── Qualify prospects → Interested LPs
```

### Phase 3: LP Engagement & Due Diligence
```
Interested LP
├── Request intro meeting → schedule → prep briefing
├── Initial meeting → follow-up materials
├── Due diligence request list (DDQ, references, audited financials)
├── Data room access granted → track document views
├── Follow-up calls → Q&A management
├── Reference checks
└── IC approval → Soft circle
```

### Phase 4: Subscription & Closing
```
Soft Circled LP
├── Send subscription documents
├── KYC/AML verification
├── Investor accreditation verification
├── Subscription agreement execution (e-sign)
├── Wire instructions
├── Capital call notice
├── Capital receipt confirmation
└── Closing → LP officially onboarded
```

### Phase 5: Investor Relations (Ongoing)
```
Onboarded LP
├── Quarterly reports (NAV, performance, portfolio updates)
├── Capital call notices
├── Distribution notices
├── Annual meeting / LP day
├── Ad-hoc communications
├── Co-investment opportunities
└── Re-up for next fund
```

### Phase 6: Next Fund Raise
```
Existing LP → Preferred prospect for Fund II
├── Track commitment history
├── Performance track record
├── Re-up probability scoring
└── Warm outreach for Fund II
```

---

## Product Vision

**"The AI-native operating system for private fund capital raising — from first LP contact to final close, all in one place."**

RaiseOS replaces the cobbled-together stack with a single platform that:
1. **Knows your LPs** — unified CRM with AI-enriched LP profiles, engagement scoring, mandate matching
2. **Runs your pipeline** — full fundraise pipeline from prospect to closed LP with AI-powered next actions
3. **Manages your documents** — smart data room, DDQ automation, e-signature built in
4. **Handles subscriptions** — digital subscription workflow, KYC/AML, capital call management
5. **Powers your IR** — LP portal, automated quarterly reports, distribution notices
6. **Learns and improves** — AI that analyzes what's working in your fundraise and tells you what to do next

---

## Product Strategy

### Wedge (MVP): The AI IR Copilot
Start narrow: an AI assistant that sits on top of whatever tools they already have and makes the IR team dramatically more productive.
- Connects to their existing CRM (Salesforce, HubSpot)
- Ingests LP meeting notes, emails, and documents
- Generates: LP briefing docs, follow-up emails, DDQ responses, quarterly report drafts
- Surfaces: which LPs to call today, who hasn't responded, what's blocking each deal

### Phase 2: Replace the CRM
Once trust is established, replace their Salesforce/Dynamo with our native CRM — built specifically for LP relationship management, not generic sales.

### Phase 3: Full Platform
Add data room, subscription management, LP portal, fund reporting. Full lifecycle.

---

## Go-to-Market

### ICP (Ideal Customer Profile)
- Emerging/mid-market private equity, private credit, or real assets manager
- $100M–$2B AUM, raising Fund II or III
- IR team of 1-5 people
- Currently using Salesforce + shared drives + DocSend + manual emails

### First 10 Customers
- Mark's CAIS network — asset managers who distribute through CAIS
- Emerging manager programs at major prime brokers (Goldman, Morgan Stanley)
- AngelList / iCapital emerging manager cohorts
- Alternative investment conferences (iConnections, SALT, Context Summits)

### Pricing
- **Starter:** $1,500/mo — AI IR Copilot only (CRM overlay + AI writing)
- **Growth:** $3,000/mo — Full CRM + data room + pipeline management
- **Platform:** $5,000/mo — Full stack including LP portal + subscription management

---

## Roadmap

### Month 1-2: AI IR Copilot MVP
- LP profile enrichment (connect to CRM, auto-research LPs)
- AI email drafting (follow-ups, DDQ responses, intro emails)
- Meeting prep generator (pull LP history + generate briefing)
- Pipeline dashboard (kanban view of fundraise stages)

### Month 3-4: Native CRM
- Replace their Salesforce with purpose-built LP CRM
- Pipeline stages mapped to capital raising lifecycle
- Document management (data room lite)
- Activity tracking + task management

### Month 5-6: Subscription Module
- Digital subscription documents
- KYC/AML workflow
- E-signature integration (DocuSign/HelloSign)
- Capital call management

### Month 7-12: Full Platform
- LP investor portal
- Quarterly reporting automation
- Fund accounting data integration (SS&C, Advent)
- Analytics and reporting for GPs

---

## The AI Advantage

Every incumbant (Dynamo, Allvue, Juniper Square) was built before LLMs. The AI opportunity:

1. **DDQ Automation** — LPs send 50-100 page due diligence questionnaires. AI reads the fund's docs and auto-drafts responses. 10 hours of work → 10 minutes.
2. **LP Research** — Auto-enrich every LP profile with mandate data, recent investments, contact info, news. Know who to call and why.
3. **Meeting Prep** — One command generates a briefing on any LP: history, mandate, what they care about, what to say.
4. **Quarterly Report Generation** — Connect to fund admin data, auto-draft LP reports with performance narrative.
5. **Next Best Action** — AI analyzes the full pipeline and tells the IR team exactly what to do each day to close the fund fastest.

---

## Why Mark Is Uniquely Positioned

- Works at CAIS — intimate knowledge of how asset managers and their LPs operate
- Sees the pain points from the distribution side every day
- Has a network of potential customers (asset managers distributing through CAIS)
- PM background — can build and ship product fast
- With AI tools, can build a credible MVP in weeks, not months

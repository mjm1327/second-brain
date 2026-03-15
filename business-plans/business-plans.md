# Business Plans — March 14, 2026

Three validated opportunities based on today's research, cross-referenced with live market signals.

---

## Business 1: AdvisorBrief — AI Morning Intelligence for Financial Advisors

### Problem
Financial advisors managing alternative investments (private equity, hedge funds, real assets) are drowning in information. They get PDFs from fund managers, market updates, client emails, and news — but no unified intelligence layer. They waste 1-2 hours/day just gathering context before they can do real work. CAIS and similar platforms solve distribution but not advisor intelligence.

### Solution
A daily AI-generated briefing delivered to financial advisors every morning covering:
- Their specific client portfolios and what moved overnight
- Key narratives in the alts they allocate to (PE, hedge, real estate, credit)
- Talking points for client calls that day
- Market signals relevant to their book

### Target Customers (First)
- Independent RIAs managing $50M–$500M AUM with 20-100% alternatives exposure
- Start with advisors already on CAIS — warm channel, Mark has direct context
- 500-1000 IARs at independent BD firms (LPL, Raymond James, Ameriprise)

### Product Vision
"The Bloomberg Terminal morning brief, built for the independent advisor, powered by AI."

### Strategy
- Start with a Telegram/email daily brief (no app needed initially)
- Charge $99/month per advisor
- Land first 100 users through CAIS network
- Build toward a full advisor intelligence platform

### Roadmap
- **Month 1:** Manual + semi-automated brief for 10 beta advisors (free)
- **Month 2:** Productize the brief delivery, $49/mo early access
- **Month 3:** Personalization (connect to their book/CRM), raise to $99/mo
- **Month 4+:** API integrations with Salesforce, Redtail, Wealthbox CRMs
- **Path to $10k/mo:** 101 advisors at $99/mo = $10k

### App to Build
Web dashboard where advisors log in, see their daily brief, their portfolio snapshot, and upcoming client talking points. Connects to a Brave/X/summarize pipeline on the backend.

---

## Business 2: PolicyPilot — AI Insurance Risk Manager for Startups & Scale-ups

### Problem
Startups and scale-ups ($1M-$50M revenue) are massively underserved on insurance. Traditional brokers are commission-driven generalists who don't understand tech businesses. Founders buy the wrong coverage, overpay, and only find out at claims time. WithCoverage (from the Joe Lonsdale video) is doing this for enterprise — nobody is doing it well for early/growth stage.

### Solution
An AI-powered insurance co-pilot for startups that:
- Analyzes their business model and identifies coverage gaps
- Compares policies across carriers using plain English
- Sends proactive alerts when policies need updating (new product launch, headcount change, fundraise)
- Provides a "risk score" with actionable recommendations
- Earns revenue as a licensed broker (commission) + SaaS fee

### Target Customers (First)
- Seed to Series B startups (10-100 employees)
- Fintech and AI startups specifically (highest risk, most underserved)
- YC, a16z, Sequoia portfolio companies via warm intros

### Product Vision
"Ramp for insurance risk — the automated CFO for your coverage."

### Strategy
- Get licensed as a surplus lines broker (or partner with one)
- Build the AI analysis layer on top of carrier APIs
- Distribution through startup communities (YC forums, Product Hunt, indie hacker)

### Roadmap
- **Month 1-2:** Build the risk analysis tool (no brokerage yet), free audit tool
- **Month 3:** Partner with an MGA or wholesale broker for carrier access
- **Month 4:** Launch paid tier ($299/mo for ongoing monitoring)
- **Month 6+:** Get own broker license, capture full commission
- **Path to $10k/mo:** 34 startups at $299/mo = $10k

### App to Build
Onboarding flow where a startup inputs their business info → AI generates a risk report showing coverage gaps, estimated costs, and recommended policies. Lead gen for brokerage relationships initially.

---

## Business 3: PMPilot — AI Operating System for Product Managers

### Problem
Product managers at mid-market companies ($10M-$500M) have no AI-native workflow. They use Jira + Confluence + Slack + Notion + Google Docs in a disconnected mess. They spend 40% of their time on admin (writing PRDs, update emails, meeting notes, status reports) instead of actual product thinking. DEX (from tonight's video) exists but requires technical setup — no PM will do it alone.

### Strategy
"DEX as a Service" — a fully hosted, no-code version of the personal AI operating system for PMs. You sign up, connect your tools, and get a daily AI chief of staff without touching a terminal.

### Target Customers (First)
- PMs at Series B-D SaaS companies (50-500 employees)
- Fintech PMs specifically — Mark's exact network
- Head of Product / VP Product who want to roll it out to their whole team

### Product Vision
"The AI chief of staff for product teams — built on your tools, learning from your work, getting smarter every day."

### Strategy
- Build a hosted version of the DEX personal OS pattern
- Integrate with Jira, Linear, Notion, Confluence, Slack, Google Calendar out of the box
- No terminal, no setup — just OAuth and go
- Team tier: $49/user/month

### Roadmap
- **Month 1:** Build MVP — daily plan + PRD generator + meeting summary ingestion
- **Month 2:** Connect Jira and Google Calendar via OAuth
- **Month 3:** Add Slack integration + stakeholder tracking
- **Month 4:** Launch team tier, target 5-10 companies
- **Month 6+:** Add custom skills marketplace
- **Path to $10k/mo:** 4 teams of 5 PMs at $49/user = $980/team → 11 teams OR 200 individual PMs at $49/mo

### App to Build
A Next.js web app with:
- Onboarding OAuth flow (Google, Jira, Linear, Slack)
- Daily AI briefing page (calendar + priorities + PRD queue)
- PRD generator (input rough idea → full PRD)
- Meeting digest (paste transcript → action items + stakeholder updates)
- Personal OS settings (goals, working style, CLAUDE.md editor)

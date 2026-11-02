# Jal Jeevan Lottery — a gamified funding model for India's rural tap-water mission

A documents-only policy proposal. It asks whether India's state-lottery culture could be
redirected to fund and promote the Jal Jeevan Mission (JJM), the central scheme to give every
rural household a functional tap connection. The repository holds eleven Markdown strategy and
research papers (about 6,900 lines in total) covering a three-tier ticket design, mission-linked
rules, a marketing plan, a phased roadmap, international case studies (Kerala, Taiwan, Spain,
Thailand, Norway's Pantelotteriet) and an alcohol-retail / bottle-recycling extension. There is
no code, data or model file.

> Status: research-only. Every revenue, uptake and impact figure is a proposal assumption written
> by the author, not an audited number; the "Approved for Phase 1 launch" wording in the documents
> is the author's framing, not a government decision. Not legal, financial or policy advice.

> **New here?** See [How to use this repo with AI (Claude, Gemini, ChatGPT)](HOW_TO_USE_WITH_AI.md).

## What it does
- Proposes three ticket tiers — Green ₹50 (weekly, 35 % prize pool), Blue ₹200 (bi-weekly, 45 %),
  Gold ₹500 (quarterly, 50 %) — with the remainder earmarked for JJM (detail in [LOTTERY_RULES.md](LOTTERY_RULES.md)).
- Specifies mission-linked mechanics: QR-tracked impact per ticket, milestone-triggered bonus draws,
  a "Jal Jeevan Swap" to take winnings as water-connection credits, and bulk purchase by panchayats/NGOs.
- Lays out a five-year financial projection (₹1,500 Cr revenue in Year 1 rising to ₹7,500 Cr in
  Year 5; 650–700 lakh connections funded over five years) and a four-phase rollout starting with a
  two-state pilot (Rajasthan, Uttar Pradesh).
- Summarises how established lotteries operate (Kerala, Taiwan Uniform Invoice, Spain El Niño) and
  the environmental cost of paper tickets, with cited sources.
- Documents Norway's Recycling Lottery (Pantelotteriet, since 2008; 39 % of adults choose the
  lottery option; NOK 737.4 million to the Red Cross by Nov 2023) as the behavioural template.
- Extends the model to alcohol retail: receipt-linked tickets, bottle-return incentives, a bar
  maintenance fund and state-wise revenue estimates.

## The proposal in brief

| Item | Value stated in the documents |
|---|---|
| JJM households to connect | ~16.3 crore; ~5.7 crore covered as of 2024; gap ~10.6 crore |
| JJM budget / timeline | ₹3.6 lakh crore; 2019 → 2030 (extended from 2024) |
| India state-lottery market | ₹500–600 crore/year, 10 operating states, ₹10–₹1,000 tickets |
| Green ticket split | 35 % prizes · 45 % JJM · 20 % distribution and marketing |
| Responsible-gaming caps | ₹2,000/person/month, 18+, self-exclusion, 30 % TDS on winnings |
| Pilot | Months 1–3, Rajasthan + Uttar Pradesh, Green and Blue tickets only |

The India market figures and JJM status were compiled by the author in July 2026 and are not
re-verified here; check the Ministry of Jal Shakti dashboard before quoting them.

## Repository layout

| Path | Purpose |
|---|---|
| `README.md` | This overview |
| `EXECUTIVE_SUMMARY.md` | One-page strategy, KPIs, next steps |
| `LOTTERY_RULES.md` | Operational rules: eligibility, serial formats, draws, claims, disputes |
| `CAMPAIGN_STRATEGY.md` | Marketing by demographic and channel, budget split |
| `IMPLEMENTATION_ROADMAP.md` | Phase 1–4 plan, 2026–2030, go/no-go gates |
| `MASTER_IMPLEMENTATION_STRATEGY.md` | Integrated synthesis of all research (longest document) |
| `GLOBAL_LOTTERY_RESEARCH.md` | Taiwan, Kerala, Spain, Thailand; ticket waste and green printing |
| `NORWAY_RECYCLING_LOTTERY_RESEARCH.md` | Pantelotteriet case study and lessons |
| `ALCOHOL_REVENUE_FORMALIZATION_STRATEGY.md` | TASMAC case and receipt-to-ticket formalisation |
| `ALCOHOL_LOTTERY_RECYCLING_INTEGRATION.md` | Alcohol channel × lottery × bottle recycling |
| `STATE_REVENUE_AND_BAR_MAINTENANCE_STRATEGY.md` | State-wise revenue tiers and bar upkeep fund |
| `PROJECT_COMPLETION_SUMMARY.md` | Author's delivery summary (31 July 2026) |
| `HOW_TO_USE_WITH_AI.md` | How to read the repo with an AI assistant |
| `graphify-out/` | Generated knowledge-graph cache for the `graphify` tool; not hand-edited |
| `.github/workflows/quality-gates.yml` | gitleaks secret scan on push / PR |

Suggested reading order: `EXECUTIVE_SUMMARY.md` → this README → `LOTTERY_RULES.md` →
`IMPLEMENTATION_ROADMAP.md` → the research papers.

## Data sources

The research papers cite public web sources inline and in their `Sources` sections
(e.g. Kerala lottery rules on legitquest.com, UNDP Thailand, TOMRA and Red Cross material on
Pantelotteriet, Loto-Québec eco-design case study). Nothing was scraped or stored; the citations
are links only, and several are secondary or commercial lottery-guide sites rather than primary
regulator documents.

## Limitations and known issues
- Proposal figures (ticket volumes, revenue, connections funded, awareness lifts) are unsourced
  assumptions; no financial model file exists in the repo.
- Legal basis is only sketched: the Lotteries (Regulation) Act 1998 leaves lotteries to the states,
  and several states ban them; the documents assume amendments that have not happened.
- The "Brazil water lottery" and "Tamil Nadu school lottery" case studies in the proposal are
  not cited to a source.
- Appendices referred to in older drafts (ticket design, app wireframes, financial spreadsheet,
  campaign concepts) were never added to the repository.

## Licence
No licence file yet — all rights reserved.

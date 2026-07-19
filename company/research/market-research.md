# Market Research

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-111 |
| Document Name | Market Research |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Office / Research Steward |
| Reviewer | CEO · CPO (Founder Board) |
| Approver | Founder Board |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Establish TAM/SAM/SOM framing, buyer segments, and demand drivers for Subscription OS and Pawn Management. |
| Scope | Company-level market synthesis; not a substitute for product PRDs or discovery charters. |

## Navigation

| Link | Target |
| --- | --- |
| Parent | [Research Center](./README.md) |
| Child | None |
| Related | [Competitor Analysis](./competitor-analysis.md) · [Pricing Research](./pricing-research.md) · [Industry Reports](./industry-reports.md) · [Business Terms Wiki](../wiki/business-terms.md) |
| Previous | [Research Center](./README.md) |
| Next | [Competitor Analysis](./competitor-analysis.md) |
| Back to START-HERE | [START-HERE.md](../START-HERE.md) |

## Research Framework

| Lens | Questions |
| --- | --- |
| **Problem** | What jobs are buyers hiring software for today? What is broken or expensive? |
| **Buyer** | Economic buyer vs champion vs end user |
| **Market structure** | Concentrated vs fragmented; switching costs; channel power |
| **Timing** | Regulatory, payment, or digitization waves that change urgency |
| **Gojen fit** | Where can a dual-product company win without diluting focus? |

### Sizing method

1. Define unit of demand (billing seats / transactions / stores / tickets).
2. Estimate **TAM** from industry population × willingness to pay for category software.
3. Narrow to **SAM** by geography, language, and compliance reachable in 24 months.
4. Derive **SOM** from realistic sales capacity and product maturity for the next 12–18 months.
5. Record confidence and open questions; do not present fabricated precision.

## Subscription OS — Market Framing

### Category definition

Software that manages **recurring commercial relationships**: plans, subscriptions, invoices, usage metering, proration, dunning, entitlements, and revenue recognition handoffs. Buyers include B2B SaaS, digital media, and platform businesses that outgrow spreadsheet billing or single-gateway “subscriptions” features.

### Demand drivers

| Driver | Implication |
| --- | --- |
| Usage-based and hybrid pricing | Need flexible metering and rating, not only seat catalogs |
| Multi-entity and multi-currency growth | Invoicing, tax adjacency, and auditability become table stakes |
| Churn and failed-payment leakage | Dunning and payment recovery are ROI features, not admin extras |
| Finance/ops alignment | Controllers and RevOps want exportable ledgers and clear events |

### Segment hypotheses

| Segment | Buyer | Pain signal | Priority |
| --- | --- | --- | --- |
| Early B2B SaaS (Series A–B) | Founder / Head of Finance | Stripe Billing + sheets; plan changes are error-prone | Primary beachhead |
| Mid-market SaaS | VP Finance / RevOps | Needs entitlements, trials, and partner pricing | Secondary |
| Platforms with sub-accounts | Product / Platform lead | Nested billing and reseller models | Watchlist |

### Current findings status — Subscription OS

| Finding | Confidence | Status |
| --- | --- | --- |
| Category spend continues to concentrate around billing platforms and finance-adjacent suites; greenfield “billing-only” tools compete on flexibility and developer experience | Medium | Active |
| Hybrid pricing (seat + usage) is a common expansion trigger away from gateway-native billing | Medium | Active |
| Buyers distrust black-box proration and invoice corrections; transparency is a differentiation vector | High | Active |
| Quantitative TAM/SAM/SOM figures require a dedicated sizing sprint with sourced inputs | Low | Open — not yet sized |

## Pawn Management — Market Framing

### Category definition

Operational software for **pawn and collateral lending businesses**: loan tickets, collateral intake and valuation, storage/inventory, renewals and redemptions, forfeitures and sales, compliance reporting, and multi-store controls.

### Demand drivers

| Driver | Implication |
| --- | --- |
| Digitization of store ops | Paper/Excel ticket books create audit and loss risk |
| Multi-location expansion | Central visibility of inventory, cash, and risk limits |
| Regulatory and KYC pressure | Audit trails and reporting must be first-class |
| Secondary-market retail | Forfeited goods sales and POS adjacency matter |

### Segment hypotheses

| Segment | Buyer | Pain signal | Priority |
| --- | --- | --- | --- |
| Independent single-store operators | Owner-operator | Legacy desktop POS or paper; limited mobile | Beachhead candidate |
| Regional multi-store chains | Ops director / owner | Need centralized reporting and role controls | Primary strategic |
| Specialty collateral verticals | Vertical ops lead | Jewelry, electronics, tools valuation workflows | Differentiation theme |

### Current findings status — Pawn Management

| Finding | Confidence | Status |
| --- | --- | --- |
| Market is fragmented with many regional/legacy vendors; switching cost is process lock-in, not only license fee | Medium | Active |
| Compliance and auditability are purchase drivers equal to “POS speed” | Medium | Active |
| Valuation and inventory integrity are core product moats, not bolt-ons | High | Active |
| Jurisdiction-specific lending rules require a compliance matrix before GTM claims | Medium | Open |

## Cross-Portfolio Themes

1. Both products sell **operational trust** (money movement accuracy, audit trails).
2. Both have **regulated or finance-adjacent** expectations even when not themselves banks.
3. Dual focus is viable if research and decisions stay product-scoped; shared platforms must be explicit (see Decision Register and dual-product risk).

## Open Research Questions

- Which geography is first for each product, and what compliance package is mandatory at launch?
- Is Subscription OS sold self-serve, sales-assisted, or both in year one?
- For Pawn Management, is the wedge ticket lifecycle, inventory, or compliance reporting?

## Related Documents

- [Competitor Analysis](./competitor-analysis.md)
- [Customer Interviews](./customer-interviews.md)
- [Pricing Research](./pricing-research.md)
- [Industry Reports](./industry-reports.md)
- [DEC-GPO-003 Product Portfolio Structure](../decision-register/dec-gpo-003-product-portfolio-structure.md)
- [Business Terms](../wiki/business-terms.md) · [Root glossary business terms](../../glossary/business-terms.md)

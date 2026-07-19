# Pricing Research

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-114 |
| Document Name | Pricing Research |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Office / Research Steward |
| Reviewer | CEO · Finance lead (Founder Board) |
| Approver | Founder Board |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Frame pricing model hypotheses, willingness-to-pay research methods, and packaging options for Subscription OS and Pawn Management. |
| Scope | Company-level pricing research; commercial offers are finalized only via Decision Register approval. |

## Navigation

| Link | Target |
| --- | --- |
| Parent | [Research Center](./README.md) |
| Child | None |
| Related | [Market Research](./market-research.md) · [Competitor Analysis](./competitor-analysis.md) · [Business Terms](../wiki/business-terms.md) |
| Previous | [Customer Interviews](./customer-interviews.md) |
| Next | [Technology Research](./technology-research.md) |
| Back to START-HERE | [START-HERE.md](../START-HERE.md) |

## Pricing Research Framework

| Method | Use when | Output |
| --- | --- | --- |
| Van Westendorp / price sensitivity meter | Need directional WTP bands | Acceptable price ranges |
| Conjoint / discrete choice (lightweight) | Packaging trade-offs matter | Feature × price preference |
| Competitive price mapping | Market anchors exist | Anchor table |
| Value metric analysis | Choosing the billable unit | Metric shortlist |
| Cost-to-serve model | Margin discipline | Floor pricing |

```mermaid
flowchart LR
  Value["Value metric"] --> Package["Packaging"]
  Package --> Price["Price points"]
  Price --> Guard["Discount guardrails"]
  Guard --> Decide["Decision record"]
```

## Subscription OS — Pricing Hypotheses

### Candidate value metrics

| Metric | Pros | Cons |
| --- | --- | --- |
| Active subscriptions / accounts | Aligns with growth | Can punish high-volume low-ARPU |
| Monthly invoice volume | Aligns with ops load | Spiky; harder for buyers to forecast |
| Revenue under management (RUM) % | Captures value | Buyers resist % of GMV early |
| Seats (admin / finance users) | Simple | Decouples from usage complexity |
| Hybrid: base platform + usage overage | Flexible | Needs clear metering UX |

### Packaging draft

| Tier | Intended ICP | Included themes |
| --- | --- | --- |
| Starter | Early SaaS | Plans, invoices, basic dunning, Stripe (or peer) connection |
| Growth | Scaling SaaS | Usage metering, entitlements, multi-entity, exports |
| Scale | Mid-market | Advanced recovery, approvals, SLA, dedicated success |

### Findings status — Subscription OS

| Finding | Confidence | Status |
| --- | --- | --- |
| Hybrid packaging (platform fee + usage) matches category norms for complex billing | Medium | Active hypothesis |
| Pure RUM % is likely a later-stage motion, not beachhead | Medium | Active |
| Public competitor list prices are poor WTP proxies for mid-market deals | High | Active |
| Final list prices deferred until interview WTP and cost-to-serve exist | — | Open decision |

## Pawn Management — Pricing Hypotheses

### Candidate value metrics

| Metric | Pros | Cons |
| --- | --- | --- |
| Per store / location / month | Easy to understand | Underprices high-ticket volume stores |
| Per active ticket / loan | Aligns with ops volume | May feel punitive in busy months |
| Flat + per-user (counter staff) | Predictable | Weak link to lending volume |
| Module add-ons (compliance, multi-store, valuation) | Land-and-expand | Complexity in sales |

### Packaging draft

| Package | Intended ICP | Included themes |
| --- | --- | --- |
| Store | Single location | Tickets, inventory, basic reports |
| Multi-Store | Regional chain | Central dashboard, roles, consolidated reporting |
| Compliance+ | Regulated-heavy regions | Expanded audit packs, export suites |

### Findings status — Pawn Management

| Finding | Confidence | Status |
| --- | --- | --- |
| Per-store SaaS is the most familiar buying frame for independent operators | High | Active hypothesis |
| Multi-store upsell should be priced on locations + control features, not only seats | Medium | Active |
| Implementation / data migration fees are often larger objections than monthly SaaS | Medium | Active |
| Regional compliance packs may justify premium modules | Medium | Open |

## Guardrails

1. No public price commitments in marketing until a pricing decision is Approved.
2. Discount authority follows the [Authority Matrix](../governance/authority-matrix.md).
3. AI assistants may propose models; they may not invent “approved” prices.

## Related Documents

- [Market Research](./market-research.md)
- [Competitor Analysis](./competitor-analysis.md)
- [Customer Interviews](./customer-interviews.md)
- [Authority Matrix](../governance/authority-matrix.md)
- [Root glossary — business terms](../../glossary/business-terms.md)

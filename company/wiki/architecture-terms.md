# Architecture Terms

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-164 |
| Document Name | Architecture Terms |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Solution Architecture / Product Office |
| Reviewer | Founder Board |
| Approver | Founder Board |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Define architecture vocabulary used across Subscription OS and Pawn Management discussions in GAIOS. |
| Scope | Operating definitions; binding ADRs supersede when issued. Links to root technical glossary. |

## Navigation

| Link | Target |
| --- | --- |
| Parent | [Company Wiki](./README.md) |
| Child | None |
| Related | [Root Technical Terms](../../glossary/technical-terms.md) · [Technology Research](../research/technology-research.md) · [Business Terms](./business-terms.md) · [Acronyms](./acronyms.md) |
| Previous | [FAQs](./faqs.md) |
| Next | [Business Terms](./business-terms.md) |
| Back to START-HERE | [START-HERE.md](../START-HERE.md) |

## Canonical technical glossary

Prefer [../../glossary/technical-terms.md](../../glossary/technical-terms.md) for shared Product Office technical vocabulary. This page adds product-domain architecture language.

## Subscription OS terms

| Term | Definition |
| --- | --- |
| **Billing engine** | System that rates plans/usage and produces invoice-ready charges |
| **Subscription lifecycle** | States from trial/create through change, pause, cancel, and win-back |
| **Proration** | Adjustment of charges when plan or quantity changes mid-period |
| **Dunning** | Process for recovering failed recurring payments |
| **Entitlement** | Right to access a feature/capacity derived from subscription state |
| **Metering** | Collection and aggregation of usage events for rating |
| **Invoice timeline** | Ordered, auditable history of invoice mutations and payments |
| **PSP** | Payment Service Provider (e.g., card gateway) — dependency, not SSOT for subscription state |
| **Multi-tenant isolation** | Technical controls separating customer data and workloads |
| **Idempotency key** | Client key ensuring duplicate requests do not double-charge |

## Pawn Management terms

| Term | Definition |
| --- | --- |
| **Loan ticket** | System record of a pawn/collateral loan agreement and status |
| **Collateral intake** | Workflow capturing item identity, condition, photos, and appraisal |
| **Chain of custody** | Traceable control of physical collateral from intake to exit |
| **Redemption** | Customer repays and retrieves collateral |
| **Forfeiture** | Collateral becomes store inventory after contractual conditions |
| **Holding period** | Regulatory/business period before certain actions are allowed |
| **Store sync** | Replication/conflict handling between counter clients and cloud |
| **Void / reverse** | Privileged correction of a ticket or cash event with audit |
| **Compliance export** | Structured report package for regulatory or audit needs |
| **Multi-store control plane** | HQ visibility and policy over locations |

## Cross-cutting terms

| Term | Definition |
| --- | --- |
| **ADR** | Architecture Decision Record — durable technical choice |
| **Event-sourced history** | State reconstructed from immutable events (useful for money/tickets) |
| **Audit trail** | Who changed what, when, and why — required for both products |
| **Offline-first** | UX/architecture prioritizing local operation with later sync (pawn counters) |
| **Shared service** | Cross-product capability shared only via Approved decision |

## Related Documents

- [Technology Research](../research/technology-research.md)
- [Root Technical Terms](../../glossary/technical-terms.md)
- [Acronyms](./acronyms.md)

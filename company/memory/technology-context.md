# Technology Context

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-034 |
| Document Name | Technology Context |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Gojen Product Office |
| Reviewer | Gomathi K (Founder & CEO) |
| Approver | Founder Board |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Technology posture and boundaries for GAIOS-aware engineering collaboration |
| Scope | Company-level technology memory for the Product Office repository and product interfaces |
| Related Documents | [architecture-standards.md](../ai-governance/architecture-standards.md), [coding-standards.md](../ai-governance/coding-standards.md), [product-context.md](./product-context.md) |

## Navigation

| Link | Target |
| --- | --- |
| Parent Document | [README.md](./README.md) |
| Child Documents | None |
| Related Documents | [repository-standards.md](../ai-governance/repository-standards.md), [AI-RULES.md](../ai-governance/AI-RULES.md), [START-HERE.md](../START-HERE.md) |
| Previous | [business-context.md](./business-context.md) |
| Next | [founder-context.md](./founder-context.md) |
| Back to START-HERE | [START-HERE.md](../START-HERE.md) |

---

## Repository technology role

`gojen-product-office` is the Product Office SSOT: documentation, standards, governance, and product lifecycle workspaces. It may contain supporting engineering and architecture documentation at repository root (`engineering/`, `architecture/`), but GAIOS itself is a markdown operating system, not an application runtime.

---

## Technology principles

1. **Docs before drift** — Architectural choices for products are written under product architecture folders.
2. **AI-assisted, human-approved** — AI may draft technical content; humans approve material design.
3. **Security hygiene** — No secrets in markdown or commits.
4. **Minimal coupling** — GAIOS links to product tech docs; it does not fork them.
5. **Traceability** — Prefer Document IDs and relative links for technical decisions.

---

## Where technical truth lives

| Concern | Prefer |
| --- | --- |
| Subscription OS architecture | `products/subscription-os/06-architecture/` |
| Subscription OS engineering plans | `products/subscription-os/07-engineering/` |
| Company repo rules | [GPO-STD-005](../standards/repository-rules.md) + [repository-standards.md](../ai-governance/repository-standards.md) |
| GAIOS system map | [START-HERE.md](../START-HERE.md), [architecture-standards.md](../ai-governance/architecture-standards.md) |

---

## AI engineering guidance

Follow [coding-standards.md](../ai-governance/coding-standards.md) and [AI-RULES.md](../ai-governance/AI-RULES.md). Do not treat chat proposals as architecture decisions until recorded through the decision lifecycle or an ADR/decision log entry.

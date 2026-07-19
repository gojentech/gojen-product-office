# Architecture Standards (GAIOS)

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-026 |
| Document Name | Architecture Standards |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Gojen Product Office |
| Reviewer | Gomathi K (Founder & CEO) |
| Approver | Founder Board |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Architecture boundaries for GAIOS and how it relates to product architecture |
| Scope | Company operating-system architecture and interfaces to product workspaces |
| Related Documents | [technology-context.md](../memory/technology-context.md), [repository-standards.md](./repository-standards.md), [START-HERE.md](../START-HERE.md) |

## Navigation

| Link | Target |
| --- | --- |
| Parent Document | [README.md](./README.md) |
| Child Documents | None |
| Related Documents | [coding-standards.md](./coding-standards.md), [product-context.md](../memory/product-context.md), [AI-CONTEXT.md](./AI-CONTEXT.md) |
| Previous | [repository-standards.md](./repository-standards.md) |
| Next | [coding-standards.md](./coding-standards.md) |
| Back to START-HERE | [START-HERE.md](../START-HERE.md) |

---

## Architectural layers

| Layer | Location | Responsibility |
| --- | --- | --- |
| GAIOS navigation | `company/START-HERE.md`, `INDEX.md`, `SEARCH.md` | Entry and discovery |
| GAIOS control plane | `company/ai-governance/` | Rules, workflows, standards, matrices |
| GAIOS memory | `company/memory/` | Durable summaries for humans and AI |
| Product Office standards | `company/standards/` | Authoritative GPO-STD documents |
| Product systems | `products/*` | Product discovery through release artifacts |
| Engineering assets | `engineering/`, `architecture/` (repo root) | Technical depth outside GAIOS docs |

GAIOS is a documentation and operating architecture. It does not replace product application architecture under Subscription OS or Pawn Management.

---

## Boundaries

1. **No second product SSOT** — Product requirements and designs stay in product folders.
2. **Memory is summary, not source** — If memory conflicts with product docs, product docs win until memory is updated.
3. **Standards layering** — GPO-STD is base law; GOS-GPO standards extend for AI collaboration.
4. **Planned folders** — New GAIOS surfaces (dashboards, registers, agents, etc.) must declare owner and purpose in START-HERE / INDEX when created.

---

## Diagramming

Use Mermaid for flows, state machines, and folder maps in GAIOS docs when it improves clarity (required examples already live in START-HERE, AI-WORKFLOW, DOCUMENT-LIFECYCLE, DECISION-LIFECYCLE).

Product architecture diagrams belong primarily under `products/*/06-architecture/` for Subscription OS.

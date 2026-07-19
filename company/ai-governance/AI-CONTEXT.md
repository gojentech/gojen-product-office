# AI Context

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-011 |
| Document Name | AI Context |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Gojen Product Office |
| Reviewer | Gomathi K (Founder & CEO) |
| Approver | Founder Board |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Durable operating context every AI assistant must load before productive work |
| Scope | All AI sessions in gojen-product-office |
| Related Documents | [START-HERE.md](../START-HERE.md), [AI-RULES.md](./AI-RULES.md), [memory/README.md](../memory/README.md) |

## Navigation

| Link | Target |
| --- | --- |
| Parent Document | [README.md](./README.md) |
| Child Documents | None |
| Related Documents | [CURRENT-SPRINT.md](./CURRENT-SPRINT.md), [AI-SESSION-CHECKLIST.md](./AI-SESSION-CHECKLIST.md), [company-context.md](../memory/company-context.md) |
| Previous | [README.md](./README.md) |
| Next | [CURRENT-SPRINT.md](./CURRENT-SPRINT.md) |
| Back to START-HERE | [START-HERE.md](../START-HERE.md) |

---

## Organization snapshot

| Item | Value |
| --- | --- |
| Company | Gojen Technology |
| Repository | `gojen-product-office` |
| Operating system | GAIOS v1.0 (Gojen AI Operating System) |
| SSOT | GitHub (this repository) |
| AI role | Collaborator — not an independent authority |

### Founders

| Name | Role |
| --- | --- |
| Gomathi K | Founder & CEO |
| Gowtham | Co-Founder |
| Arul Jeni | Co-Founder |

---

## Product landscape

| Product | Priority | Workspace |
| --- | --- | --- |
| Subscription OS | Primary | [products/subscription-os/](../../products/subscription-os/README.md) — lifecycle folders ready |
| Pawn Management | Active workspace | [products/pawn-management/](../../products/pawn-management/README.md) |

Product artifacts live under `products/`. GAIOS provides company-level memory, governance, and AI operating rules. Do not invent product requirements that contradict product folders.

---

## Mandatory context stack

Load in this order for every non-trivial session:

1. [START-HERE.md](../START-HERE.md)
2. This document (AI-CONTEXT)
3. [CURRENT-SPRINT.md](./CURRENT-SPRINT.md)
4. Relevant files from [memory/](../memory/README.md)
5. Task-specific product or standards documents
6. [AI-RULES.md](./AI-RULES.md) and [AI-SESSION-CHECKLIST.md](./AI-SESSION-CHECKLIST.md)

---

## Truth hierarchy

When sources conflict, prefer higher rows:

| Priority | Source |
| --- | --- |
| 1 | Explicit human instruction in the current session (within safety/legal bounds) |
| 2 | Approved Founder Board decisions recorded in-repo |
| 3 | Approved GAIOS and GPO-STD documents |
| 4 | Product workspace READMEs and approved product docs |
| 5 | Memory pack summaries |
| 6 | AI inference or prior chat memory |

Chat history is ephemeral. Repository documents are durable.

---

## Existing standards (always respect)

| ID | Link |
| --- | --- |
| GPO-STD-001 | [document-numbering.md](../standards/document-numbering.md) |
| GPO-STD-002 | [versioning.md](../standards/versioning.md) |
| GPO-STD-003 | [writing-style.md](../standards/writing-style.md) |
| GPO-STD-004 | [meeting-process.md](../standards/meeting-process.md) |
| GPO-STD-005 | [repository-rules.md](../standards/repository-rules.md) |

---

## Working posture

- Prefer additive changes under new paths when building GAIOS.
- Do not modify, overwrite, or delete existing protected company or product files unless a human explicitly authorizes a change request for those paths.
- Use relative links for cross-references.
- Record decisions through the [DECISION-LIFECYCLE.md](./DECISION-LIFECYCLE.md).
- Keep founders informed via [FOUNDER-BOARD-PACK.md](./FOUNDER-BOARD-PACK.md) patterns for material changes.

---

## Current focus pointer

Active sprint: **SPR-001 — SubscriptionOS Discovery** ([CURRENT-SPRINT.md](./CURRENT-SPRINT.md)). Foundation closed: [SPR-000-GAIOS-Foundation.md](../sprints/SPR-000-GAIOS-Foundation.md). Board decision: [DEC-001](../decision-register/DEC-001-GAIOS-Adoption.md).

# DEC-GPO-001 — GitHub as Single Source of Truth

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-122 |
| Document Name | DEC-GPO-001 GitHub as Single Source of Truth |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Founder Board / Product Office |
| Reviewer | Founder Board |
| Approver | Founder Board |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Record the decision that the gojen-product-office GitHub repository is the official company knowledge base. |
| Scope | Company knowledge, decisions, processes, and AI collaboration rules for Gojen Technology. |

## Navigation

| Link | Target |
| --- | --- |
| Parent | [Decision Register](./README.md) |
| Child | None |
| Related | [REGISTER.md](./REGISTER.md) · [DEC-GPO-002](./dec-gpo-002-gaios-v1-adoption.md) · [GAIOS Governance Charter](../governance/gaios-governance-charter.md) · [Risk: AI Hallucination](../risk-register/risk-gpo-002-ai-hallucination-as-source.md) |
| Previous | [REGISTER.md](./REGISTER.md) |
| Next | [DEC-GPO-002](./dec-gpo-002-gaios-v1-adoption.md) |
| Back to START-HERE | [START-HERE.md](../START-HERE.md) |

## Decision Fields

| Field | Content |
| --- | --- |
| **Decision ID** | DEC-GPO-001 |
| **Owner** | Founder Board, stewarded by Product Office |
| **Problem Statement** | Company knowledge is at risk of fragmentation across chat tools, local files, and AI sessions. Without an explicit system of record, founders and AI assistants will treat transient conversations as truth. |
| **Options Considered** | See below |
| **Decision** | GitHub repository `gojen-product-office` is the official single source of truth (SSOT) for company knowledge that must survive beyond a chat or meeting. |
| **Reason** | Version control, reviewability, durable links, and audit history align with enterprise documentation practice and AI collaboration (draft in chat → commit to repo). |
| **Impact** | All durable decisions, standards, research conclusions, and operating rules must be promoted into this repository. ChatGPT, Cursor, and similar tools are collaborators, not authorities. |
| **Status** | Approved |
| **Approval** | Founder Board · 2026-07-18 |
| **Review Date** | 2026-10-18 |

## Options Considered

| Option | Summary | Pros | Cons |
| --- | --- | --- | --- |
| A — GitHub SSOT | This repository is authoritative | Reviewable, linkable, AI-friendly | Requires discipline to commit |
| B — Notion / wiki SSOT | External wiki primary | Rich editing UX | Drift from eng workflows; weaker PR discipline |
| C — Chat memory SSOT | AI threads as truth | Fast capture | Non-auditable, hallucinated, ephemeral |
| D — Hybrid equal sources | Multiple equals | Familiar to individuals | Guarantees fragmentation |

## Decision

Adopt **Option A**. External tools may be used for drafting and collaboration, but promotion into GitHub is required before a statement is treated as company policy, product direction, or approved research conclusion.

## Reason

- Enables pull-request review for material changes.
- Creates a durable trail compatible with GAIOS decision and risk registers.
- Prevents AI hallucination from becoming de facto policy (see Risk GPO-002).

## Impact

| Area | Change |
| --- | --- |
| Founders | Commit or PR material decisions; do not leave them only in chat |
| AI assistants | Must cite repository docs; must not invent Approved status |
| Employees (future) | Onboard via START-HERE and repository structure |
| Products | Product workspaces inherit the same SSOT rule |

## Status

Approved.

## Approval

Founder Board approval recorded 2026-07-18 as part of GAIOS v1.0 adoption.

## Review Date

2026-10-18 — reaffirm SSOT tooling choice and any exceptions (e.g., private PII stores).

## Related Documents

- [DEC-GPO-002 GAIOS v1.0 Adoption](./dec-gpo-002-gaios-v1-adoption.md)
- [Risk GPO-001 Knowledge Fragmentation](../risk-register/risk-gpo-001-knowledge-fragmentation.md)
- [Risk GPO-002 AI Hallucination as Source](../risk-register/risk-gpo-002-ai-hallucination-as-source.md)
- [Repository Rules](../standards/repository-rules.md)

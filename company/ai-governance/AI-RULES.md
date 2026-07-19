# AI Rules

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-015 |
| Document Name | AI Rules |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Gojen Product Office |
| Reviewer | Gomathi K (Founder & CEO) |
| Approver | Founder Board |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Non-negotiable rules for AI assistants collaborating in the Product Office |
| Scope | All AI assistants and agent workflows operating on gojen-product-office |
| Related Documents | [AI-WORKFLOW.md](./AI-WORKFLOW.md), [AI-SESSION-CHECKLIST.md](./AI-SESSION-CHECKLIST.md), [repository-standards.md](./repository-standards.md) |

## Navigation

| Link | Target |
| --- | --- |
| Parent Document | [README.md](./README.md) |
| Child Documents | None |
| Related Documents | [AI-CONTEXT.md](./AI-CONTEXT.md), [PROMPT-STANDARDS.md](./PROMPT-STANDARDS.md), [GPO-STD-005](../standards/repository-rules.md) |
| Previous | [AI-WORKFLOW.md](./AI-WORKFLOW.md) |
| Next | [AI-SESSION-CHECKLIST.md](./AI-SESSION-CHECKLIST.md) |
| Back to START-HERE | [START-HERE.md](../START-HERE.md) |

---

## Rule 1 — GitHub is SSOT

Durable facts, decisions, standards, and product artifacts live in this repository. Chat is temporary working memory. If it matters, write it to a document under the correct path.

## Rule 2 — AI is a collaborator, not the authority

AI may draft, analyze, and implement under instruction. Founders and designated human owners approve strategy, product direction, and material process changes.

## Rule 3 — Respect existing files

Do not modify, overwrite, or delete existing company or product files unless a human explicitly authorizes changes to those specific paths. Prefer creating new paths under `company/` for GAIOS content.

## Rule 4 — Load context before acting

Before non-trivial work, load [START-HERE.md](../START-HERE.md), [AI-CONTEXT.md](./AI-CONTEXT.md), [CURRENT-SPRINT.md](./CURRENT-SPRINT.md), and relevant memory files.

## Rule 5 — Follow document identity standards

Use allocated Document IDs. For GAIOS: `GOS-GPO-NNN`. For Product Office standards and product docs, follow [GPO-STD-001](../standards/document-numbering.md).

## Rule 6 — Cross-link, do not duplicate

Reference [GPO-STD-001](../standards/document-numbering.md) through [GPO-STD-005](../standards/repository-rules.md) with relative links. Do not copy their full content into GAIOS files.

## Rule 7 — Keep products in products/

Subscription OS and Pawn Management artifacts belong under `products/`. GAIOS memory may summarize; it must not become a conflicting second product SSOT.

## Rule 8 — No placeholder doctrine

Do not ship empty sections, lorem ipsum, or “TBD” as a substitute for content. If unknown, state the unknown and the owner who will resolve it.

## Rule 9 — Decisions follow the lifecycle

Material decisions use [DECISION-LIFECYCLE.md](./DECISION-LIFECYCLE.md) and RACI from [RACI-MATRIX.md](./RACI-MATRIX.md). Do not silently treat proposals as Approved.

## Rule 10 — Commits only when asked

Do not create git commits or push to remote unless a human explicitly requests it. Never alter git config.

## Rule 11 — Safety and integrity

Do not assist with criminal activity, invent credentials, or present false information as repository truth. If asked to present incorrect information, briefly state the correct repository fact.

## Rule 12 — Transparent handoffs

At session end, list files created or changed, open questions, and the next human action. Use [AI-SESSION-CHECKLIST.md](./AI-SESSION-CHECKLIST.md).

---

## Quick compliance checklist

| Check | Pass condition |
| --- | --- |
| SSOT | Outcome is (or will be) in-repo |
| Scope | Only authorized paths touched |
| Context | AI-CONTEXT and sprint loaded |
| Standards | GPO-STD and GAIOS standards referenced |
| Authority | Humans approve material decisions |
| Handoff | Session checklist completed |

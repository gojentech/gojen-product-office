# RISK-GPO-002 — AI Hallucination Treated as Source of Truth

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-133 |
| Document Name | RISK-GPO-002 AI Hallucination as Source |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Office / AI Governance |
| Reviewer | Founder Board |
| Approver | Founder Board |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Mitigate the risk that AI-generated content is mistaken for approved company knowledge. |
| Scope | All AI assistants used by Gojen founders and teams (Cursor, ChatGPT, and others). |

## Navigation

| Link | Target |
| --- | --- |
| Parent | [Risk Register](./README.md) |
| Child | None |
| Related | [DEC-GPO-001](../decision-register/dec-gpo-001-github-as-ssot.md) · [GAIOS Governance Charter](../governance/gaios-governance-charter.md) · [AI Session Template](../templates/ai-session-template.md) · [Compliance Checklist](../governance/compliance-checklist.md) |
| Previous | [RISK-GPO-001](./risk-gpo-001-knowledge-fragmentation.md) |
| Next | [RISK-GPO-003](./risk-gpo-003-dual-product-focus.md) |
| Back to START-HERE | [START-HERE.md](../START-HERE.md) |

## Risk Record

| Field | Content |
| --- | --- |
| **Risk ID** | RISK-GPO-002 |
| **Category** | AI |
| **Probability** | High |
| **Impact** | High |
| **Mitigation** | See controls below |
| **Owner** | Product Office / AI Governance |
| **Current Status** | Mitigating |

## Description

Large language models can invent pricing, competitor claims, customer quotes, legal interpretations, and “approved” decisions. If founders paste AI output into customer materials or treat it as SSOT without verification, Gojen incurs strategic, legal, and reputational damage—especially in billing accuracy (Subscription OS) and regulated lending ops (Pawn Management).

## Triggers

- AI output published without human verification
- Fabricated customer stories or PII-like examples treated as real
- AI invents Document IDs, Approvals, or Statuses

## Consequences

- False market or compliance claims
- Bad architecture or pricing decisions
- Erosion of trust in GAIOS itself

## Mitigation

| Control | Detail |
| --- | --- |
| Collaborator rule | AI is never SSOT ([DEC-GPO-001](../decision-register/dec-gpo-001-github-as-ssot.md)) |
| Citation rule | Material claims must cite repository docs or named external sources |
| Status rule | Only humans set Status = Approved on decisions/risks |
| PII rule | No real customer PII; use anonymized segments |
| Session checklist | End every AI session with verification & docs-to-update list |
| Agent briefs | Scope and restrictions in [Agent Brief Template](../templates/agent-brief-template.md) |

## Residual Risk

Medium–High for unattended agent runs; requires ongoing AI governance review.

## Related Documents

- [GAIOS Governance Charter](../governance/gaios-governance-charter.md)
- [Approval Workflow](../governance/approval-workflow.md)
- [AI Session Template](../templates/ai-session-template.md)
- [Customer Interviews](../research/customer-interviews.md)

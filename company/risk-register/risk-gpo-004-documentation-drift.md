# RISK-GPO-004 — Documentation Drift

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-135 |
| Document Name | RISK-GPO-004 Documentation Drift |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Documentation Engineering / Product Office |
| Reviewer | Founder Board |
| Approver | Founder Board |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Control the risk that GAIOS and product docs become stale relative to real decisions and systems. |
| Scope | Metadata freshness, cross-links, and status accuracy across company GAIOS docs. |

## Navigation

| Link | Target |
| --- | --- |
| Parent | [Risk Register](./README.md) |
| Child | None |
| Related | [RISK-GPO-001](./risk-gpo-001-knowledge-fragmentation.md) · [Compliance Checklist](../governance/compliance-checklist.md) · [Versioning Standard](../standards/versioning.md) |
| Previous | [RISK-GPO-003](./risk-gpo-003-dual-product-focus.md) |
| Next | [GAIOS Templates](../templates/README.md) |
| Back to START-HERE | [START-HERE.md](../START-HERE.md) |

## Risk Record

| Field | Content |
| --- | --- |
| **Risk ID** | RISK-GPO-004 |
| **Category** | Process |
| **Probability** | Medium |
| **Impact** | Medium |
| **Mitigation** | See controls below |
| **Owner** | Documentation Engineering / Product Office |
| **Current Status** | Mitigating |

## Description

As GAIOS grows, documents can retain Approved status while content no longer matches decisions, research findings, or product reality. Drift is especially dangerous when AI assistants confidently quote stale pages.

## Triggers

- Decision Approved but dependent wiki/process pages unchanged
- Review Dates pass without affirmation
- Navigation links broken after folder moves
- Version numbers not bumped on material edits

## Consequences

- AI and humans act on obsolete policy
- Duplicate competing docs
- Trust loss in the repository SSOT

## Mitigation

| Control | Detail |
| --- | --- |
| Review dates | Mandatory on decisions; scan registers monthly |
| Metadata standard | Version, Status, Last Updated on every GAIOS doc |
| Navigation integrity | Parent/Child/Previous/Next/Back to START-HERE |
| Compliance checklist | [compliance-checklist.md](../governance/compliance-checklist.md) |
| Change promotion | Material process changes require PR review |
| Drift audits | Quarterly link and status audit |

## Residual Risk

Low–Medium if audits run; High if audits are skipped for a quarter.

## Related Documents

- [Compliance Checklist](../governance/compliance-checklist.md)
- [Versioning](../standards/versioning.md)
- [Document Numbering](../standards/document-numbering.md)
- [Approval Workflow](../governance/approval-workflow.md)

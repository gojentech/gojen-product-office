# Gowtham – Decision Drafts

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-060 |
| Document Name | Gowtham Decision Drafts |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Gowtham – Co-Founder |
| Reviewer | Gomathi K – Founder & CEO |
| Approver | Founder Board |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Frame Co-Founder technical and delivery decisions before Founder Board ratification. |
| Scope | Pre-decision drafts owned by Gowtham; ratified records move to ADRs, governance, or minutes. |
| Related Documents | [Engineering Dashboard](../../dashboards/engineering-dashboard.md), [Action Items](./action-items.md), [Sample Founder Board Agenda](../../meetings/sample-founder-board-agenda.md) |

## Navigation

| Link | Target |
| --- | --- |
| Parent Document | [Gowtham Workspace](./README.md) |
| Child Documents | None |
| Related Documents | [Gomathi Decision Drafts](../gomathi/decision-drafts.md), [Meeting Notes](./meeting-notes.md) |
| Previous | [Roadmap](./roadmap.md) |
| Next | [Arul Workspace](../arul/README.md) |
| Back to START-HERE | [START-HERE](../../START-HERE.md) |

## Draft DEC-ENG-001 – No Feature Build Until Discovery Exit Criteria

**Status:** Ready for Founder Board 2026-07-22  
**Ask:** Affirm that Subscription OS feature coding waits on published discovery exit criteria and definition-of-ready.

| Option | Pros | Cons |
| --- | --- | --- |
| A – Gate feature build (recommended) | Reduces rework; forces Product Office clarity | Feels slow externally |
| B – Parallel spike freely | Visible activity | High rework risk |
| C – Build UI shell only | Demo candy | Couples UI to unstable domain |

**Recommendation:** Option A, with allowlisted readiness work (ADRs, harnesses, CI) continuing now.

## Draft DEC-ENG-002 – July Engineering Capacity Split

**Status:** Framing with CEO sequencing draft  
**Ask:** Publish July capacity as SOS enablement-heavy with Pawn capped.

| Bucket | Proposed July share |
| --- | --- |
| Infra / reliability | 25% |
| GAIOS / engineering ops | 20% |
| Subscription OS enablement | 45% |
| Pawn Management | 10% |

## Draft Hygiene

1. Technical decisions that affect product scope need CEO co-sign.
2. After ratification, create ADR stubs under product architecture when folders exist.
3. Keep drafts linked from the engineering dashboard pending decisions table.

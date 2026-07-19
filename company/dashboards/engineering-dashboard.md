# Engineering Dashboard

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-083 |
| Document Name | Engineering Dashboard |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Gowtham – Co-Founder |
| Reviewer | Gomathi K – Founder & CEO |
| Approver | Founder Board |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Provide the weekly engineering truth on capacity, readiness, infra health, and blockers. |
| Scope | Engineering operations for GAIOS-backed delivery across Subscription OS and Pawn Management. |
| Related Documents | [Dashboards Index](./README.md), [Gowtham Weekly Log](../founder-workspaces/gowtham/weekly-log.md), [Subscription OS Roadmap](../roadmaps/subscription-os-roadmap.md) |

## Navigation

| Link | Target |
| --- | --- |
| Parent Document | [Dashboards Index](./README.md) |
| Child Documents | None |
| Related Documents | [CPO Dashboard](./cpo-dashboard.md), [Operations Dashboard](./operations-dashboard.md) |
| Previous | [CPO Dashboard](./cpo-dashboard.md) |
| Next | [Sales Dashboard](./sales-dashboard.md) |
| Back to START-HERE | [START-HERE](../START-HERE.md) |

## Current Sprint

| Item | Area | Status | Notes |
| --- | --- | --- | --- |
| Infra health maintenance | Platform | Active | Foundation ready; keep green |
| Engineering dashboard + readiness rules | GAIOS | In progress | Docs-first framing |
| Subscription OS ADR topic outline | Subscription OS | Planned | Tenancy, entitlements, audit |
| Pawn spikes | Pawn Management | Cap 10% | Only if discovery-unblockable |

## KPIs

| KPI | Target | Current | Trend |
| --- | --- | --- | --- |
| P0 infra incidents | 0 / week | 0 | Stable |
| CI baseline | Passing | Passing | Stable |
| July capacity to Pawn | ≤10% | 10% planned | On track |
| Blocked-by-docs items visible | 100% listed | Listed below | Establishing |
| Feature builds without discovery exit | 0 | 0 | Stable |

## Open Risks

| Risk | Likelihood | Impact | Owner | Mitigation |
| --- | --- | --- | --- | --- |
| Premature feature coding | Medium | High | Gowtham | DEC-ENG-001 gate |
| Silent capacity drift to Pawn | Medium | Medium | Gowtham / Arul | Published cap |
| ADR delay blocks later build | Medium | Medium | Gowtham | Outline by 2026-07-24 |

## Blocked Items

| Blocked item | Waiting on | Since | Unblock action |
| --- | --- | --- | --- |
| Subscription OS feature sprint planning | Discovery exit criteria | 2026-07-14 | Product Office publish criteria |
| Entitlements implementation estimate | Domain model draft | 2026-07-15 | Discovery + ADR |
| Pawn schema exploration | Discovery questions register | 2026-07-16 | ACT-OPS-05 |

## Upcoming Milestones

| Milestone | Date | Linked |
| --- | --- | --- |
| Definition-of-ready checklist live | 2026-07-31 | [Gowtham Roadmap](../founder-workspaces/gowtham/roadmap.md) |
| SOS ADR pack draft | 2026-08-15 | [SOS Roadmap](../roadmaps/subscription-os-roadmap.md) |
| Capacity cap review | 2026-08-01 | [DEC-ENG-002](../founder-workspaces/gowtham/decision-drafts.md) |

## Pending Decisions

| Decision | Options summary | Needed by | Draft |
| --- | --- | --- | --- |
| Feature build gate | Gate vs free spikes vs UI-only | 2026-07-22 | [DEC-ENG-001](../founder-workspaces/gowtham/decision-drafts.md) |
| July capacity split | Proposed SOS-heavy mix | 2026-07-22 | [DEC-ENG-002](../founder-workspaces/gowtham/decision-drafts.md) |

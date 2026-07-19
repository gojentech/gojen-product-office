# GAIOS Changelog

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-024 |
| Document Name | GAIOS Changelog |
| Version | 1.2.0 |
| Status | Approved |
| Owner | Gojen Product Office |
| Reviewer | Gomathi K (Founder & CEO) |
| Approver | Founder Board |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-19 |
| Purpose | Record GAIOS version history and material operating-system changes |
| Scope | Changes to GAIOS documents and structure under company/ |
| Related Documents | [CURRENT-SPRINT.md](./CURRENT-SPRINT.md), [START-HERE.md](../START-HERE.md), [GPO-STD-002](../standards/versioning.md) |

## Navigation

| Link | Target |
| --- | --- |
| Parent Document | [README.md](./README.md) |
| Child Documents | None |
| Related Documents | [INDEX.md](../INDEX.md), [DOCUMENT-LIFECYCLE.md](./DOCUMENT-LIFECYCLE.md), [FOUNDER-BOARD-PACK.md](./FOUNDER-BOARD-PACK.md) |
| Previous | [RACI-MATRIX.md](./RACI-MATRIX.md) |
| Next | [repository-standards.md](./repository-standards.md) |
| Back to START-HERE | [START-HERE.md](../START-HERE.md) |

---

## Versioning note

GAIOS follows semantic versioning guidance aligned with [GPO-STD-002](../standards/versioning.md). This changelog tracks the operating system package; individual documents also carry their own Version fields.

---

## [1.2.0] — 2026-07-19

### Changed

- Closed GAIOS Foundation as **Completed**; permanent archive at [SPR-000-GAIOS-Foundation.md](../sprints/SPR-000-GAIOS-Foundation.md)
- [CURRENT-SPRINT.md](./CURRENT-SPRINT.md) now active **SPR-001 SubscriptionOS Discovery Sprint**
- Company and Subscription OS roadmaps: GAIOS Foundation Completed; next milestones Discovery → MVP Definition → Architecture → Development → Pilot

### Added

- [DEC-001-GAIOS-Adoption.md](../decision-register/DEC-001-GAIOS-Adoption.md) Board citation alias for DEC-GPO-002
- [products/subscription-os/backlog/SPR-001.md](../../products/subscription-os/backlog/SPR-001.md)
- [meetings/action-register/FBM-001-Actions.md](../meetings/action-register/FBM-001-Actions.md)
- [learning/retrospectives/SPR-000.md](../learning/retrospectives/SPR-000.md)

---

## [1.1.0] — 2026-07-19

### Changed

- [CURRENT-SPRINT.md](./CURRENT-SPRINT.md) is now a **pointer only** (active sprint identity + links); it no longer holds backlog, review, or retrospective content
- [SPRINT-STANDARDS.md](./SPRINT-STANDARDS.md) updated to the permanent sprint-folder model (v1.1.0)

### Added

- `company/sprints/` hub and permanent sprint folders:
  - [SPR-000](../sprints/SPR-000/README.md) — Closed (GAIOS v1.0 Foundation) with retrospective and metrics
  - [SPR-001](../sprints/SPR-001/README.md) — Active (GAIOS Operationalization) with backlog, review, retrospective

### Why

Historical sprint information must never be overwritten. GitHub remains the audit trail and stronger SSOT when each sprint has its own folder.

---

## [1.0.0] — 2026-07-18

### Added

- Entry points: `company/START-HERE.md` (GOS-GPO-001), `company/INDEX.md` (GOS-GPO-002), `company/SEARCH.md` (GOS-GPO-003)
- AI governance pack: GOS-GPO-010 through GOS-GPO-028 under `company/ai-governance/`
- Memory pack: GOS-GPO-030 through GOS-GPO-036 under `company/memory/`
- Sprint GAIOS-1 declared as foundation sprint in [CURRENT-SPRINT.md](./CURRENT-SPRINT.md) (later migrated to [SPR-000](../sprints/SPR-000/README.md))

### Principles established

- GitHub is SSOT; AI assistants are collaborators
- Additive-only creation for foundation; existing Product Office files referenced, not modified
- Document IDs use `GOS-GPO-NNN`
- Existing standards GPO-STD-001–005 remain authoritative and linked

### Planned (not yet created in this release)

Folder surfaces documented in START-HERE for later sprints: founder-workspaces, dashboards, roadmaps, meetings, research, decision-register, risk-register, templates, prompt-library, playbooks, governance additions, wiki, learning, quality, versions, agents.

---

## How to update this file

On each GAIOS-visible release or sprint close:

1. Add a new version section at the top (below this note)
2. Summarize Added / Changed / Deprecated
3. Link to CURRENT-SPRINT and INDEX updates
4. Bump document Version and Last Updated in the metadata table

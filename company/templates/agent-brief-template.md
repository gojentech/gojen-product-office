# Agent Brief Template

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-144 |
| Document Name | Agent Brief Template |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Office / AI Governance |
| Reviewer | Founder Board |
| Approver | Founder Board |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Brief AI agents with mission, inputs, outputs, KPIs, and hard restrictions before autonomous or semi-autonomous work. |
| Scope | Cursor agents, chat agents, and future registered Gojen AI roles. |

## Navigation

| Link | Target |
| --- | --- |
| Parent | [GAIOS Templates](./README.md) |
| Child | None |
| Related | [AI Session Template](./ai-session-template.md) · [RISK-GPO-002](../risk-register/risk-gpo-002-ai-hallucination-as-source.md) · [Authority Matrix](../governance/authority-matrix.md) |
| Previous | [Decision Draft Template](./decision-draft-template.md) |
| Next | [Dashboard Update Template](./dashboard-update-template.md) |
| Back to START-HERE | [START-HERE.md](../START-HERE.md) |

---

## How to use

Complete this brief before launching a multi-step agent. Attach it to the session or agent registry entry.

---

## Agent Brief

| Field | Value |
| --- | --- |
| Brief ID | `AGB-{YYYYMMDD}-{NN}` |
| Agent / role name | e.g., Documentation Engineer Agent |
| Operator | Human owner |
| Product scope | Subscription OS / Pawn Management / Company / Cross |
| Time box | Duration or end time |
| Autonomy level | Draft-only / Propose+edit new files / (never overwrite without approval) |

### Mission

One paragraph: what success looks like.

### Responsibilities

- …
- …

### Inputs

| Input | Location / description |
| --- | --- |
| START-HERE | `company/START-HERE.md` |
| Context docs | paths |
| Constraints from human | free text |

### Outputs

| Output | Format | Destination |
| --- | --- | --- |
| … | Markdown | path (new files only unless authorized) |

### KPIs for this run

| KPI | Target |
| --- | --- |
| Completeness | All requested files created |
| SSOT compliance | Links and metadata present |
| Verification | Human checklist passed |

### Commands / allowed actions

- Create new markdown files under listed paths
- Read existing repository docs
- Run read-only inspection commands if needed

### Restrictions (hard)

- Do **not** modify, overwrite, or delete existing files unless the operator explicitly lists them.
- Do **not** invent Approved status, customer PII, or legal conclusions.
- Do **not** push to remote or change git config.
- Do **not** treat chat memory as SSOT.
- Respect dual-product boundaries unless brief says cross-cutting.

### Escalation

If blocked, stop and ask the operator. Do not guess Approvals.

### Acceptance criteria

- [ ] Mission outputs delivered
- [ ] Metadata + navigation complete on new docs
- [ ] Promotion list provided for human follow-up
- [ ] No unauthorized file mutations

# DevOps Lead Role Prompt Playbook

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-221 |
| Document Name | DevOps Lead Role Prompt Playbook |
| Version | 1.0.0 |
| Status | Approved |
| Owner | DevOps Lead |
| Reviewer | Engineering Manager |
| Approver | Engineering Manager |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Full role prompt playbook defining how the DevOps Lead operates inside Gojen Technology GAIOS. |
| Scope | Gojen Technology; Subscription OS and Pawn Management. |
| Related Documents | [Incident Postmortem Prompt](../../prompt-library/engineering/incident-postmortem-draft.md), [Engineering Playbook](../engineering.md), [Backend Lead Role](./backend-lead.md) |

## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Roles Index](./README.md)
- [Playbooks](../README.md)

## Mission

Ensure reliable delivery pipelines, secure environments, and operable production systems for Gojen Technology products.

## Responsibilities

- Own CI/CD reliability and environment parity
- Define observability, alerting, and on-call practices
- Manage infrastructure as code and secrets hygiene
- Lead incident response coordination for platform issues
- Drive cost-aware cloud operations with Finance

## Inputs

Deploy requests, SLOs, alerts, infra changes, security findings, cost reports.

## Outputs

Pipeline fixes, runbooks, incident timelines, infra PRs, access reviews, reliability proposals.

## KPIs

Deploy success rate, MTTR, SLO attainment, pipeline duration, secret rotation compliance, infra cost variance.

## Authority

Production change windows within policy; rollback execution; access grant recommendations; block unsafe deploys.

## Communication Style

Operational clarity, blameless incidents, automation bias. Prefer runbooks over heroics.

## Decision Scope

Deploy/rollback calls for platform risk; alert thresholds; environment topology within architecture standards.

## Daily Workflow

Watch CI/CD and prod health; clear deploy blockers; respond to Sev pages.

## Weekly Workflow

On-call review; pipeline flakiness; capacity and cost checkpoint.

## Monthly Workflow

DR exercise notes; access audit; reliability roadmap update; postmortem action aging.

## Example Prompts

### Example 1

```text
Draft a blameless postmortem outline for incident [TITLE] with timeline, 5 Whys, and action items.
```

### Example 2

```text
Propose a CI quality gate set for [PRODUCT] balancing speed and safety.
```

### Example 3

```text
Create a rollback runbook checklist for [SERVICE] including verification steps.
```

## Restrictions

- Do not disable security scanning to unblock deploys without EM+Architect approval
- Do not store secrets in repo or chat logs
- Do not make irreversible prod changes without rollback plan

## Related Documents

[Incident Postmortem Prompt](../../prompt-library/engineering/incident-postmortem-draft.md), [Engineering Playbook](../engineering.md), [Backend Lead Role](./backend-lead.md)
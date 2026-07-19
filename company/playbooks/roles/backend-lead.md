# Backend Lead Role Prompt Playbook

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-218 |
| Document Name | Backend Lead Role Prompt Playbook |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Backend Lead |
| Reviewer | Tech Lead |
| Approver | Engineering Manager |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Full role prompt playbook defining how the Backend Lead operates inside Gojen Technology GAIOS. |
| Scope | Gojen Technology; Subscription OS and Pawn Management. |
| Related Documents | [Solution Architect Role](./solution-architect.md), [API Contract Prompt](../../prompt-library/architecture/api-contract-review.md), [DevOps Lead Role](./devops-lead.md) |

## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Roles Index](./README.md)
- [Playbooks](../README.md)

## Mission

Lead backend correctness, data integrity, and API reliability for Subscription OS and Pawn Management services.

## Responsibilities

- Own service boundaries and data models with Architect
- Ensure API contracts, idempotency, and error models
- Guide migrations and transactional integrity
- Review high-risk backend PRs (auth, billing, ledger, inventory)
- Partner with DevOps on observability

## Inputs

PRDs, API drafts, schemas, SLOs, incident RCAs, load expectations.

## Outputs

API designs, migration plans, review notes, reliability improvements, contract tests guidance.

## KPIs

API error budgets, migration success rate, data-incident count, contract-test coverage on critical APIs.

## Authority

Backend implementation patterns; request-changes on unsafe data changes; propose schema evolution plans.

## Communication Style

Correctness-first, explicit about failure modes. Prefer idempotent designs. Document invariants.

## Decision Scope

Schema evolution approach; transaction boundaries; caching strategy within ADR constraints.

## Daily Workflow

Review critical PRs; validate migration safety; respond to production data questions.

## Weekly Workflow

API contract review; SLO burn review with DevOps; backlog spikes for complexity.

## Monthly Workflow

Data model health; dependency and CVE review for backend stack; capacity notes for peak loads.

## Example Prompts

### Example 1

```text
Design a safe migration plan for [SCHEMA_CHANGE] including rollback and verification queries.
```

### Example 2

```text
Review this API contract for pagination, authz, and idempotency gaps: [CONTRACT].
```

### Example 3

```text
List failure modes for [WORKFLOW] and required compensating actions.
```

## Restrictions

- Do not run irreversible migrations without backup/rollback
- Do not weaken authz for convenience
- Do not log PII/secrets

## Related Documents

[Solution Architect Role](./solution-architect.md), [API Contract Prompt](../../prompt-library/architecture/api-contract-review.md), [DevOps Lead Role](./devops-lead.md)
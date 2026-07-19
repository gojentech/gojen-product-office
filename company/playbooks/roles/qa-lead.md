# QA Lead Role Prompt Playbook

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-220 |
| Document Name | QA Lead Role Prompt Playbook |
| Version | 1.0.0 |
| Status | Approved |
| Owner | QA Lead |
| Reviewer | Engineering Manager |
| Approver | Engineering Manager |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Full role prompt playbook defining how the QA Lead operates inside Gojen Technology GAIOS. |
| Scope | Gojen Technology; Subscription OS and Pawn Management. |
| Related Documents | [Quality Review Agent](../../agents/quality-review-agent.md), [Engineering Playbook](../engineering.md), [Code Review Prompt](../../prompt-library/engineering/code-review-checklist.md) |

## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Roles Index](./README.md)
- [Playbooks](../README.md)

## Mission

Protect customers by ensuring Subscription OS and Pawn Management releases meet quality bars before and after ship.

## Responsibilities

- Define test strategy across unit, integration, e2e, and exploratory
- Own release readiness recommendation
- Track defect trends and escape analysis
- Partner with PO on acceptance clarity
- Improve automation ROI and reduce flaky tests

## Inputs

Stories/AC, risk assessments, builds, environments, production incidents, customer defects.

## Outputs

Test plans, bug reports, release readiness notes, quality metrics, automation priorities.

## KPIs

Escape defect rate, flake rate, regression cycle time, critical bug reopen rate, coverage of critical journeys.

## Authority

Recommend go/no-go for release; block release when Sev1 criteria unmet; define QA entrance/exit criteria.

## Communication Style

Risk-based, factual, calm under pressure. Severity must be evidence-based. Prefer reproducible reports.

## Decision Scope

Test depth per risk; automation vs manual balance; severity classification within policy.

## Daily Workflow

Execute/monitor critical tests; triage new bugs; update release risk.

## Weekly Workflow

Quality report; flake burn-down; upcoming feature risk assessment.

## Monthly Workflow

Escape analysis; tooling evaluation; DoD quality clause proposals.

## Example Prompts

### Example 1

```text
Create a risk-based test plan for [FEATURE] on [PRODUCT] including edge cases and regression focus.
```

### Example 2

```text
Classify and prioritize these defects with customer impact rationale: [BUGS].
```

### Example 3

```text
Produce a release readiness checklist result for build [ID] with go/no-go recommendation.
```

## Restrictions

- Do not approve releases with unresolved Sev1 issues
- Do not mark flaky failures as passing
- Do not test against production with destructive actions

## Related Documents

[Quality Review Agent](../../agents/quality-review-agent.md), [Engineering Playbook](../engineering.md), [Code Review Prompt](../../prompt-library/engineering/code-review-checklist.md)
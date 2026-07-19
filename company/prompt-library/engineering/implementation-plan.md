# Implementation Plan

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-177 |
| Document Name | Implementation Plan Prompt |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Office |
| Reviewer | Chief Product Officer |
| Approver | CEO |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Reusable professional prompt for Gojen Technology teams working on Subscription OS and Pawn Management. |
| Scope | Gojen Technology company-wide; applicable to Subscription OS and Pawn Management. |
| Related Documents | [Engineering Prompts](./README.md), [Engineering Playbook](../../playbooks/engineering.md), [Cursor Engineer Role](../../playbooks/roles/cursor-engineer.md) |

## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Prompt Library](../README.md)

## When to Use

Use before coding a non-trivial change in Subscription OS or Pawn Management to produce a safe, reviewable plan.

## Prompt Body

```text
You are a senior engineer at Gojen Technology planning implementation in Cursor.

Change: [CHANGE]
Product: [Subscription OS | Pawn Management]
Repo areas touched: [PATHS]
Constraints: [PERF / SECURITY / BACKWARD_COMPAT]

Produce an implementation plan:
1. Problem and success criteria
2. Files/modules likely touched
3. Step-by-step approach (smallest safe increments)
4. Test plan (unit, integration, e2e)
5. Rollout / migration / feature flag notes
6. Risks and rollback
7. Definition of done checklist

Do not write full code yet unless asked; focus on the plan.
```

## Expected Output

A stepwise implementation plan with touched areas, tests, rollout, risks, and DoD checklist.

## Restrictions

- Do not modify unrelated files in the plan.
- Do not propose destructive data migrations without backup/rollback steps.
- Do not skip security review for auth, payments, or PII paths.

## Related Documents

[Engineering Prompts](./README.md), [Engineering Playbook](../../playbooks/engineering.md), [Cursor Engineer Role](../../playbooks/roles/cursor-engineer.md)
# Safe Refactor Plan

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-193 |
| Document Name | Safe Refactor Plan Prompt |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Office |
| Reviewer | Chief Product Officer |
| Approver | CEO |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Reusable professional prompt for Gojen Technology teams working on Subscription OS and Pawn Management. |
| Scope | Gojen Technology company-wide; applicable to Subscription OS and Pawn Management. |
| Related Documents | [Cursor Prompts](./README.md), [Tech Lead Role](../../playbooks/roles/tech-lead.md), [Quality Review Agent](../../agents/quality-review-agent.md) |
## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Prompt Library](../README.md)

## When to Use

Use before large refactors in Cursor to keep changes incremental and reviewable.

## Prompt Body

```text
Create a safe refactor plan for Gojen Technology code.

Product: [Subscription OS | Pawn Management]
Refactor goal: [GOAL]
Current pain: [PAIN]
Constraints: [TESTS / DEADLINES / API STABILITY]

Produce:
1. Refactor objective and non-goals
2. Characterization tests to add first
3. Incremental PR slices
4. Compatibility guarantees
5. Rollback strategy
6. Done criteria

Optimize for reviewability and low blast radius.
```

## Expected Output

Incremental refactor plan with characterization tests, PR slices, compatibility, and rollback.

## Restrictions

- Do not mix feature work with refactor in the same slice unless unavoidable and labeled.
- Do not remove public APIs without deprecation plan.
- Do not skip tests for "cleanup only" claims.

## Related Documents

[Cursor Prompts](./README.md), [Tech Lead Role](../../playbooks/roles/tech-lead.md), [Quality Review Agent](../../agents/quality-review-agent.md)
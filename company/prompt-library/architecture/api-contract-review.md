# API Contract Review

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-182 |
| Document Name | API Contract Review Prompt |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Office |
| Reviewer | Chief Product Officer |
| Approver | CEO |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Reusable professional prompt for Gojen Technology teams working on Subscription OS and Pawn Management. |
| Scope | Gojen Technology company-wide; applicable to Subscription OS and Pawn Management. |
| Related Documents | [Architecture Prompts](./README.md), [Backend Lead Role](../../playbooks/roles/backend-lead.md), [Architecture Agent](../../agents/architecture-agent.md) |

## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Prompt Library](../README.md)

## When to Use

Use when reviewing REST/GraphQL/event contracts before implementation freeze for Gojen products.

## Prompt Body

```text
Review the API contract for Gojen Technology.

Product: [Subscription OS | Pawn Management]
Contract draft: [CONTRACT]
Consumers: [CONSUMERS]
Compatibility needs: [BACKWARD_COMPAT]

Evaluate:
1. Resource naming and consistency
2. Error model completeness
3. AuthZ/AuthN assumptions
4. Pagination, filtering, idempotency
5. Versioning strategy
6. Breaking-change risks
7. Required contract tests

Return a pass/fail with blocking issues listed first.
```

## Expected Output

Pass/fail contract review with blocking issues, compatibility risks, and required contract tests.

## Restrictions

- Do not approve breaking changes without a versioning plan.
- Do not ignore authorization gaps.
- Do not invent fields; propose them as optional recommendations labeled clearly.

## Related Documents

[Architecture Prompts](./README.md), [Backend Lead Role](../../playbooks/roles/backend-lead.md), [Architecture Agent](../../agents/architecture-agent.md)
# PRD Outline Generator

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-174 |
| Document Name | PRD Outline Generator Prompt |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Office |
| Reviewer | Chief Product Officer |
| Approver | CEO |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Reusable professional prompt for Gojen Technology teams working on Subscription OS and Pawn Management. |
| Scope | Gojen Technology company-wide; applicable to Subscription OS and Pawn Management. |
| Related Documents | [Product Prompts](./README.md), [Product Playbook](../../playbooks/product.md), [Product Agent](../../agents/product-agent.md), [CPO Role](../../playbooks/roles/chief-product-officer.md) |

## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Prompt Library](../README.md)

## When to Use

Use when starting a Product Requirements Document for a Subscription OS or Pawn Management feature or epic.

## Prompt Body

```text
You are the Chief Product Officer assistant for Gojen Technology.

Create a PRD outline for:
- Product: [Subscription OS | Pawn Management]
- Feature / epic: [NAME]
- Problem statement: [PROBLEM]
- Target users: [USERS]
- Success metrics: [METRICS]
- Constraints: [TECH / COMPLIANCE / TIMELINE]

Produce sections:
1. Overview and problem
2. Goals and non-goals
3. Personas and jobs-to-be-done
4. User journeys
5. Functional requirements (MoSCoW)
6. Non-functional requirements
7. Analytics and instrumentation
8. Rollout and feature flags
9. Open questions
10. Acceptance criteria summary

Align with Gojen documentation standards and cross-link assumptions clearly.
```

## Expected Output

A complete PRD outline with MoSCoW requirements, NFRs, rollout plan, and acceptance criteria summary.

## Restrictions

- Do not invent regulatory requirements; flag compliance review needed.
- Do not prescribe implementation stack unless asked.
- Do not expand scope beyond the stated epic without labeling it as future work.

## Related Documents

[Product Prompts](./README.md), [Product Playbook](../../playbooks/product.md), [Product Agent](../../agents/product-agent.md), [CPO Role](../../playbooks/roles/chief-product-officer.md)
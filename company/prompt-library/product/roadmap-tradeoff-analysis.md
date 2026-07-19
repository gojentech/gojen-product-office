# Roadmap Tradeoff Analysis

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-176 |
| Document Name | Roadmap Tradeoff Analysis Prompt |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Office |
| Reviewer | Chief Product Officer |
| Approver | CEO |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Reusable professional prompt for Gojen Technology teams working on Subscription OS and Pawn Management. |
| Scope | Gojen Technology company-wide; applicable to Subscription OS and Pawn Management. |
| Related Documents | [Product Prompts](./README.md), [Product Playbook](../../playbooks/product.md), [CPO Role](../../playbooks/roles/chief-product-officer.md) |

## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Prompt Library](../README.md)

## When to Use

Use when prioritizing roadmap themes across Subscription OS and Pawn Management under capacity constraints.

## Prompt Body

```text
Perform a roadmap tradeoff analysis for Gojen Technology.

Horizon: [QUARTER]
Capacity: [TEAM_WEEKS]
Themes A/B/C: [THEMES]
Strategic goals: [GOALS]
Customer commitments: [COMMITMENTS]
Technical debt pressure: [DEBT]

Produce:
1. Scoring matrix (reach, impact, confidence, effort, strategic fit, risk reduction)
2. Ranked recommendation
3. What gets deferred and why
4. Dependency and sequencing notes between Subscription OS and Pawn Management
5. Communication summary for engineering and sales

Be explicit about opportunity cost.
```

## Expected Output

A scored tradeoff matrix, ranked recommendation, deferred items with rationale, and cross-product sequencing notes.

## Restrictions

- Do not promise dates without capacity input.
- Do not hide customer commitments; surface conflicts.
- Do not optimize for vanity metrics over strategic goals provided.

## Related Documents

[Product Prompts](./README.md), [Product Playbook](../../playbooks/product.md), [CPO Role](../../playbooks/roles/chief-product-officer.md)
# Code Review Checklist Prompt

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-178 |
| Document Name | Code Review Checklist Prompt |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Office |
| Reviewer | Chief Product Officer |
| Approver | CEO |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Reusable professional prompt for Gojen Technology teams working on Subscription OS and Pawn Management. |
| Scope | Gojen Technology company-wide; applicable to Subscription OS and Pawn Management. |
| Related Documents | [Engineering Prompts](./README.md), [Quality Review Agent](../../agents/quality-review-agent.md), [QA Lead Role](../../playbooks/roles/qa-lead.md) |

## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Prompt Library](../README.md)

## When to Use

Use when reviewing a pull request for Subscription OS or Pawn Management.

## Prompt Body

```text
Review this change for Gojen Technology.

Product: [Subscription OS | Pawn Management]
PR summary: [SUMMARY]
Diff or description: [DIFF]
Risk areas: [AUTH / BILLING / DATA / UX]

Provide:
1. Summary of what the PR does
2. Correctness findings (blocking vs non-blocking)
3. Security and privacy findings
4. Test coverage gaps
5. Maintainability / naming / architecture fit
6. Checklist score against Gojen engineering standards
7. Explicit approve / request-changes recommendation

Be specific; cite locations when possible.
```

## Expected Output

A structured review with severity-ranked findings, standards checklist score, and clear approve or request-changes recommendation.

## Restrictions

- Do not approve if security or data-integrity issues are unresolved.
- Do not demand style-only nits that block delivery without labeling them as non-blocking.
- Do not invent bugs not supported by the provided diff.

## Related Documents

[Engineering Prompts](./README.md), [Quality Review Agent](../../agents/quality-review-agent.md), [QA Lead Role](../../playbooks/roles/qa-lead.md)
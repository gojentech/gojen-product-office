# Test Generation Prompt

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-194 |
| Document Name | Test Generation Prompt |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Office |
| Reviewer | Chief Product Officer |
| Approver | CEO |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Reusable professional prompt for Gojen Technology teams working on Subscription OS and Pawn Management. |
| Scope | Gojen Technology company-wide; applicable to Subscription OS and Pawn Management. |
| Related Documents | [Cursor Prompts](./README.md), [QA Lead Role](../../playbooks/roles/qa-lead.md), [Engineering Playbook](../../playbooks/engineering.md) |
## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Prompt Library](../README.md)

## When to Use

Use when generating focused automated tests for a Gojen Technology change.

## Prompt Body

```text
Generate tests for a Gojen Technology change.

Product: [Subscription OS | Pawn Management]
Code under test: [PATH or SUMMARY]
Risk areas: [RISKS]
Existing test patterns: [PATTERNS]

Deliver:
1. Test plan (unit vs integration)
2. Critical cases including edge and failure paths
3. Proposed test code following repo patterns
4. Gaps that need manual QA
5. Flake risks to avoid

Prefer fewer high-value tests over broad low-signal suites.
```

## Expected Output

Test plan, critical cases, proposed tests matching repo patterns, and manual QA gaps.

## Restrictions

- Do not snapshot overly brittle UI without need.
- Do not hit production systems from tests.
- Do not commit secrets into fixtures.

## Related Documents

[Cursor Prompts](./README.md), [QA Lead Role](../../playbooks/roles/qa-lead.md), [Engineering Playbook](../../playbooks/engineering.md)
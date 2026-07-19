# Repo Onboarding Brief

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-192 |
| Document Name | Repo Onboarding Brief Prompt |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Office |
| Reviewer | Chief Product Officer |
| Approver | CEO |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Reusable professional prompt for Gojen Technology teams working on Subscription OS and Pawn Management. |
| Scope | Gojen Technology company-wide; applicable to Subscription OS and Pawn Management. |
| Related Documents | [Cursor Prompts](./README.md), [Cursor Engineer Role](../../playbooks/roles/cursor-engineer.md), [Engineering Playbook](../../playbooks/engineering.md) |
## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Prompt Library](../README.md)

## When to Use

Use when onboarding an engineer or Cursor agent to a Gojen Technology repository area.

## Prompt Body

```text
Produce a repo onboarding brief for Gojen Technology.

Product area: [Subscription OS | Pawn Management | Company docs]
Paths to focus: [PATHS]
Task to accomplish: [TASK]

Deliver:
1. How this area fits the product
2. Key entry files and why they matter
3. Local run / test commands if discoverable
4. Coding conventions observed
5. Safe first contribution plan
6. Risks of naive edits

Prefer reading existing docs and code over guessing.
```

## Expected Output

Onboarding brief with entry files, conventions, safe first contribution plan, and edit risks.

## Restrictions

- Do not modify files while producing the brief unless asked.
- Do not invent scripts that are not in the repo.
- Do not bypass repository rules or secrets handling.

## Related Documents

[Cursor Prompts](./README.md), [Cursor Engineer Role](../../playbooks/roles/cursor-engineer.md), [Engineering Playbook](../../playbooks/engineering.md)
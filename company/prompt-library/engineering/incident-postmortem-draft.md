# Incident Postmortem Draft

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-179 |
| Document Name | Incident Postmortem Draft Prompt |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Office |
| Reviewer | Chief Product Officer |
| Approver | CEO |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Reusable professional prompt for Gojen Technology teams working on Subscription OS and Pawn Management. |
| Scope | Gojen Technology company-wide; applicable to Subscription OS and Pawn Management. |
| Related Documents | [Engineering Prompts](./README.md), [Engineering Playbook](../../playbooks/engineering.md), [DevOps Lead Role](../../playbooks/roles/devops-lead.md) |

## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Prompt Library](../README.md)

## When to Use

Use after a production incident affecting Subscription OS or Pawn Management to draft a blameless postmortem.

## Prompt Body

```text
Draft a blameless postmortem for Gojen Technology.

Incident: [TITLE]
Product: [Subscription OS | Pawn Management]
Severity: [SEV]
Timeline: [TIMELINE]
Impact: [CUSTOMERS / REVENUE / DATA]
Detection: [HOW]
Mitigation: [WHAT_WE_DID]
Current hypothesis: [CAUSE]

Sections:
1. Summary
2. Impact
3. Timeline
4. Root cause analysis (5 Whys)
5. What went well / poorly
6. Action items (owner, due date, preventive vs detective)
7. Follow-up communications

Keep tone blameless and systems-focused.
```

## Expected Output

A blameless postmortem with timeline, 5 Whys RCA, and owned action items.

## Restrictions

- Do not assign personal blame.
- Do not omit customer impact.
- Do not close the incident narrative without at least one preventive action item.

## Related Documents

[Engineering Prompts](./README.md), [Engineering Playbook](../../playbooks/engineering.md), [DevOps Lead Role](../../playbooks/roles/devops-lead.md)
# ADR Draft

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-180 |
| Document Name | ADR Draft Prompt |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Office |
| Reviewer | Chief Product Officer |
| Approver | CEO |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Reusable professional prompt for Gojen Technology teams working on Subscription OS and Pawn Management. |
| Scope | Gojen Technology company-wide; applicable to Subscription OS and Pawn Management. |
| Related Documents | [Architecture Prompts](./README.md), [Architecture Agent](../../agents/architecture-agent.md), [Solution Architect Role](../../playbooks/roles/solution-architect.md) |

## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Prompt Library](../README.md)

## When to Use

Use when recording an Architecture Decision Record for Subscription OS or Pawn Management.

## Prompt Body

```text
Draft an Architecture Decision Record (ADR) for Gojen Technology.

Product: [Subscription OS | Pawn Management]
Decision title: [TITLE]
Context: [CONTEXT]
Drivers: [DRIVERS]
Options: [OPTIONS]
Preferred option: [OPTION]

Use structure:
- Status
- Context
- Decision
- Consequences (positive / negative)
- Alternatives considered
- Compliance / security notes
- Related ADRs and documents

Be precise and decision-oriented.
```

## Expected Output

A complete ADR with status, context, decision, consequences, alternatives, and security notes.

## Restrictions

- Do not mark Status as Accepted unless a human approver is named in context.
- Do not ignore negative consequences.
- Do not introduce new vendor lock-in without calling it out.

## Related Documents

[Architecture Prompts](./README.md), [Architecture Agent](../../agents/architecture-agent.md), [Solution Architect Role](../../playbooks/roles/solution-architect.md)
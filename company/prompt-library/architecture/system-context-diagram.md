# System Context Diagram Prompt

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-181 |
| Document Name | System Context Diagram Prompt |
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

Use when explaining or documenting how a Gojen product interacts with users and external systems.

## Prompt Body

```text
Produce a C4 System Context description for Gojen Technology.

Product: [Subscription OS | Pawn Management]
Actors: [ACTORS]
External systems: [SYSTEMS]
Trust boundaries: [BOUNDARIES]

Deliver:
1. Narrative system context
2. Mermaid C4-style context diagram
3. List of relationships (who talks to whom, protocol, data class)
4. Open interface questions

Prefer clarity over completeness.
```

## Expected Output

Narrative context, Mermaid diagram, relationship list with data classes, and open interface questions.

## Restrictions

- Do not invent external vendors not listed in inputs.
- Do not expose secrets or credential locations.
- Do not skip trust boundaries for PII or payment flows.

## Related Documents

[Architecture Prompts](./README.md), [Architecture Agent](../../agents/architecture-agent.md), [Solution Architect Role](../../playbooks/roles/solution-architect.md)
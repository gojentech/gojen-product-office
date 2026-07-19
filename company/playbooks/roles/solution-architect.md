# Solution Architect Role Prompt Playbook

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-214 |
| Document Name | Solution Architect Role Prompt Playbook |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Solution Architect |
| Reviewer | Engineering Manager |
| Approver | CEO |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Full role prompt playbook defining how the Solution Architect operates inside Gojen Technology GAIOS. |
| Scope | Gojen Technology; Subscription OS and Pawn Management. |
| Related Documents | [Architecture Agent](../../agents/architecture-agent.md), [Architecture Prompts](../../prompt-library/architecture/README.md), [Tech Lead Role](./tech-lead.md) |

## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Roles Index](./README.md)
- [Playbooks](../README.md)

## Mission

Design coherent, secure, evolvable architectures for Subscription OS and Pawn Management that meet product and operational constraints.

## Responsibilities

- Produce architecture overviews and ADRs
- Guide API and integration contracts
- Evaluate build vs buy and major tech choices
- Partner with Security/DevOps on NFRs
- Review high-risk designs before build

## Inputs

PRDs, NFRs, constraints, existing system maps, incident lessons, vendor options.

## Outputs

ADRs, C4 views, API guidelines, risk assessments, architecture review notes.

## KPIs

ADR coverage for major decisions, design-review lead time, severity of architecture-related incidents, NFR acceptance rate.

## Authority

Technical recommendation authority; ADR drafting; block merge of architecture-breaking changes pending review.

## Communication Style

Systems thinking, tradeoff-explicit, diagram-friendly. Name consequences of decisions.

## Decision Scope

Recommended architecture options; interface boundaries; technology shortlists within company standards.

## Daily Workflow

Unblock design questions; review critical PRs for architectural fit; update living diagrams when reality changes.

## Weekly Workflow

ADR progress; API contract reviews; tech debt vs feature tradeoff input.

## Monthly Workflow

Architecture health check; dependency risk review; standards proposal updates.

## Example Prompts

### Example 1

```text
Draft an ADR for [DECISION] on [PRODUCT] with options, consequences, and security notes.
```

### Example 2

```text
Produce a C4 system context for [PRODUCT] with actors, externals, and trust boundaries.
```

### Example 3

```text
Review this API contract for breaking changes and auth gaps: [CONTRACT].
```

## Restrictions

- Do not mark ADRs Accepted without named human approver
- Do not introduce unmanaged vendor lock-in
- Do not ignore security/privacy for speed

## Related Documents

[Architecture Agent](../../agents/architecture-agent.md), [Architecture Prompts](../../prompt-library/architecture/README.md), [Tech Lead Role](./tech-lead.md)
# Product Owner Role Prompt Playbook

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-212 |
| Document Name | Product Owner Role Prompt Playbook |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Owner |
| Reviewer | Chief Product Officer |
| Approver | Chief Product Officer |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Full role prompt playbook defining how the Product Owner operates inside Gojen Technology GAIOS. |
| Scope | Gojen Technology; Subscription OS and Pawn Management. |
| Related Documents | [CPO Role](./chief-product-officer.md), [Sprint Coach Agent](../../agents/sprint-coach-agent.md), [User Story Prompt](../../prompt-library/product/user-story-refinement.md) |

## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Roles Index](./README.md)
- [Playbooks](../README.md)

## Mission

Translate product strategy into a clear, valuable, sprint-ready backlog for a Gojen Technology product squad.

## Responsibilities

- Own team backlog order and clarity
- Write and refine user stories with acceptance criteria
- Accept or reject sprint increments against DoD
- Represent customer value in ceremonies
- Manage scope within sprint commitments

## Inputs

PRDs, designs, tech constraints, sprint velocity, bug reports, stakeholder requests.

## Outputs

Ordered backlog, refined stories, acceptance decisions, sprint goals, clarification notes.

## KPIs

Sprint goal success rate, story readiness %, escaped defects from unclear AC, stakeholder response time.

## Authority

Backlog order for the squad; acceptance of stories; sprint scope negotiation with Tech Lead within CPO themes.

## Communication Style

Concrete, collaborative, AC-driven. Prefer Given/When/Then. Escalate ambiguity early.

## Decision Scope

Story splits; acceptance; minor scope swaps inside sprint; clarification of intent within PRD boundaries.

## Daily Workflow

Clarify blockers; accept ready work; keep board accurate; answer engineering questions same day.

## Weekly Workflow

Refinement; sprint planning/review/retro participation; dependency check with other teams.

## Monthly Workflow

Backlog health audit; outcome contribution review with CPO; DoD improvements with QA.

## Example Prompts

### Example 1

```text
Refine this draft story for [PRODUCT] into INVEST format with Gherkin acceptance criteria and edge cases: [DRAFT].
```

### Example 2

```text
Propose a sprint goal for the next sprint given this backlog slice and capacity: [DATA].
```

### Example 3

```text
Decide accept/reject for this increment against AC and DoD; list gaps: [SUMMARY].
```

## Restrictions

- Do not unilaterally change portfolio priorities set by CPO
- Do not accept work missing tests required by DoD
- Do not add mid-sprint scope without Tech Lead agreement and risk note

## Related Documents

[CPO Role](./chief-product-officer.md), [Sprint Coach Agent](../../agents/sprint-coach-agent.md), [User Story Prompt](../../prompt-library/product/user-story-refinement.md)
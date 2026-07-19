# Business Analyst Role Prompt Playbook

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-213 |
| Document Name | Business Analyst Role Prompt Playbook |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Business Analyst |
| Reviewer | Chief Product Officer |
| Approver | Chief Product Officer |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Full role prompt playbook defining how the Business Analyst operates inside Gojen Technology GAIOS. |
| Scope | Gojen Technology; Subscription OS and Pawn Management. |
| Related Documents | [Product Prompts](../../prompt-library/product/README.md), [Research Agent](../../agents/research-agent.md), [Product Owner Role](./product-owner.md) |

## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Roles Index](./README.md)
- [Playbooks](../README.md)

## Mission

Elicit, analyze, and document business requirements so Subscription OS and Pawn Management solutions solve the right problems.

## Responsibilities

- Facilitate discovery workshops and interviews
- Produce BRDs, process maps, and requirement traces
- Analyze gaps between current and future state
- Support UAT scenario design with QA
- Keep requirements traceable to outcomes

## Inputs

Stakeholder interviews, existing SOPs, product goals, constraints, data samples, competitor notes.

## Outputs

BRDs, process flows, requirement matrices, assumption logs, UAT scenario drafts.

## KPIs

Requirement defect rate, traceability completeness, stakeholder sign-off cycle time, rework caused by ambiguous requirements.

## Authority

Requirement documentation quality bar; facilitation of elicitation; recommendation of scope options (not final prioritization).

## Communication Style

Precise, structured, neutral. Distinguish must/should/could. Surface conflicts explicitly.

## Decision Scope

How to model a process; which questions to ask; when requirements are ready for PO/CPO review.

## Daily Workflow

Capture clarifications; update requirement docs; resolve ambiguities with owners.

## Weekly Workflow

Workshop or interview synthesis; traceability update; sync with PO and Architect.

## Monthly Workflow

Requirements portfolio audit; process map refresh for changed domains; lesson learned from UAT defects.

## Example Prompts

### Example 1

```text
Create a current-vs-future process map for [WORKFLOW] in [PRODUCT] and list requirement gaps.
```

### Example 2

```text
Draft a BRD section for [EPIC] with MoSCoW business rules and open questions.
```

### Example 3

```text
Turn these interview notes into a requirements assumption log with confidence ratings: [NOTES].
```

## Restrictions

- Do not invent business rules without labeling assumptions
- Do not prioritize the roadmap (CPO/PO ownership)
- Do not expose confidential customer data in examples

## Related Documents

[Product Prompts](../../prompt-library/product/README.md), [Research Agent](../../agents/research-agent.md), [Product Owner Role](./product-owner.md)
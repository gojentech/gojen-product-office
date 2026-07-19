# Cursor Engineer Role Prompt Playbook

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-228 |
| Document Name | Cursor Engineer Role Prompt Playbook |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Cursor Engineer |
| Reviewer | Tech Lead |
| Approver | Engineering Manager |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Full role prompt playbook defining how the Cursor Engineer operates inside Gojen Technology GAIOS. |
| Scope | Gojen Technology; Subscription OS and Pawn Management. |
| Related Documents | [Cursor Prompts](../../prompt-library/cursor/README.md), [Tech Lead Role](./tech-lead.md), [Engineering Playbook](../engineering.md) |

## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Roles Index](./README.md)
- [Playbooks](../README.md)

## Mission

Use Cursor and GAIOS prompts to implement high-quality code and documentation changes safely for Gojen Technology products.

## Responsibilities

- Execute implementation plans in small reviewable increments
- Follow repository rules and product coding standards
- Generate tests alongside changes
- Keep AI-assisted work within Restrictions of assigned prompts/agents
- Document what changed and how to verify

## Inputs

Tickets/stories, ADRs, repo context, failing tests, Cursor prompts, review feedback.

## Outputs

PRs, tests, implementation notes, risk callouts, verification steps.

## KPIs

PR acceptance rate, rework rate, test pass rate, mean time to first reviewable PR, incident rate from AI-assisted changes.

## Authority

Local code changes within assigned task; propose refactors; must not merge without required reviews.

## Communication Style

Plan-first, minimal diff, explicit verification. Ask when ambiguous. Prefer readable code over cleverness.

## Decision Scope

Local implementation details within story/ADR; test selection; when to stop and escalate ambiguity.

## Daily Workflow

Pull context; implement slice; run tests; open/update PR; respond to review.

## Weekly Workflow

Reduce recurring friction with better prompts/checklists; share learnings with Tech Lead.

## Monthly Workflow

Tooling/prompt improvements; personal defect pattern review; contribute to Cursor prompt library.

## Example Prompts

### Example 1

```text
Produce a repo onboarding brief for paths [PATHS] and task [TASK] without modifying files.
```

### Example 2

```text
Create a safe refactor plan for [GOAL] with characterization tests and PR slices.
```

### Example 3

```text
Generate high-value tests for [CHANGE] following existing repo patterns; list manual QA gaps.
```

## Restrictions

- Do not modify/overwrite/delete unrelated existing files
- Do not commit secrets or disable security controls
- Do not expand scope beyond the assigned task
- Do not push force or skip hooks

## Related Documents

[Cursor Prompts](../../prompt-library/cursor/README.md), [Tech Lead Role](./tech-lead.md), [Engineering Playbook](../engineering.md)
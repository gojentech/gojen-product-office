# Tech Lead Role Prompt Playbook

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-216 |
| Document Name | Tech Lead Role Prompt Playbook |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Tech Lead |
| Reviewer | Engineering Manager |
| Approver | Engineering Manager |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Full role prompt playbook defining how the Tech Lead operates inside Gojen Technology GAIOS. |
| Scope | Gojen Technology; Subscription OS and Pawn Management. |
| Related Documents | [Cursor Engineer Role](./cursor-engineer.md), [Engineering Prompts](../../prompt-library/engineering/README.md), [Quality Review Agent](../../agents/quality-review-agent.md) |

## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Roles Index](./README.md)
- [Playbooks](../README.md)

## Mission

Provide hands-on technical leadership so the squad ships correct, maintainable software aligned with Gojen architecture standards.

## Responsibilities

- Guide implementation design within ADR boundaries
- Review critical PRs and coach engineers
- Decompose work into safe increments
- Own technical spike quality
- Keep Definition of Done practical and enforced

## Inputs

Stories, designs, ADRs, CI results, production signals, team skill matrix.

## Outputs

Technical plans, PR reviews, spike reports, refactor proposals, risk notes.

## KPIs

PR review latency, reopen rate, spike-to-decision time, production escapes attributable to design gaps.

## Authority

Technical approach within story; request changes on PRs; propose ADRs; temporary hotfix authority with DevOps.

## Communication Style

Pragmatic, teaching-oriented, precise. Prefer small PRs. Explain why, not only what.

## Decision Scope

Implementation approach for stories; merge readiness; spike conclusions; tech debt sequencing inside sprint.

## Daily Workflow

Review PRs; unblock implementation; adjust plan when unknowns appear.

## Weekly Workflow

Tech plan for next sprint; debt triage; architecture sync.

## Monthly Workflow

Module health review; mentoring plan; propose standards improvements.

## Example Prompts

### Example 1

```text
Create a safe implementation plan for [CHANGE] on [PRODUCT] including tests, rollout, and rollback.
```

### Example 2

```text
Review this PR summary for correctness, security, and maintainability; recommend approve or request-changes: [SUMMARY].
```

### Example 3

```text
Propose incremental refactor slices for [AREA] with characterization tests first.
```

## Restrictions

- Do not merge without required reviews/tests
- Do not expand scope silently
- Do not bypass security checks for auth/billing/PII paths

## Related Documents

[Cursor Engineer Role](./cursor-engineer.md), [Engineering Prompts](../../prompt-library/engineering/README.md), [Quality Review Agent](../../agents/quality-review-agent.md)
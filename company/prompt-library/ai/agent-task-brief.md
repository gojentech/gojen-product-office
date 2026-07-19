# Agent Task Brief

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-195 |
| Document Name | Agent Task Brief Prompt |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Office |
| Reviewer | Chief Product Officer |
| Approver | CEO |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Reusable professional prompt for Gojen Technology teams working on Subscription OS and Pawn Management. |
| Scope | Gojen Technology company-wide; applicable to Subscription OS and Pawn Management. |
| Related Documents | [AI Prompts](./README.md), [AI Agent Registry](../../agents/README.md), [Sprint Coach Agent](../../agents/sprint-coach-agent.md) |
## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Prompt Library](../README.md)

## When to Use

Use when assigning work to a GAIOS AI agent so the task is scoped, measurable, and safe.

## Prompt Body

```text
Create an agent task brief for Gojen Technology GAIOS.

Agent: [AGENT_NAME]
Goal: [GOAL]
Product context: [Subscription OS | Pawn Management | Company]
Inputs provided: [INPUTS]
Definition of done: [DOD]
Time box: [TIMEBOX]

Produce:
1. Mission statement for this run
2. Allowed actions
3. Forbidden actions
4. Output artifacts and destinations
5. Escalation triggers
6. Acceptance checks

Align with registered agent restrictions.
```

## Expected Output

Scoped agent task brief with allowed/forbidden actions, artifacts, escalations, and acceptance checks.

## Restrictions

- Do not authorize destructive git or production actions.
- Do not allow editing existing approved docs unless explicitly in scope.
- Do not omit escalation triggers for ambiguity.

## Related Documents

[AI Prompts](./README.md), [AI Agent Registry](../../agents/README.md), [Sprint Coach Agent](../../agents/sprint-coach-agent.md)
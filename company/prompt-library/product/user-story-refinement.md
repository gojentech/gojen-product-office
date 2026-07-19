# User Story Refinement

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-175 |
| Document Name | User Story Refinement Prompt |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Office |
| Reviewer | Chief Product Officer |
| Approver | CEO |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Reusable professional prompt for Gojen Technology teams working on Subscription OS and Pawn Management. |
| Scope | Gojen Technology company-wide; applicable to Subscription OS and Pawn Management. |
| Related Documents | [Product Prompts](./README.md), [Product Owner Role](../../playbooks/roles/product-owner.md), [Sprint Coach Agent](../../agents/sprint-coach-agent.md) |

## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Prompt Library](../README.md)

## When to Use

Use in backlog refinement to turn rough ideas into INVEST-quality user stories for Subscription OS or Pawn Management.

## Prompt Body

```text
Refine the following backlog item for Gojen Technology.

Product: [Subscription OS | Pawn Management]
Draft story: [DRAFT]
Persona: [PERSONA]
Dependencies: [DEPS]
Definition of Done baseline: [DOD]

Output for each story:
1. Title
2. User story (As aâ€¦ I wantâ€¦ So thatâ€¦)
3. Acceptance criteria (Given/When/Then)
4. Edge cases
5. Analytics events
6. Estimate confidence (H/M/L) and unknowns
7. Split recommendations if the story is too large

Ensure stories are Independent, Negotiable, Valuable, Estimable, Small, Testable.
```

## Expected Output

One or more INVEST-quality stories with Gherkin-style acceptance criteria, edge cases, and analytics events.

## Restrictions

- Do not invent API contracts; list interface questions instead.
- Do not assign story points unless a team baseline is provided.
- Do not merge unrelated personas into one story.

## Related Documents

[Product Prompts](./README.md), [Product Owner Role](../../playbooks/roles/product-owner.md), [Sprint Coach Agent](../../agents/sprint-coach-agent.md)
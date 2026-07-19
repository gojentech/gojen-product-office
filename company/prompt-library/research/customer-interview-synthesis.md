# Customer Interview Synthesis

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-184 |
| Document Name | Customer Interview Synthesis Prompt |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Office |
| Reviewer | Chief Product Officer |
| Approver | CEO |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Reusable professional prompt for Gojen Technology teams working on Subscription OS and Pawn Management. |
| Scope | Gojen Technology company-wide; applicable to Subscription OS and Pawn Management. |
| Related Documents | [Research Prompts](./README.md), [Product Agent](../../agents/product-agent.md), [Business Analyst Role](../../playbooks/roles/business-analyst.md) |
## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Prompt Library](../README.md)

## When to Use

Use after customer or prospect interviews to synthesize insights for product and GTM.

## Prompt Body

```text
Synthesize customer interviews for Gojen Technology.

Product: [Subscription OS | Pawn Management]
Interview notes: [NOTES]
Interview goals: [GOALS]

Produce:
1. Participant summary (anonymized)
2. Jobs-to-be-done themes
3. Pain severity ranking
4. Verbatim quotes (high-signal only)
5. Opportunity hypotheses mapped to product areas
6. Contradictions and open questions
7. Recommended next research steps

Separate observation from interpretation.
```

## Expected Output

Themed synthesis with JTBD, pain ranking, quotes, opportunity hypotheses, and next research steps.

## Restrictions

- Do not reveal personal identifiable information beyond what was provided for anonymization.
- Do not over-generalize from n=1 without labeling confidence.
- Do not convert research into committed roadmap items.

## Related Documents

[Research Prompts](./README.md), [Product Agent](../../agents/product-agent.md), [Business Analyst Role](../../playbooks/roles/business-analyst.md)
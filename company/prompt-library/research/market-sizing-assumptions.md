# Market Sizing Assumptions

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-185 |
| Document Name | Market Sizing Assumptions Prompt |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Office |
| Reviewer | Chief Product Officer |
| Approver | CEO |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Reusable professional prompt for Gojen Technology teams working on Subscription OS and Pawn Management. |
| Scope | Gojen Technology company-wide; applicable to Subscription OS and Pawn Management. |
| Related Documents | [Research Prompts](./README.md), [Research Agent](../../agents/research-agent.md), [Sales Director Role](../../playbooks/roles/sales-director.md) |
## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Prompt Library](../README.md)

## When to Use

Use when estimating TAM/SAM/SOM for Subscription OS or Pawn Management with transparent assumptions.

## Prompt Body

```text
Build a transparent market sizing model for Gojen Technology.

Product: [Subscription OS | Pawn Management]
Geography: [GEO]
Customer definition: [ICP]
Pricing hypothesis: [ARPU]
Sources available: [SOURCES]

Produce:
1. TAM / SAM / SOM definitions for this product
2. Bottom-up calculation with formulas
3. Top-down cross-check
4. Assumption register (each assumption: value, confidence, source)
5. Sensitivity analysis (best / base / worst)
6. Implications for GTM focus

Show math; do not hide steps.
```

## Expected Output

TAM/SAM/SOM with formulas, assumption register, sensitivity cases, and GTM implications.

## Restrictions

- Do not present estimates as facts.
- Do not omit low-confidence assumptions.
- Do not use circular reasoning (revenue goal defining market size).

## Related Documents

[Research Prompts](./README.md), [Research Agent](../../agents/research-agent.md), [Sales Director Role](../../playbooks/roles/sales-director.md)
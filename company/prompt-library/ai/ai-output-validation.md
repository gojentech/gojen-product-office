# AI Output Validation

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-197 |
| Document Name | AI Output Validation Prompt |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Product Office |
| Reviewer | Chief Product Officer |
| Approver | CEO |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Reusable professional prompt for Gojen Technology teams working on Subscription OS and Pawn Management. |
| Scope | Gojen Technology company-wide; applicable to Subscription OS and Pawn Management. |
| Related Documents | [AI Prompts](./README.md), [Quality Review Agent](../../agents/quality-review-agent.md), [Documentation Agent](../../agents/documentation-agent.md) |
## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Prompt Library](../README.md)

## When to Use

Use when validating AI-generated documents, code plans, or analyses before they enter Gojen official records.

## Prompt Body

```text
Validate AI output for Gojen Technology before promotion to Approved status.

Artifact type: [DOC / PLAN / ANALYSIS / CODE]
Artifact: [CONTENT]
Source prompt / agent: [SOURCE]
Claims requiring evidence: [CLAIMS]

Check:
1. Factual consistency with provided inputs
2. Hallucination risks
3. Scope creep
4. Missing restrictions handling
5. Cross-link and metadata completeness
6. Ready for human approval? (Yes/No with reasons)

Produce a validation report with required fixes.
```

## Expected Output

Validation report covering hallucinations, scope, metadata, and ready-for-approval judgment.

## Restrictions

- Do not auto-approve; human Approver remains required.
- Do not silently rewrite the artifact; list required fixes.
- Do not ignore conflicts with existing Approved documents.

## Related Documents

[AI Prompts](./README.md), [Quality Review Agent](../../agents/quality-review-agent.md), [Documentation Agent](../../agents/documentation-agent.md)
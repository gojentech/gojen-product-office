# Documentation Engineer Role Prompt Playbook

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-227 |
| Document Name | Documentation Engineer Role Prompt Playbook |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Documentation Engineer |
| Reviewer | Product Office |
| Approver | Chief Product Officer |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Full role prompt playbook defining how the Documentation Engineer operates inside Gojen Technology GAIOS. |
| Scope | Gojen Technology; Subscription OS and Pawn Management. |
| Related Documents | [Documentation Agent](../../agents/documentation-agent.md), [Prompt Library](../../prompt-library/README.md), [Quality Review Agent](../../agents/quality-review-agent.md) |

## Navigation

- [Back to START-HERE.md](../../START-HERE.md)
- [Roles Index](./README.md)
- [Playbooks](../README.md)

## Mission

Make Gojen Technology knowledge durable, searchable, and standards-compliant across company and product documentation.

## Responsibilities

- Enforce document metadata, numbering, and cross-linking standards
- Author and refactor technical and operational docs
- Partner with agents to keep docs synchronized with reality
- Improve navigation (START-HERE, indexes, READMEs)
- Review docs for clarity, completeness, and drift

## Inputs

ADRs, PRDs, release notes, standards, meeting minutes, engineering changes.

## Outputs

Approved docs, indexes, migration maps, doc quality reviews, templates.

## KPIs

Doc freshness, broken-link rate, standards compliance %, time-to-find rated by teams, orphan doc count.

## Authority

Documentation structure proposals; block publish of docs missing required metadata; recommend doc ownership.

## Communication Style

Clear, structured, link-rich. Prefer short sentences and explicit owners. No placeholder prose.

## Decision Scope

Information architecture for docs; when to split/merge docs; taxonomy updates with Product Office.

## Daily Workflow

Fix critical doc gaps; validate metadata on new docs; respond to doc requests.

## Weekly Workflow

Link checker; drift review vs releases; index updates.

## Monthly Workflow

Standards compliance audit; template improvements; archive obsolete docs via process.

## Example Prompts

### Example 1

```text
Review this document for GAIOS metadata completeness and cross-link quality; list required fixes: [DOC].
```

### Example 2

```text
Create a navigation map from START-HERE to [TOPIC] for Subscription OS and Pawn Management.
```

### Example 3

```text
Convert these meeting decisions into durable documentation updates with owners: [NOTES].
```

## Restrictions

- Do not overwrite existing Approved files without change control
- Do not invent Document IDs outside numbering standards
- Do not leave TODO/placeholder content in Approved docs

## Related Documents

[Documentation Agent](../../agents/documentation-agent.md), [Prompt Library](../../prompt-library/README.md), [Quality Review Agent](../../agents/quality-review-agent.md)
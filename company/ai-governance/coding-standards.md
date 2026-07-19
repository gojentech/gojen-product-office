# Coding Standards (GAIOS)

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-027 |
| Document Name | Coding Standards |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Gojen Product Office |
| Reviewer | Gomathi K (Founder & CEO) |
| Approver | Founder Board |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Engineering conduct for AI-assisted coding work that touches this repository |
| Scope | Code and automation changes performed with AI collaboration in gojen-product-office |
| Related Documents | [repository-standards.md](./repository-standards.md), [AI-RULES.md](./AI-RULES.md), [architecture-standards.md](./architecture-standards.md) |

## Navigation

| Link | Target |
| --- | --- |
| Parent Document | [README.md](./README.md) |
| Child Documents | None |
| Related Documents | [documentation-standards.md](./documentation-standards.md), [technology-context.md](../memory/technology-context.md), [GPO-STD-005](../standards/repository-rules.md) |
| Previous | [architecture-standards.md](./architecture-standards.md) |
| Next | [documentation-standards.md](./documentation-standards.md) |
| Back to START-HERE | [START-HERE.md](../START-HERE.md) |

---

## Posture

`gojen-product-office` is primarily a Product Office documentation and governance repository. Coding work that appears here (scripts, CI, light tooling) must still obey GAIOS collaboration rules.

Product application codebases may live elsewhere; when they are referenced, treat product architecture and engineering folders as SSOT for technical design.

---

## AI coding rules

1. Match existing project conventions before introducing new patterns.
2. Prefer minimal diffs that solve the stated problem.
3. Do not add dependencies without human approval.
4. Do not commit secrets; use environment configuration patterns approved by humans.
5. Do not write exploit payloads or attack tooling.
6. Tests should validate behavior; avoid destructive operations against shared systems.
7. Document non-obvious decisions via ADRs or decision records when material.

---

## Documentation coupling

When code behavior changes operating practice:

- Update the relevant GAIOS or product document in the same change set when authorized
- Link code paths from docs with relative links where practical
- Note GAIOS-visible process changes in [CHANGELOG.md](./CHANGELOG.md)

---

## Review expectation

Human review is required before merging code that affects CI, repository structure, or automation that AI assistants will rely on. RACI: [RACI-MATRIX.md](./RACI-MATRIX.md).

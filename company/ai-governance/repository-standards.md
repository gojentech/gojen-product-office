# Repository Standards (GAIOS)

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-025 |
| Document Name | Repository Standards |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Gojen Product Office |
| Reviewer | Gomathi K (Founder & CEO) |
| Approver | Founder Board |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | GAIOS extension of repository practice for AI-assisted collaboration |
| Scope | How AI and humans create and organize files in gojen-product-office |
| Related Documents | [GPO-STD-005](../standards/repository-rules.md), [AI-RULES.md](./AI-RULES.md), [documentation-standards.md](./documentation-standards.md) |

## Navigation

| Link | Target |
| --- | --- |
| Parent Document | [README.md](./README.md) |
| Child Documents | None |
| Related Documents | [architecture-standards.md](./architecture-standards.md), [coding-standards.md](./coding-standards.md), [START-HERE.md](../START-HERE.md) |
| Previous | [CHANGELOG.md](./CHANGELOG.md) |
| Next | [architecture-standards.md](./architecture-standards.md) |
| Back to START-HERE | [START-HERE.md](../START-HERE.md) |

---

## Relationship to GPO-STD-005

[GPO-STD-005 Repository Rules](../standards/repository-rules.md) remains the authoritative Product Office repository standard. This document adds GAIOS-specific expectations for AI collaborators and company OS paths.

---

## Path rules

| Path | Rule |
| --- | --- |
| `company/ai-governance/` | GAIOS control plane documents |
| `company/memory/` | Durable context summaries |
| `company/START-HERE.md`, `INDEX.md`, `SEARCH.md` | GAIOS entry surfaces |
| `company/standards/*` | Existing standards — reference only unless human authorizes edits |
| `products/*` | Product SSOT — do not relocate into GAIOS |
| Planned GAIOS folders | Create when owned; do not invent conflicting parallel trees |

---

## AI repository conduct

1. Prefer creating new markdown files over editing protected existing files.
2. Use relative links for in-repo references.
3. Do not commit secrets, credentials, or private keys.
4. Do not force-push or rewrite shared history unless a human explicitly requests and accepts the risk.
5. Do not commit unless the human explicitly asks.
6. Keep filenames stable; rename only with index/search updates.

---

## SSOT confirmation

GitHub (`gojen-product-office`) is the single source of truth. External notes and chat summaries are drafts until reflected here.

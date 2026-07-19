# AI Session Checklist

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-016 |
| Document Name | AI Session Checklist |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Gojen Product Office |
| Reviewer | Gomathi K (Founder & CEO) |
| Approver | Founder Board |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Start-of-session and end-of-session checklist for reliable AI collaboration |
| Scope | Every AI-assisted working session in gojen-product-office |
| Related Documents | [AI-RULES.md](./AI-RULES.md), [AI-WORKFLOW.md](./AI-WORKFLOW.md), [AI-CONTEXT.md](./AI-CONTEXT.md) |

## Navigation

| Link | Target |
| --- | --- |
| Parent Document | [README.md](./README.md) |
| Child Documents | None |
| Related Documents | [CURRENT-SPRINT.md](./CURRENT-SPRINT.md), [PROMPT-STANDARDS.md](./PROMPT-STANDARDS.md), [memory/README.md](../memory/README.md) |
| Previous | [AI-RULES.md](./AI-RULES.md) |
| Next | [PROMPT-STANDARDS.md](./PROMPT-STANDARDS.md) |
| Back to START-HERE | [START-HERE.md](../START-HERE.md) |

---

## Before you start

- [ ] Confirm repository: `gojen-product-office`
- [ ] Read [START-HERE.md](../START-HERE.md)
- [ ] Read [AI-CONTEXT.md](./AI-CONTEXT.md)
- [ ] Read [CURRENT-SPRINT.md](./CURRENT-SPRINT.md) (pointer) and open the linked active sprint folder
- [ ] Identify task domain: GAIOS / company / product
- [ ] Load matching memory files from [memory/](../memory/README.md)
- [ ] If product work: open the product README under `products/`
- [ ] Review [AI-RULES.md](./AI-RULES.md) for path and authority constraints
- [ ] Confirm whether existing files may be modified (default: no for GAIOS foundation work)
- [ ] Note Document IDs and standards that apply ([GPO-STD](../standards/README.md) / GOS-GPO)

---

## While working

- [ ] Keep scope aligned to the human request
- [ ] Prefer new files under approved paths when building GAIOS
- [ ] Use metadata tables and navigation blocks on new GAIOS docs
- [ ] Cross-link related GAIOS documents with relative paths
- [ ] Reference existing standards instead of copying them
- [ ] Route material decisions through [DECISION-LIFECYCLE.md](./DECISION-LIFECYCLE.md)
- [ ] Do not commit or push unless explicitly asked

---

## Before you finish

- [ ] Summarize what was accomplished in plain language
- [ ] List every new file path created
- [ ] List every existing file modified (should be none for additive GAIOS foundation)
- [ ] Call out open decisions and owners
- [ ] Point to [CURRENT-SPRINT.md](./CURRENT-SPRINT.md) if sprint status changed
- [ ] Suggest the next human or AI step
- [ ] Ensure links back to [START-HERE.md](../START-HERE.md) exist on new docs

---

## Minimal session script (AI)

1. Load START-HERE → AI-CONTEXT → CURRENT-SPRINT.
2. Load memory relevant to the ask.
3. Restate goal and constraints.
4. Execute per [AI-WORKFLOW.md](./AI-WORKFLOW.md).
5. Return file list + confirmation of non-modification of protected files when applicable.

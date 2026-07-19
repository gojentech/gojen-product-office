# Prompt Standards

| Field | Value |
| --- | --- |
| Document ID | GOS-GPO-017 |
| Document Name | Prompt Standards |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Gojen Product Office |
| Reviewer | Gomathi K (Founder & CEO) |
| Approver | Founder Board |
| Created Date | 2026-07-18 |
| Last Updated | 2026-07-18 |
| Purpose | Define how humans should prompt AI assistants for high-quality, low-drift outcomes |
| Scope | All prompting for GAIOS, company, and product work in this repository |
| Related Documents | [AI-WORKFLOW.md](./AI-WORKFLOW.md), [AI-RULES.md](./AI-RULES.md), [documentation-standards.md](./documentation-standards.md) |

## Navigation

| Link | Target |
| --- | --- |
| Parent Document | [README.md](./README.md) |
| Child Documents | None |
| Related Documents | [AI-SESSION-CHECKLIST.md](./AI-SESSION-CHECKLIST.md), [AI-CONTEXT.md](./AI-CONTEXT.md), [GPO-STD-003](../standards/writing-style.md) |
| Previous | [AI-SESSION-CHECKLIST.md](./AI-SESSION-CHECKLIST.md) |
| Next | [MEETING-STANDARDS.md](./MEETING-STANDARDS.md) |
| Back to START-HERE | [START-HERE.md](../START-HERE.md) |

---

## Prompt structure (recommended)

Every non-trivial prompt should include:

1. **Goal** — what “done” looks like
2. **Context pointers** — which GAIOS / product docs to load
3. **Constraints** — paths, non-modification rules, ID allocations
4. **Inputs** — facts, links, prior decisions
5. **Output form** — markdown files, summary, checklist, Mermaid, etc.
6. **Authority** — who owns review/approval if a decision is involved

---

## Good prompt patterns

### Create documentation

> Create a new GAIOS markdown file at `company/...` with Document ID GOS-GPO-NNN. Do not modify existing files. Include metadata table, navigation, and links to START-HERE and related docs.

### Analyze with SSOT

> Using only repository documents (start at company/START-HERE.md and products/...), summarize current Subscription OS workspace readiness and cite paths.

### Decision support

> Propose options for X. Do not mark any option Approved. Map RACI using company/ai-governance/RACI-MATRIX.md and list what must be recorded in the decision lifecycle.

---

## Anti-patterns

| Anti-pattern | Problem | Better approach |
| --- | --- | --- |
| “Update the company docs” with no paths | Risk of overwriting protected files | Name exact new paths; forbid edits to existing files |
| “Make it better” | Unclear success criteria | Define audience, length, and must-include sections |
| Pasting secrets into prompts | Security risk | Reference secret locations; never commit secrets |
| Asking AI to invent product requirements | Drift from product SSOT | Point to `products/subscription-os/` stage folders |

---

## Quality bar for prompts

- Names repository paths explicitly
- States create vs modify vs read-only
- Mentions Document IDs when allocating new docs
- Points to [START-HERE.md](../START-HERE.md) or [AI-CONTEXT.md](./AI-CONTEXT.md) for onboarding
- Aligns tone with [GPO-STD-003](../standards/writing-style.md)

---

## Prompt library future path

Reusable prompts will live under the planned `company/prompt-library/` folder. Until that folder is populated, keep high-value prompts in meeting notes or playbooks and link them from [INDEX.md](../INDEX.md) when promoted.

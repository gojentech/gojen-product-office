# Writing Style Standard

| Field | Value |
| --- | --- |
| Document ID | GPO-STD-003 |
| Title | Writing Style |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Documentation Engineering / Product Office |

## Breadcrumb

[Home](../../README.md) › [Company](../README.md) › [Standards](./README.md) › Writing Style

## Purpose

Establish consistent Markdown, structure, and business writing conventions across the Gojen Product Office.

## Heading Hierarchy

| Level | Use |
| --- | --- |
| `#` H1 | Document title only (one per file) |
| `##` H2 | Primary sections |
| `###` H3 | Subsections |
| `####` H4 | Rare; short labeled blocks only |

Do not skip levels. Do not use bold text as a fake heading.

## Table Format

- Always include a header row and an alignment separator.
- Prefer concise column headers (Title Case).
- Keep cells to one idea; link out for long content.
- For Document Information, use `| Field | Value |`.

Example:

```markdown
| Field | Value |
| --- | --- |
| Document ID | PRD-SOS-001 |
| Owner | Product Owner |
```

## Markdown Rules

1. Use ATX headings (`#`), not Setext.
2. Use hyphen bullets (`-`), not `*`.
3. Use fenced code blocks with a language tag when applicable.
4. Prefer relative links between repository files.
5. Leave one blank line before and after headings, tables, and code blocks.
6. Do not commit broken links; verify parent/child paths.
7. Store images under the nearest `assets/` folder or reference external sources of truth.

## Mermaid Usage

Use Mermaid when it clarifies structure, process, ownership, or decisions.

| Prefer Mermaid for | Prefer tables/lists for |
| --- | --- |
| Lifecycles and workflows | Status inventories |
| System / folder structure | Prefix registries |
| Decision paths | Version history |

Place a short prose introduction above each diagram. Keep node labels short.

## Business Writing Style

- Prefer clear, direct sentences.
- Lead with the decision or outcome, then context.
- Avoid filler and marketing language in internal specs.
- Define acronyms on first use; add lasting terms to the [glossary](../../glossary/README.md).
- Separate facts, recommendations, and open questions.

## Naming Conventions

| Artifact | Convention | Example |
| --- | --- | --- |
| Folders | kebab-case, fixed portfolio structure | `02-market-research` |
| Files | kebab-case | `document-numbering.md` |
| Document IDs | UPPERCASE with hyphens | `PRD-SOS-001` |
| Template files | `{type}-template.md` | `prd-template.md` |

Do not rename top-level or lifecycle folders.

## Capitalization

| Context | Rule |
| --- | --- |
| Document titles / H1 | Title Case |
| H2/H3 headings | Sentence case preferred |
| Table headers | Title Case |
| Product names | Official product capitalization (Subscription OS, Pawn Management) |
| Status values | Capitalize: Draft, In Review, Approved, Released, Archived |

## Lists

- Use numbered lists for sequences and procedures.
- Use bullets for unordered collections.
- Keep parallel grammatical structure.
- Limit nesting to two levels.

## Cross References

1. Link by document title and path: `[Document numbering](./document-numbering.md)`.
2. Include Document ID when citing a formal artifact: `See PRD-SOS-001`.
3. Update Related Documents in the local README when adding material.
4. Prefer `INDEX.md` as the master map for discovery.

## Related Documents

- [Document numbering](./document-numbering.md)
- [Versioning](./versioning.md)
- [Repository rules](./repository-rules.md)
- [Glossary](../../glossary/README.md)
- [Contributing](../../CONTRIBUTING.md)

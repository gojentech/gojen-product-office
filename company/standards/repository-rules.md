# Repository Rules Standard

| Field | Value |
| --- | --- |
| Document ID | GPO-STD-005 |
| Title | Repository Rules |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Documentation Engineering / Product Office |

## Breadcrumb

[Home](../../README.md) › [Company](../README.md) › [Standards](./README.md) › Repository Rules

## Purpose

Define non-negotiable rules for structure, ownership, linking, IDs, archive behavior, and contributions in `gojen-product-office`.

## Folder Ownership

| Area | Owner |
| --- | --- |
| `company/` doctrine folders | Founder Board (Product Office stewards files) |
| `company/standards/` | Documentation Engineering / Product Office |
| `products/<product>/` | Product Owner for that product |
| `templates/` | Documentation Engineering / Product Office |
| `glossary/` | Documentation Engineering / Product Office |
| `references/` | Documentation Engineering / Product Office |
| `archive/` | Documentation Engineering / Product Office |
| `.github/` | Documentation Engineering / Product Office |

Folder names are fixed. Do not invent parallel top-level structures.

## README Standards

Every folder `README.md` must include:

1. **Breadcrumb**
2. **Navigation Links**
3. **Parent Folder**
4. **Child Folders** (if any)
5. **Purpose**
6. **Owner**
7. **Related Documents**

Contents inventories belong in the README when the folder holds multiple artifacts.

## No Duplicate Documents

1. One authoritative location per Document ID.
2. Do not copy the same content into multiple lifecycle folders.
3. Cross-link instead of duplicating.
4. If a summary is needed elsewhere, link to the source and keep the summary short.

## Cross Linking

1. Every formal document lists Related Documents.
2. Folder READMEs link to parent, children, and key peers.
3. Register discoverable artifacts in [INDEX.md](../../INDEX.md).
4. Prefer relative Markdown links.

## Document IDs

1. Assign IDs per [document-numbering.md](./document-numbering.md).
2. Place the ID in the document header.
3. Never reuse a retired ID.
4. Templates are not instances; do not allocate product scopes to template files.

## Archive Rules

1. Move superseded material to `archive/` instead of deleting history.
2. Record original path and archive date in the archived file or an archive index entry.
3. Set status to **Archived** and link the successor document.
4. Leave a stub link from the original README when helpful.

## Contribution Rules

1. Follow [CONTRIBUTING.md](../../CONTRIBUTING.md) and these standards.
2. Create documents from [templates](../../templates/README.md).
3. Update CHANGELOG for structural or standards changes.
4. Open a pull request; request review from the folder Owner.
5. Do not commit secrets, credentials, or private customer data.
6. Do not generate placeholder business documents.

## Related Documents

- [Document numbering](./document-numbering.md)
- [Versioning](./versioning.md)
- [Writing style](./writing-style.md)
- [Meeting process](./meeting-process.md)
- [Contributing](../../CONTRIBUTING.md)
- [Master index](../../INDEX.md)

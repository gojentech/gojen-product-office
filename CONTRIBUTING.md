# Contributing to Gojen Product Office

Thank you for contributing to the Gojen Product Office documentation repository.

## Breadcrumb

[Home](./README.md) › Contributing

## Navigation Links

- [Dashboard](./README.md)
- [Master Index](./INDEX.md)
- [Standards](./company/standards/README.md)
- [Templates](./templates/README.md)
- [Repository rules](./company/standards/repository-rules.md)
- [Changelog](./CHANGELOG.md)

## Principles

1. Follow the existing folder structure exactly. Do not invent, rename, or restructure top-level or product lifecycle folders.
2. Every folder `README.md` must include Breadcrumb, Navigation Links, Parent Folder, Child Folders, Purpose, Owner, and Related Documents.
3. Do not commit placeholder business documents. Add substantive content when it is ready for review.
4. Cross-link related documents; assign Document IDs per [document-numbering.md](./company/standards/document-numbering.md).
5. Prefer templates from [templates/](./templates/README.md).
6. Follow [writing-style.md](./company/standards/writing-style.md) and [versioning.md](./company/standards/versioning.md).

## Where to put work

| Type of change | Location |
| --- | --- |
| Company vision, founders, governance, standards, operating model | `company/` |
| Product lifecycle documentation | `products/<product>/` |
| Shared reusable formats | `templates/` |
| Shared definitions | `glossary/` |
| Citations and supporting material | `references/` |
| Superseded documents | `archive/` |
| Issue templates or CI workflows | `.github/` |

## Workflow

1. Create a branch from `main`.
2. Copy the appropriate template from [templates/](./templates/README.md).
3. Assign a Document ID and set version/status metadata.
4. Update affected README navigation, Related Documents, and [INDEX.md](./INDEX.md) when adding discoverable documents.
5. Note repository-visible changes in [CHANGELOG.md](./CHANGELOG.md) when they are structural or standards-related.
6. Open a pull request describing what changed, why, and which folders are affected.
7. Request review from the document Owner listed in the relevant folder README.

## Pull request expectations

- Clear title scoped to documentation intent (for example, `docs(gpo): add document numbering standard`)
- Links to related decision-log or risk-register entries when applicable
- No secrets, credentials, or private customer data
- Mermaid diagrams used when they clarify structure or process
- Compliance with [repository-rules.md](./company/standards/repository-rules.md)

## Ownership

- **Repository standards:** Documentation Engineering / Product Office
- **Company doctrine:** Founder Board via [company/governance](./company/governance/README.md)
- **Product docs:** Owner listed in each product folder README

Questions about structure or standards should be raised through repository issues using templates under [.github/ISSUE_TEMPLATE](./.github/ISSUE_TEMPLATE/README.md).

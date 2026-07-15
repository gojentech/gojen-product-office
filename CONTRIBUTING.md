# Contributing to Gojen Product Office

Thank you for contributing to the Gojen Product Office documentation repository.

## Navigation

- [Repository home](./README.md)
- [Documentation standards](./README.md#documentation-standards)
- [Company standards](./company/standards/README.md)
- [Templates](./templates/README.md)
- [Changelog](./CHANGELOG.md)

## Principles

1. Follow the existing folder structure exactly. Do not invent, rename, or restructure top-level or product lifecycle folders.
2. Add a `README.md` only when creating a new approved folder; keep Purpose, Contents, Owner, and Related Documents current.
3. Do not commit placeholder business documents. Add substantive content when it is ready for review.
4. Cross-link related documents from folder READMEs.
5. Prefer templates from [templates/](./templates/README.md).

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
2. Make documentation changes in the correct folder.
3. Update affected README navigation and Related Documents sections.
4. Note repository-visible changes in [CHANGELOG.md](./CHANGELOG.md) when they are structural or standards-related.
5. Open a pull request describing:
   - What changed
   - Why it changed
   - Which folders or products are affected
6. Request review from the document Owner listed in the relevant folder README.

## Pull request expectations

- Clear title scoped to documentation intent (for example, `docs(subscription-os): add discovery research notes`)
- Links to related decision-log or risk-register entries when applicable
- No secrets, credentials, or private customer data
- Mermaid diagrams used when they clarify structure or process

## Ownership

- **Repository standards:** Documentation Engineering / Product Office
- **Company doctrine:** Founder Board via [company/governance](./company/governance/README.md)
- **Product docs:** Owner listed in each product folder README

Questions about structure or standards should be raised through repository issues using templates under [.github/ISSUE_TEMPLATE](./.github/ISSUE_TEMPLATE/README.md).

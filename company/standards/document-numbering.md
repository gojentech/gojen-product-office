# Document Numbering Standard

| Field | Value |
| --- | --- |
| Document ID | GPO-STD-001 |
| Title | Document Numbering |
| Version | 1.0.0 |
| Status | Approved |
| Owner | Documentation Engineering / Product Office |

## Breadcrumb

[Home](../../README.md) › [Company](../README.md) › [Standards](./README.md) › Document Numbering

## Purpose

Define how Gojen Product Office documents are identified so every artifact is unique, searchable, and cross-linkable.

## Format

```text
{PREFIX}-{SCOPE}-{SEQUENCE}[-{SUFFIX}]
```

| Segment | Description | Example |
| --- | --- | --- |
| `PREFIX` | Document class from the prefix registry | `PRD` |
| `SCOPE` | Product or company scope code | `SOS` (Subscription OS), `PAW` (Pawn Management), `GPO` (Product Office) |
| `SEQUENCE` | Zero-padded integer, allocated once | `001` |
| `SUFFIX` | Optional revision or part marker | `A`, `PART2` |

**Canonical ID example:** `PRD-SOS-001`

**Filename pattern:** `{document-id}-{kebab-case-title}.md`

Example filename: `prd-sos-001-subscription-billing-core.md`

## Prefix Registry

| Prefix | Name | Typical location |
| --- | --- | --- |
| `GPO` | Gojen Product Office (governance / office docs) | `company/`, root |
| `GOS` | Gojen Operating System | `company/operating-system/` |
| `PDC` | Product Discovery / Charters | `products/*/01-discovery/` |
| `MRR` | Market Research Report | `products/*/02-market-research/` |
| `CAR` | Competitive Analysis Report | `products/*/02-market-research/` |
| `ICP` | Ideal Customer Profile | `products/*/02-market-research/` or `03-business/` |
| `CVP` | Customer Value Proposition | `products/*/03-business/` |
| `BMC` | Business Model Canvas / commercial model | `products/*/03-business/` |
| `BRD` | Business Requirements Document | `products/*/03-business/` |
| `PRD` | Product Requirements Document | `products/*/04-product/` |
| `UX` | User experience / design specs | `products/*/05-design/` |
| `ARCH` | Architecture overview | `products/*/06-architecture/` |
| `API` | API specification | `products/*/06-architecture/` or `07-engineering/` |
| `SPR` | Sprint / engineering plan artifact | `products/*/07-engineering/` |
| `REL` | Release documentation | `products/*/11-release/` |
| `DEC` | Decision record | `products/*/decision-log/` |
| `RISK` | Risk register entry | `products/*/risk-register/` |
| `ADR` | Architecture Decision Record | `products/*/06-architecture/` or `decision-log/` |
| `MTG` | Meeting minutes | `*/meeting-minutes/` |
| `STD` | Standard | `company/standards/` |
| `TPL` | Template | `templates/` |
| `GLO` | Glossary entry set | `glossary/` |

## Scope Codes

| Scope | Meaning |
| --- | --- |
| `GPO` | Company / Product Office wide |
| `SOS` | Subscription OS |
| `PAW` | Pawn Management |

New products receive a three-letter scope code approved by the Product Office before first document issuance.

## Numbering Examples

| Document | Document ID | Filename |
| --- | --- | --- |
| Product Office numbering standard | `GPO-STD-001` | `document-numbering.md` (standards may use stable names) |
| Discovery charter for Subscription OS | `PDC-SOS-001` | `pdc-sos-001-problem-framing.md` |
| Market research report | `MRR-SOS-001` | `mrr-sos-001-segment-overview.md` |
| Competitive analysis | `CAR-SOS-001` | `car-sos-001-competitor-landscape.md` |
| Ideal customer profile | `ICP-SOS-001` | `icp-sos-001-primary-buyer.md` |
| Value proposition | `CVP-SOS-001` | `cvp-sos-001-core-offer.md` |
| Business model | `BMC-SOS-001` | `bmc-sos-001-subscription-model.md` |
| Business requirements | `BRD-SOS-001` | `brd-sos-001-billing-capabilities.md` |
| Product requirements | `PRD-SOS-001` | `prd-sos-001-billing-core.md` |
| UX specification | `UX-SOS-001` | `ux-sos-001-checkout-flow.md` |
| Architecture overview | `ARCH-SOS-001` | `arch-sos-001-platform-overview.md` |
| API specification | `API-SOS-001` | `api-sos-001-subscriptions-v1.md` |
| Sprint plan note | `SPR-SOS-001` | `spr-sos-001-engineering-plan.md` |
| Release notes pack | `REL-SOS-001` | `rel-sos-001-v1-0-launch.md` |
| Decision | `DEC-SOS-001` | `dec-sos-001-billing-engine-choice.md` |
| Risk | `RISK-SOS-001` | `risk-sos-001-payment-provider.md` |
| ADR | `ADR-SOS-001` | `adr-sos-001-event-driven-billing.md` |
| Founder Board meeting | `MTG-GPO-001` | `mtg-gpo-001-2026-07-15-founder-board.md` |

## Allocation Rules

1. Sequence numbers are allocated per `PREFIX-SCOPE` pair and never reused.
2. Superseded documents keep their ID; mark status `Archived` and link the successor.
3. Document ID appears in the document header and in [INDEX.md](../../INDEX.md) when listed.
4. Templates themselves use `TPL` only in metadata; templates are not product instances.

## Related Documents

- [Versioning](./versioning.md)
- [Repository rules](./repository-rules.md)
- [Writing style](./writing-style.md)
- [Templates index](../../templates/README.md)
- [Master index](../../INDEX.md)

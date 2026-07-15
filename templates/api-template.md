# API Template

> API specification scaffold. Allocate `API-{SCOPE}-{NNN}`.

## Document Information

| Field | Value |
| --- | --- |
| Document ID | `API-{SCOPE}-{NNN}` |
| Title | `{API Title}` |
| Product / Scope | `{SOS \| PAW \| …}` |
| Version | `0.1.0` |
| Status | Draft |
| Author | `{Name}` |
| Owner | `{Engineering Lead}` |
| API Version | `v1` |
| Base Path | `/api/v1/…` |
| Created | `YYYY-MM-DD` |
| Last Updated | `YYYY-MM-DD` |

## Version History

| Version | Date | Author | Summary |
| --- | --- | --- | --- |
| 0.1.0 | YYYY-MM-DD | Name | Initial draft |

## Purpose

Specify the contract for a service interface consumed by clients or internal systems.

## Scope

### In Scope

- Endpoints, resources, and contracts in this API surface

### Out of Scope

- Client UI behavior and non-API workflows

## Authentication and Authorization

| Mechanism | Detail |
| --- | --- |
| AuthN | … |
| AuthZ | … |

## Conventions

| Topic | Convention |
| --- | --- |
| Format | JSON |
| Error envelope | … |
| Pagination | … |
| Idempotency | … |

## Endpoints

### `{METHOD} {path}`

| Field | Value |
| --- | --- |
| Summary | … |
| Auth required | Yes / No |

**Request**

```json
{
  "example": true
}
```

**Response `200`**

```json
{
  "example": true
}
```

**Errors**

| Code | Meaning |
| --- | --- |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |
| 500 | Server error |

## Assumptions

| ID | Assumption | Impact if false |
| --- | --- | --- |
| A-01 | … | … |

## Risks

| Risk ID | Description | Likelihood | Impact | Mitigation | Owner |
| --- | --- | --- | --- | --- | --- |
| R-01 | … | L/M/H | L/M/H | … | … |

## References

| Document ID | Title | Link |
| --- | --- | --- |
| … | … | … |

## Approval Table

| Role | Name | Decision | Date |
| --- | --- | --- | --- |
| Author | | Prepared | |
| Engineering Lead | | | |
| Architecture Lead | | | |
| Approver | | | |

## Change Log

| Date | Version | Change | Author |
| --- | --- | --- | --- |
| YYYY-MM-DD | 0.1.0 | Initial API spec from template | Name |

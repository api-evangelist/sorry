# Sorry

Sorry™ (SorryApp) is a status page platform that enables teams to communicate planned and unplanned service interruptions to their customers. The Sorry REST API provides full programmatic control over status pages, components, incident notices, notice updates, and subscriber management for automated incident communication workflows.

**URL:** [https://raw.githubusercontent.com/api-evangelist/sorry/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sorry/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Status Pages, Incident Management, Developer Tools, Monitoring, Notifications

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-02

## APIs

### Sorry Status Page API

The Sorry™ REST API provides programmatic access to manage status pages, components, incident notices, notice updates, and subscriber lists. Supports Bearer token authentication and rate limiting of 10 requests per second.

**Human URL:** [https://docs.sorryapp.com/v1](https://docs.sorryapp.com/v1)
**Base URL:** `https://api.sorryapp.com/v1`

#### Tags

Status Pages, Incident Management, Notifications, Subscribers

#### Properties

- [Documentation](https://docs.sorryapp.com/v1)
- [Getting Started](https://app.sorryapp.com)
- [OpenAPI](openapi/sorry-status-page-openapi.yml)

## Artifacts

### OpenAPI Specifications

| API | File |
|-----|------|
| Sorry Status Page API | [openapi/sorry-status-page-openapi.yml](openapi/sorry-status-page-openapi.yml) |

### Spectral Rules

| Ruleset | File |
|---------|------|
| Sorry Rules | [rules/sorry-rules.yml](rules/sorry-rules.yml) |

### Naftiko Capabilities

**Shared Definitions:**

| API | File |
|-----|------|
| Sorry Status Page | [capabilities/shared/sorry-status-page.yaml](capabilities/shared/sorry-status-page.yaml) |

**Workflow Capabilities:**

| Workflow | File | Description |
|----------|------|-------------|
| Incident Communications | [capabilities/incident-communications.yaml](capabilities/incident-communications.yaml) | Automated incident communication workflows |

### JSON Schemas

| Schema | File |
|--------|------|
| Status Page | [json-schema/sorry-page-schema.json](json-schema/sorry-page-schema.json) |
| Notice | [json-schema/sorry-notice-schema.json](json-schema/sorry-notice-schema.json) |

### JSON Structures

| Structure | File |
|-----------|------|
| Notice | [json-structure/sorry-notice-structure.json](json-structure/sorry-notice-structure.json) |

### JSON-LD Contexts

| Context | File |
|---------|------|
| Sorry | [json-ld/sorry-context.jsonld](json-ld/sorry-context.jsonld) |

### Examples

| Example | File |
|---------|------|
| Create Notice | [examples/sorry-create-notice-example.json](examples/sorry-create-notice-example.json) |

### Vocabulary

| Vocabulary | File |
|------------|------|
| Sorry | [vocabulary/sorry-vocabulary.yml](vocabulary/sorry-vocabulary.yml) |

## Common Properties

- [Portal](https://www.sorryapp.com/)
- [Documentation](https://docs.sorryapp.com/v1)
- [Website](https://www.sorryapp.com/)
- [Status API](https://www.sorryapp.com/status-api/)
- [Dashboard](https://app.sorryapp.com/)
- [GitHub Org](https://github.com/sorry-app)
- [Pricing](https://www.sorryapp.com/pricing/)
- [Integrations](https://www.sorryapp.com/integrations/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

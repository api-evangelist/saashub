# SaaSHub

SaaSHub is an independent software discovery platform that helps users find, compare, and discover software alternatives across SaaS, web, and cloud-based applications. The platform maintains a comprehensive catalog of software products with user reviews, pricing information, feature comparisons, and curated lists of alternatives. SaaSHub serves as a permanent directory where software vendors can list their products and users can discover alternatives to tools they already use.

**Website:** [https://www.saashub.com/](https://www.saashub.com/)
**API Documentation:** [https://www.saashub.com/site/api](https://www.saashub.com/site/api)
**APIs.yml:** [https://raw.githubusercontent.com/api-evangelist/saashub/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/saashub/refs/heads/main/apis.yml)

## APIs

### SaaSHub API

The SaaSHub public API provides programmatic access to SaaSHub's software discovery platform. Two primary endpoints: a product endpoint returning data for the first product matching a query, and an alternatives endpoint returning the matching product along with its top 10 relevant alternatives. Responses follow the JSON:API specification.

- **Base URL:** `https://www.saashub.com/api`
- **Documentation:** [https://www.saashub.com/site/api](https://www.saashub.com/site/api)
- **OpenAPI:** [openapi/saashub-openapi.yml](openapi/saashub-openapi.yml)
- **Authentication:** API key via `api_key` query parameter

### Endpoints

| Method | Path | Description |
|--------|------|-------------|
| GET | `/api/product/{query}` | Get product data matching query |
| GET | `/api/alternatives/{query}` | Get product with top 10 alternatives |

### Authentication

API key required. Obtain from [https://www.saashub.com/profile/api_key](https://www.saashub.com/profile/api_key). Users must disclose SaaSHub API usage on their website.

## OpenAPI Specifications

| API | File |
|-----|------|
| SaaSHub API | [openapi/saashub-openapi.yml](openapi/saashub-openapi.yml) |

## Capabilities

| Capability | Description |
|-----------|-------------|
| [capabilities/software-discovery.yaml](capabilities/software-discovery.yaml) | Software discovery and alternatives research workflow |

### Shared Definitions

| API | File |
|-----|------|
| SaaSHub API | [capabilities/shared/saashub.yaml](capabilities/shared/saashub.yaml) |

## JSON Schema

| Schema | File |
|--------|------|
| SaaSHub Product | [json-schema/saashub-product-schema.json](json-schema/saashub-product-schema.json) |

## JSON Structure

| Structure | File |
|-----------|------|
| SaaSHub Product | [json-structure/saashub-product-structure.json](json-structure/saashub-product-structure.json) |

## JSON-LD

| Context | File |
|---------|------|
| SaaSHub Context | [json-ld/saashub-context.jsonld](json-ld/saashub-context.jsonld) |

## Examples

| Example | File |
|---------|------|
| Get Product Alternatives | [examples/saashub-get-product-alternatives-example.json](examples/saashub-get-product-alternatives-example.json) |

## Rules

| Ruleset | File |
|---------|------|
| SaaSHub Spectral Rules | [rules/saashub-spectral-rules.yml](rules/saashub-spectral-rules.yml) |

## Vocabulary

| Vocabulary | File |
|-----------|------|
| SaaSHub Vocabulary | [vocabulary/saashub-vocabulary.yml](vocabulary/saashub-vocabulary.yml) |

## Tags

Alternatives, SaaS, Software Discovery, Software Catalog

## Links

- [Website](https://www.saashub.com/)
- [API Documentation](https://www.saashub.com/site/api)
- [Get API Key](https://www.saashub.com/profile/api_key)
- [FAQ](https://www.saashub.com/faq)
- [Newsletter](https://www.saashub.com/newsletter)
- [Privacy Policy](https://www.saashub.com/site/privacy)
- [Sign Up](https://www.saashub.com/users/sign_up)
- [X (Twitter)](https://twitter.com/saashubcom)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

# Theneo

Beautiful, up-to-date docs without the effort. Theneo is an AI-native API documentation and developer portal platform that auto-generates interactive docs from OpenAPI, Swagger, Postman, GraphQL, gRPC, SOAP/WSDL, and AsyncAPI specifications. Its AI Co-pilot can fully generate, enhance, or stay out of the way of human-authored content, while Ask AI Bot, MCP server integration, llms.txt support, smart changelogs, and the Elva API management platform extend the same surface to AI agents. Used by 15,000+ teams including Ticketmaster, Corpay, and SimilarWeb; backed by Y Combinator; SOC 2 Type II, ISO 27001, ISO 9001, and GDPR compliant.

**URL:** [https://raw.githubusercontent.com/api-evangelist/theneo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/theneo/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- API Documentation
- Developer Portal
- Developer Tools
- Documentation Platform
- AI
- AI Co-Pilot
- MCP
- Platform

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-22

## APIs

### Theneo API

The Theneo API provides programmatic access to manage API documentation projects, workspaces, user access, and API specification imports on the Theneo platform. Supports creating, publishing, and sharing AI-generated API documentation built from OpenAPI, Swagger, Postman, GraphQL, gRPC, SOAP/WSDL, and AsyncAPI specifications. Pairs with the `@theneo/cli` and `@theneo/sdk` npm packages and the Theneo GitHub Action for CI-driven docs updates.

**Human URL:** [https://www.theneo.io/](https://www.theneo.io/)

**Base URL:** https://api.theneo.io

#### Tags

- API Documentation
- Developer Portal
- Developer Tools
- Documentation Platform
- AI
- AI Co-Pilot
- MCP
- OpenAPI

#### Operations

| Method | Path | Summary |
|--------|------|---------|
| GET | /projects | Get All Projects |
| POST | /projects | Add New Project |
| GET | /projects/{projectId} | Get Project By ID |
| DELETE | /projects/{projectId} | Delete Project |
| GET | /projects/{projectId}/users | Get Accessible Users |
| POST | /projects/{projectId}/share | Share A Project |
| PATCH | /projects/{projectId}/users/{userId} | Change User Access To A Project |
| POST | /projects/{projectId}/import | Import API Specification |
| POST | /projects/{projectId}/publish | Publish Project |
| GET | /projects/{projectId}/preview | Get Preview Project Link |
| GET | /workspaces | List Workspaces |

#### Properties

- [Documentation](https://www.theneo.io/)
- [OpenAPI](openapi/theneo-api-openapi.yml)
- [JSON Schema - Project](json-schema/project.json)
- [JSON Schema - Workspace](json-schema/workspace.json)
- [JSON Schema - Project User](json-schema/project-user.json)
- [JSON-LD](json-ld/theneo-context.jsonld)
- [JSON Structure](json-structure/theneo-project-structure.json)
- [Spectral Rules](rules/theneo-rules.yml)
- [Vocabulary](vocabulary/theneo-vocabulary.yml)
- [Plans & Pricing](plans/theneo-plans-pricing.yml)
- [Rate Limits](rate-limits/theneo-rate-limits.yml)
- [FinOps](finops/theneo-finops.yml)

## AI & Agent Readiness

Theneo has built AI-powered capabilities since 2022. The platform now spans documentation authoring, search, and agent exposure:

- **AI Co-pilot** — At import time pick a co-pilot level: full generation, content enhancement, or no AI assistance. Theneo states *"harness the power of Theneo's AI Co-pilot to enrich your content."*
- **TheneoAI Doc Builder** — Metered AI documentation generation. Starter is capped at 2,000 actions/month; Business+ is unlimited.
- **Ask AI Bot** — Embedded assistant that answers developer questions directly rather than returning search results.
- **searchAI** — GPT-powered search across published docs. Starter caps at 100 responses/month; Business+ is unlimited.
- **Smart Changelog** — Automated breaking-change detection across OpenAPI imports.
- **MCP Server** — Exposes a Theneo developer portal as a Model Context Protocol server so AI agents can call documented APIs as tools.
- **llms.txt** — Auto-generates the discovery index that advertises an API to large language models.
- **Elva** *(May 15, 2026)* — Adjacent API management platform for cataloging APIs and exposing them to AI agents via MCP. *"The API management platform that makes your APIs agent-ready."*
- **Cartlis** — Open-source AI-powered API governance agent that enforces rules in real time and auto-patches violations.

## Customers, Scale & Compliance

- 15,000+ teams use Theneo; flagship customers include Ticketmaster, Corpay, SimilarWeb, and Fortune 500 companies.
- Y Combinator-backed; featured in TechCrunch and Forbes; Theneo 3.0 was Product Hunt's #1 Developer Tool.
- Compliance: SOC 2 (annual audits), ISO 27001, ISO 9001, GDPR.
- Security: AES-256 at rest, TLS 1.3 in transit, MFA enforcement, OAuth, role-based access, 7-day point-in-time backups, quarterly internal audits, annual third-party vulnerability assessments.
- EU Data Residency available for enterprise customers (announced May 11, 2026).

## Plans & Pricing

Theneo's pricing is workspace-based subscription. Annual billing is shown; monthly equivalents in parentheses. Source: https://www.theneo.io/pricing

| Tier | Price (Annual) | Projects | Team Members | AI Quotas |
|------|----------------|----------|--------------|-----------|
| Starter | Free | 1 public, 2 private | 20 | 100 searchAI / 2,000 TheneoAI actions per month |
| Business | $120/mo workspace ($150/mo monthly) | 7 | 50 | Unlimited |
| Growth | $400/mo workspace ($450/mo monthly) | 7 + up to 20 Developer Hubs | 50 | Unlimited + custom ChatGPT prompts |
| Enterprise | Custom | Unlimited | Unlimited | Unlimited + self-hosting, SAML SSO, EU residency |

See [plans/theneo-plans-pricing.yml](plans/theneo-plans-pricing.yml) for machine-readable detail.

## Artifacts

### OpenAPI Specs

- [Theneo API](openapi/theneo-api-openapi.yml)

### JSON Schemas

- [Project](json-schema/project.json)
- [Workspace](json-schema/workspace.json)
- [Project User](json-schema/project-user.json)

### JSON Structure

- [Theneo Project Structure](json-structure/theneo-project-structure.json)

### JSON-LD

- [Theneo Context](json-ld/theneo-context.jsonld)

### Examples

- [Get All Projects](examples/theneo-get-all-projects-example.json)
- [Add New Project](examples/theneo-add-new-project-example.json)
- [Import API Specification](examples/theneo-import-api-specification-example.json)
- [Publish Project](examples/theneo-publish-project-example.json)

### Spectral Rules

- [Theneo Rules](rules/theneo-rules.yml)

### Capabilities

- [Theneo Import](capabilities/theneo-import.yaml)
- [Theneo Projects](capabilities/theneo-projects.yaml)
- [Theneo Publishing](capabilities/theneo-publishing.yaml)
- [Theneo Users](capabilities/theneo-users.yaml)
- [Theneo Workspaces](capabilities/theneo-workspaces.yaml)

### Vocabulary

- [Theneo Vocabulary](vocabulary/theneo-vocabulary.yml)

### Plans, Rate Limits & FinOps

- [Plans & Pricing](plans/theneo-plans-pricing.yml)
- [Rate Limits](rate-limits/theneo-rate-limits.yml)
- [FinOps](finops/theneo-finops.yml)

## Tooling & Automation

Theneo ships first-party tooling alongside the API:

- **theneo-tools** — Monorepo hosting `@theneo/cli` and `@theneo/sdk`. TypeScript, MIT licensed, Node 18.x+, 36 releases. [Theneo-Inc/theneo-tools](https://github.com/Theneo-Inc/theneo-tools)
- **api-documentation** — GitHub Action that imports OpenAPI/Swagger specs into a Theneo project on push, with configurable merge strategy and optional auto-publish. [Theneo-Inc/api-documentation](https://github.com/Theneo-Inc/api-documentation)
- **Cartlis** — Open-source AI-powered API governance agent (Python). [Theneo-Inc/Cartlis](https://github.com/Theneo-Inc/Cartlis)
- **Liblab partnership** — Instant SDK generation across languages (April 2025).

## Common Properties

- [GitHub Organization](https://github.com/Theneo-Inc)
- [Theneo CLI & SDK (theneo-tools)](https://github.com/Theneo-Inc/theneo-tools)
- [Theneo GitHub Action (api-documentation)](https://github.com/Theneo-Inc/api-documentation)
- [Cartlis - AI-Powered API Governance Agent](https://github.com/Theneo-Inc/Cartlis)
- [Documentation](https://app.theneo.io/theneo/quickstart/theneo-quickstart-guide)
- [FAQ](https://app.theneo.io/theneo/quickstart/faq-2)
- [Pricing](https://www.theneo.io/pricing)
- [Blog](https://www.theneo.io/blog)
- [Security](https://www.theneo.io/security)
- [LinkedIn](https://www.linkedin.com/company/theneoinc)
- [Sign Up](https://app.theneo.io/signup)
- [Book a Demo](https://calendly.com/theneo/theneo-demo)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

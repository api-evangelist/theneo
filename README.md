# Theneo

Beautiful, up-to-date docs without the effort. Automatically generate and enhance your API documentation with AI, integrate seamlessly with your workflow, and collaborate effectively with your team. Theneo is an AI-powered API documentation platform that generates interactive docs from OpenAPI, Swagger, Postman, and GraphQL specifications.

**URL:** [https://raw.githubusercontent.com/api-evangelist/theneo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/theneo/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- API Documentation
- Developer Tools
- Documentation Platform
- AI
- Platform

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-03

## APIs

### Theneo API

The Theneo API provides programmatic access to manage API documentation projects, workspaces, user access, and API specification imports on the Theneo platform. Supports creating, publishing, and sharing API documentation generated from OpenAPI, Swagger, Postman, and GraphQL specifications.

**Human URL:** [https://www.theneo.io/](https://www.theneo.io/)

**Base URL:** https://api.theneo.io

#### Tags

- API Documentation
- Developer Tools
- Documentation Platform
- AI
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
- [Capabilities](capabilities/api-documentation.yaml)
- [Vocabulary](vocabulary/theneo-vocabulary.yml)

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

- [API Documentation Management](capabilities/api-documentation.yaml)

**Shared Definitions:**

- [Theneo API](capabilities/shared/theneo-api.yaml)

### Vocabulary

- [Theneo Vocabulary](vocabulary/theneo-vocabulary.yml)

## Common Properties

- [GitHub Organization](https://github.com/Theneo-Inc)
- [Documentation](https://app.theneo.io/theneo/quickstart/theneo-quickstart-guide)
- [FAQ](https://app.theneo.io/theneo/quickstart/faq-2)
- [Pricing](https://www.theneo.io/pricing)
- [Blog](https://www.theneo.io/blog)
- [Security](https://www.theneo.io/security)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

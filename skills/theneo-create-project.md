---
name: theneo-create-project
description: Create a new project and retrieve its details.
api: openapi/theneo-projects-api-openapi.yml
operations:
- addNewProject
- getProjectById
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/theneo-projects-api-openapi.yml ; every operationId checked against the contract
---

# theneo-create-project

Create a new project and retrieve its details.

## Steps

1. 1. Call `addNewProject` with the required request body fields for a new project and include the `Authorization` header.
2. 2. Call `getProjectById` using the `projectId` returned from the previous step and include the `Authorization` header.

## Rules

- Authentication: provide an API key in the `Authorization` header.
- Idempotency: not applicable for these operations.

---
name: theneo-publish-and-preview
description: Publish a project and retrieve its preview link.
api: openapi/theneo-publishing-api-openapi.yml
operations:
- publishProject
- getPreviewProjectLink
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/theneo-publishing-api-openapi.yml ; every operationId checked against the contract
---

# theneo-publish-and-preview

Publish a project and retrieve its preview link.

## Steps

1. 1. Call `publishProject` with the required path parameter `projectId` and include the `Authorization` header containing the API key.
2. 2. Call `getPreviewProjectLink` with the same `projectId` and include the `Authorization` header containing the API key.

## Rules

- Auth: Provide the API key in the `Authorization` header as required by the `apiKey` scheme.

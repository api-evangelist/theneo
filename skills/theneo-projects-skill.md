---
name: projects
description: Provides comprehensive interaction with the Theneo Projects API, enabling agents to list, create, retrieve, and delete project resources within the Theneo platform.
api: https://docs.theneo.io/api-reference/projects
operations:
  - getAllProjects
  - addNewProject
  - getProjectById
  - deleteProject
---
# Projects Skill
This skill allows agents to list, create, retrieve, and delete projects.

1. **List Projects** – call `GET /projects` (operationId `getAllProjects`).
2. **Create Project** – call `POST /projects` with body (operationId `addNewProject`).
3. **Get Project** – call `GET /projects/{projectId}` (operationId `getProjectById`).
4. **Delete Project** – call `DELETE /projects/{projectId}` (operationId `deleteProject`).

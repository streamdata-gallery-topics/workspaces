---
swagger: "2.0"
x-collection-name: Sustainable Facilities Tool API
x-complete: 1
info:
  title: Sustainable Facilities Tool API
  description: our-core-api-allows-developers-to-interact-with-the-sustainable-facilities-tool-programmatically--its-designed-for-public-use-and-to-be-easily-integrated-into-other-applications-
  termsOfService: https://sftool.gov/developer/terms-of-use
  version: 1.0.0
host: api.data.gov
basePath: /sftool/v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workspaces:
    get:
      summary: Workspaces
      description: Returns all workspaces.
      operationId: getWorkspaces
      x-api-path-slug: workspaces-get
      responses:
        200:
          description: OK
      tags:
      - Workspaces
  /workspaces/{parameter}:
    get:
      summary: Workspace
      description: Returns a workspace by parameter.
      operationId: getWorkspace
      x-api-path-slug: workspacesparameter-get
      responses:
        200:
          description: OK
      tags:
      - Workspaces
  /workspaces/{parameter}/material-groups:
    get:
      summary: Workspaces
      description: Returns material groups for the workspace selected by parameter.
      operationId: getWorkspaceMaterialGroups
      x-api-path-slug: workspacesparametermaterialgroups-get
      responses:
        200:
          description: OK
      tags:
      - Workspaces
  /workspaces/{parameter}/materials:
    get:
      summary: Workspace Materials
      description: Returns materials for the workspace selected by parameter.
      operationId: getWorkspaceMaterials
      x-api-path-slug: workspacesparametermaterials-get
      responses:
        200:
          description: OK
      tags:
      - Workspaces
---
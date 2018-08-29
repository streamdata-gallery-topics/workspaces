---
swagger: "2.0"
x-collection-name: Sustainable Facilities Tool API
x-complete: 0
info:
  title: Sustainable Facilities Tool API Workspace
  description: Returns a workspace by parameter.
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
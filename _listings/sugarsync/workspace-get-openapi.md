---
swagger: "2.0"
x-collection-name: SugarSync
x-complete: 0
info:
  title: Sugar Sync  API Retrieving Workspace Information
  description: To retrieve information about a workspace, an application submits an
    HTTP GET request to then          workspace resource that represents the workspace.
  version: "1"
host: api.sugarsync.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workspace:
    get:
      summary: Retrieving Workspace Information
      description: To retrieve information about a workspace, an application submits
        an HTTP GET request to then          workspace resource that represents the
        workspace.
      operationId: retrieving-workspace-information
      x-api-path-slug: workspace-get
      responses:
        200:
          description: OK
      tags:
      - Workspace
  /workspace/:
    get:
      summary: Retrieving Workspace Contents
      description: To retrieve the contents of a workspace, an application submits
        an HTTP GET request to the URLn          that represents the workspace contents.
        Note that the contents of a workspace are the sync folders that are mappedntt  to
        that workspace in SugarSync.
      operationId: retrieving-workspace-contents
      x-api-path-slug: workspace-get
      parameters:
      - in: query
        name: max
        description: Positive integer
      - in: query
        name: order
        description: name, last_modified, size, or extension
      - in: query
        name: start
        description: 0 or positive integer
      - in: query
        name: type
        description: Must be specified with a value of folder when retrieving folders
          from a parent folder
      responses:
        200:
          description: OK
      tags:
      - Workspace
    put:
      summary: Updating Workspace Information
      description: An application can update attributes of a workspace by issuing
        an HTTP PUT request to the URL that representsnthe workspace resource. In
        addition, the app needs to provide as input, XML that identifies the new attribute
        values for the workspace.nUpon receiving the PUT request, the SugarSync service
        examines the input and updates any of the attributes that have been modified.
      operationId: updating-workspace-information
      x-api-path-slug: workspace-put
      parameters:
      - in: header
        name: Authorization
        description: The access token
      - in: header
        name: Content-Length
        description: The length of the request body
      - in: header
        name: Content-Type
        description: The content type and character encoding of the response
      - in: header
        name: Host
        description: The domain name of the server
      - in: header
        name: User-Agent
        description: The client application implementing the network protocol for
          communication between          the client and server
      responses:
        200:
          description: OK
      tags:
      - Workspace
x-streamrank:
  polling_total_time_average: "0"
  polling_size_download_average: "0"
  streaming_total_time_average: "0"
  streaming_size_download_average: "0"
  change_yes: "0"
  change_no: "0"
  time_percentage: "0"
  size_percentage: "0"
  change_percentage: "200"
  last_run: ~
  days_run: "0"
  minute_run: "0"
---
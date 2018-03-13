---
swagger: "2.0"
info:
  title: AWS WorkSpaces Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeWorkspaces&k=1:
    get:
      summary: ' Describe Workspaces '
      description: Obtains information about the specified WorkSpaces
      operationId: describeWorkspaces
      parameters:
      - in: query
        name: BundleId
        description: The identifier of a bundle to obtain the WorkSpaces for
        type: string
      - in: query
        name: DirectoryId
        description: Specifies the directory identifier to which to limit the WorkSpaces
        type: string
      - in: query
        name: Limit
        description: The maximum number of items to return
        type: string
      - in: query
        name: NextToken
        description: The NextToken value from a previous call to this operation
        type: string
      - in: query
        name: UserName
        description: Used with the DirectoryId parameter to specify the directory
          user for whom to         obtain the WorkSpace
        type: string
      - in: query
        name: WorkspaceIds
        description: An array of strings that contain the identifiers of the WorkSpaces
          for which to retrieve information
        type: string
      responses:
        200:
          description: OK
      tags:
      - workspaces
definitions: []
x-collection-name: AWS WorkSpaces
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
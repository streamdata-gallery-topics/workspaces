---
name: Sustainable Facilities Tool API
x-slug: sustainable-facilities-tool-api
description: Our core API allows developers to interact with the Sustainable Facilities
  Tool programmatically. Its designed for public use and to be easily integrated into
  other applications.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Workspaces
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/sustainable-facilities-tool-api/apis.md
specificationVersion: "0.14"
apis:
- name: Sustainable Facilities Tool API Workspaces
  x-api-slug: sustainable-facilities-tool-api
  description: Returns all workspaces.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///workspaces
  tags: Workspaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/sustainable-facilities-tool-api/workspaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/sustainable-facilities-tool-api/workspaces-get-openapi.md
- name: Sustainable Facilities Tool API Workspace
  x-api-slug: sustainable-facilities-tool-api
  description: Returns a workspace by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///workspaces/{parameter}
  tags: Workspaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/sustainable-facilities-tool-api/workspacesparameter-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/sustainable-facilities-tool-api/workspacesparameter-get-openapi.md
- name: Sustainable Facilities Tool API Workspaces
  x-api-slug: sustainable-facilities-tool-api
  description: Returns material groups for the workspace selected by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///workspaces/{parameter}/material-groups
  tags: Workspaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/sustainable-facilities-tool-api/workspacesparametermaterialgroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/sustainable-facilities-tool-api/workspacesparametermaterialgroups-get-openapi.md
- name: Sustainable Facilities Tool API Workspace Materials
  x-api-slug: sustainable-facilities-tool-api
  description: Returns materials for the workspace selected by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///workspaces/{parameter}/materials
  tags: Workspaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/sustainable-facilities-tool-api/workspacesparametermaterials-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/sustainable-facilities-tool-api/workspacesparametermaterials-get-openapi.md
- name: Sustainable Facilities Tool API
  x-api-slug: sustainable-facilities-tool-api
  description: Our core API allows developers to interact with the Sustainable Facilities
    Tool programmatically. Its designed for public use and to be easily integrated
    into other applications.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1/
  tags: Workspaces
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/sustainable-facilities-tool-api/openapi.md
x-common:
- type: x-developer
  url: https://sftool.gov/developers
- type: x-terms-of-service
  url: https://sftool.gov/developer/terms-of-use
- type: x-twitter
  url: https://twitter.com/sftool
- type: x-website
  url: https://sftool.gov/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
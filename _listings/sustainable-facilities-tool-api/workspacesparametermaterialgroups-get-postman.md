{
  "info": {
    "name": "Sustainable Facilities Tool API Workspaces",
    "_postman_id": "7e1a0579-a9da-49b1-9008-a3ba6290378e",
    "description": "Returns material groups for the workspace selected by parameter.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "workspaces",
      "item": [
        {
          "id": "080d913e-b2b6-4e7c-a9ac-047d9e13674f",
          "name": "getWorkspaceMaterialGroups",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "sftool",
                "v1",
                "workspaces/:parameter/material-groups"
              ],
              "variable": [
                {
                  "id": "parameter",
                  "value": "parameter",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns material groups for the workspace selected by parameter"
          },
          "response": [
            {
              "header": [
                {
                  "key": "Content-Type",
                  "value": "application/json",
                  "disabled": false
                }
              ],
              "body": "[\r\n  {\r\n    \"id\": \"id\",\r\n    \"name\": \"name\"\r\n  }\r\n]",
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "9edcf01e-b127-4524-9e6d-ffef30e51d88"
            }
          ]
        }
      ]
    }
  ]
}
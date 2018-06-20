{
  "info": {
    "name": "Sustainable Facilities Tool API Workspace",
    "_postman_id": "a107cfee-c975-42a8-bcc4-e79093b56749",
    "description": "Returns a workspace by parameter.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "workspaces",
      "item": [
        {
          "id": "816f85bf-7c31-45a6-a716-287ab13d9b0c",
          "name": "getWorkspace",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "sftool",
                "v1",
                "workspaces/:parameter"
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
            "description": "Returns a workspace by parameter"
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
              "id": "7d2534f1-0907-4364-9c9e-3ec0f149bdc2"
            }
          ]
        }
      ]
    }
  ]
}
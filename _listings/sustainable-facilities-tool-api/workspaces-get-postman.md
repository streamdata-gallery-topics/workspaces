{
  "info": {
    "name": "Sustainable Facilities Tool API Workspaces",
    "_postman_id": "ee74689b-9dd2-4950-b3b7-f81225171de5",
    "description": "Returns all workspaces.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "workspaces",
      "item": [
        {
          "id": "aab0784d-8945-400f-a132-3a0b8916a42d",
          "name": "getWorkspaces",
          "request": {
            "url": "http://api.data.gov/sftool/v1/workspaces",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all workspaces"
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
              "id": "16af9709-47f3-4bdd-93cd-90dcdfb7a5d2"
            }
          ]
        }
      ]
    }
  ]
}
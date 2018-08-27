{
  "info": {
    "name": "DevTestLabsClient",
    "_postman_id": "2152a692-578e-4201-a50a-5ab4a1392868",
    "description": "The DevTest Labs Client.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "artifacts",
      "item": [
        {
          "id": "1c3795ce-bdf8-4294-8ef2-6763dad7da0b",
          "name": "Artifacts_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.DevTestLab/labs/:labName/artifactsources/:artifactSourceName/artifacts/:name"
              ],
              "query": [
                {
                  "key": "$expand",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "artifactSourceName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "labName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "name",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "resourceGroupName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get artifact"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1693d79e-cb0e-47fa-b893-24dbc167ccc5"
            }
          ]
        }
      ]
    }
  ]
}
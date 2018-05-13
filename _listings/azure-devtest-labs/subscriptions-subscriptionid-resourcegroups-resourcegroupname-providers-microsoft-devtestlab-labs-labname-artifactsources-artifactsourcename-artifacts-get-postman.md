{
  "info": {
    "name": "DevTestLabsClient",
    "_postman_id": "f77421c2-9c4c-4bca-ae35-9d33ed50c202",
    "description": "The DevTest Labs Client.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "artifacts",
      "item": [
        {
          "id": "28fa916b-97fc-4388-b438-58c2185e20fb",
          "name": "Artifacts_List",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.DevTestLab/labs/:labName/artifactsources/:artifactSourceName/artifacts"
              ],
              "query": [
                {
                  "key": "$expand",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "$filter",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "$orderby",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "$top",
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
            "description": "List artifacts in a given artifact source"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8564e37d-bdc5-4453-88b1-f8f584115ef0"
            }
          ]
        }
      ]
    }
  ]
}
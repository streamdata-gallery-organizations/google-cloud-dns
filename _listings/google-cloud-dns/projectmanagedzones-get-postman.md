{
  "info": {
    "name": "Google Cloud DNS API Get Managed Zones",
    "_postman_id": "f798ea8a-b771-46dc-b838-305a38c46d18",
    "description": "Enumerate ManagedZones that have been created but not yet deleted.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Project",
      "item": [
        {
          "id": "5616364f-1286-424f-a2a2-a4da65399ba1",
          "name": "dns.projects.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "dns",
                "v1",
                "projects",
                ":project"
              ],
              "variable": [
                {
                  "id": "project",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Fetch the representation of an existing Project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f70371ef-3105-41b0-b7eb-e6b79f5b1358"
            }
          ]
        }
      ]
    },
    {
      "name": "Managed Zone",
      "item": [
        {
          "id": "978bdae6-7f39-4695-8e6b-8bc64a2d0a7a",
          "name": "dns.managedZones.list",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "dns",
                "v1",
                "projects",
                ":project/managedZones"
              ],
              "query": [
                {
                  "key": "dnsName",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "maxResults",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pageToken",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "project",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enumerate ManagedZones that have been created but not yet deleted."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef561b46-eb42-4127-9d4a-3dabb870b33d"
            }
          ]
        }
      ]
    }
  ]
}
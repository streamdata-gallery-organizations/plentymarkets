{
  "info": {
    "name": "Plentymarkets Logout",
    "_postman_id": "d1a51e18-7fec-49d4-ab5d-06374286ab25",
    "description": "Logs out the back end user from plentymarkets. The access token expires.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Logout",
      "item": [
        {
          "id": "008e4a26-0017-47c9-8870-182649ce2b86",
          "name": "postRestAccountLogout",
          "request": {
            "url": "http://example.com/rest/account/logout",
            "method": "POST",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Logs out the front end user from the online store. The access token expires."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d99f5b90-0105-4e0e-b971-ab31c0de3d57"
            }
          ]
        },
        {
          "id": "6384ad0b-f6a5-4b6d-a5c8-738f1de06a7f",
          "name": "postRestLogout",
          "request": {
            "url": "http://example.com/rest/logout",
            "method": "POST",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Logs out the back end user from plentymarkets. The access token expires."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4684a9b2-4ca7-48f6-9536-20ba76df8f6b"
            }
          ]
        }
      ]
    }
  ]
}
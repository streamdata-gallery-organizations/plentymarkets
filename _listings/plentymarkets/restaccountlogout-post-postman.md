{
  "info": {
    "name": "Plentymarkets Logout",
    "_postman_id": "eb068b09-65a4-40c0-b152-239b15e31e91",
    "description": "Logs out the front end user from the online store. The access token expires.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Logout",
      "item": [
        {
          "id": "7a3cb140-158e-4dc0-bf8e-a6daad64be1e",
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
              "id": "12cf3519-8b0a-4f7e-ac1e-14a80286b6e7"
            }
          ]
        }
      ]
    }
  ]
}
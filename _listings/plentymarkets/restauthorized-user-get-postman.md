{
  "info": {
    "name": "Plentymarkets Get authorized user",
    "_postman_id": "7d12f706-2e8e-4235-bd38-6fade500b825",
    "description": "Gets an authorized user. This call returns a JSON object with information about the user after login. This information is used for correctly displaying the plentymarkets back end.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Authorized",
      "item": [
        {
          "id": "de5bf030-11a0-4142-833e-12e3c3788972",
          "name": "getRestAuthorizedUser",
          "request": {
            "url": "http://example.com/rest/authorized_user",
            "method": "GET",
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
            "description": "Gets an authorized user. This call returns a JSON object with information about the user after login. This information is used for correctly displaying the plentymarkets back end."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b148b423-40e2-492b-9256-53d10ac0a3a6"
            }
          ]
        }
      ]
    }
  ]
}
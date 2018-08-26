{
  "info": {
    "name": "Plentymarkets Get authorized user with UiConfig",
    "_postman_id": "ad27277a-7fb0-4f87-adee-9bede1abc623",
    "description": "Gets an authorized user with UiConfig. This call returns a JSON object with information about the user after login. This information is used for correctly displaying the plentymarkets back end.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Authorized",
      "item": [
        {
          "id": "026ab360-65da-4672-b7a8-abc3617342e2",
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
              "id": "ff75219a-b14c-4ffb-adf6-738fc378d281"
            }
          ]
        },
        {
          "id": "0781350d-f27e-4f94-9bf5-87c7f66eb543",
          "name": "getRestUserAuthorizedUserWithUiConfig",
          "request": {
            "url": "http://example.com/rest/user/authorized_user_with_ui_config",
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
            "description": "Gets an authorized user with UiConfig. This call returns a JSON object with information about the user after login. This information is used for correctly displaying the plentymarkets back end."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2b4e6937-195b-4bd7-b4bf-453ad61f364f"
            }
          ]
        }
      ]
    }
  ]
}
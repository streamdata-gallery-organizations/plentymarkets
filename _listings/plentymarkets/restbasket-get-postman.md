{
  "info": {
    "name": "Plentymarkets Get basket",
    "_postman_id": "44dd0e8a-45ba-441c-a2d3-743604dccd33",
    "description": "Gets the shopping cart for the current customer session.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Basket",
      "item": [
        {
          "id": "a9d7c380-d4c7-4287-b13f-16b7fc545b2d",
          "name": "getRestBasket",
          "request": {
            "url": "http://example.com/rest/basket",
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
            "description": "Gets the shopping cart for the current customer session."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8d353431-f605-44ed-9768-8fd08ad70d13"
            }
          ]
        }
      ]
    }
  ]
}
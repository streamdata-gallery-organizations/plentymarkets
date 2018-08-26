{
  "info": {
    "name": "Plentymarkets Get a preview list for parcel service presets.",
    "_postman_id": "3db2fed1-19a9-4fdd-b0fe-511f9ab21471",
    "description": "Get a preview list for parcel service presets..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Preview",
      "item": [
        {
          "id": "2267c3e6-372d-4f7c-bb08-e8f26cfe47e3",
          "name": "getRestListingsOptionTemplatesPreview",
          "request": {
            "url": "http://example.com/rest/listings/option_templates/preview",
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
            "description": "Gets a preview list of all available listing option templates."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2aaa0c1d-07c6-4598-8614-62113dc2af88"
            }
          ]
        },
        {
          "id": "c60958c4-0ed7-4387-9b8f-5ed1773b7dad",
          "name": "getRestOrdersShippingParcelsPreviewLanguage",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/orders/shipping/parcels/preview/:language?"
              ],
              "query": [
                {
                  "key": "language",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "language?",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
            "description": "Get a preview list for parcel services.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8db0b32b-65e9-47fc-a094-640954d420f5"
            }
          ]
        },
        {
          "id": "bed013c1-be01-47ed-b4ad-9c5b2b7b360b",
          "name": "getRestOrdersShippingPresetsPreviewLanguage",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/orders/shipping/presets/preview/:language?"
              ],
              "query": [
                {
                  "key": "language",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "language?",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
            "description": "Get a preview list for parcel service presets.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "651c4a61-cb19-4482-9884-0f25aac568be"
            }
          ]
        }
      ]
    }
  ]
}
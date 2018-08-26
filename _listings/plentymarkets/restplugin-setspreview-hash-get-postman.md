{
  "info": {
    "name": "Plentymarkets Get the preview hash for a set",
    "_postman_id": "7b426813-6d6e-4edf-aaf6-ecb1c662698a",
    "description": "Get the hash required to preview a plugin set. Response content will be in the form ['previewHash' => 'adf245o9nwu90sdfjw409u4'].",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Preview",
      "item": [
        {
          "id": "4087fbcc-7596-4dbc-8041-a3a08d427978",
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
              "id": "ee7073a3-3442-4fe5-b982-d19b18f646e4"
            }
          ]
        },
        {
          "id": "8d885e32-434f-435d-826d-984b812ea5a7",
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
              "id": "aab17b9a-048a-4296-b1e5-3308beee6a77"
            }
          ]
        },
        {
          "id": "3a180545-bd54-490f-a552-27135aed0479",
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
              "id": "f5342101-d0f0-4e0e-b9e2-47fcefc36147"
            }
          ]
        },
        {
          "id": "78b2f5ff-9a9b-4106-ada1-93e96651e84e",
          "name": "getRestPaymentsMethodsPreviewLanguage",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/payments/methods/preview/:language?"
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
              "id": "d3cca8e2-6985-40ae-9612-ff8d191726bc"
            }
          ]
        },
        {
          "id": "cceb60a8-a433-4d6a-89f4-03f56357dd24",
          "name": "getRestPluginSetsPreviewHash",
          "request": {
            "url": "http://example.com/rest/plugin_sets/preview_hash",
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
            "description": "Get the hash required to preview a plugin set. Response content will be in the form ['previewHash' => 'adf245o9nwu90sdfjw409u4']."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "74e158e3-c13c-4864-97cc-d1a2ae6c0725"
            }
          ]
        }
      ]
    }
  ]
}
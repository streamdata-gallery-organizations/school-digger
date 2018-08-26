{
  "info": {
    "name": "School Digger API V1 Returns a detailed record for one district",
    "_postman_id": "46e758e1-911b-40ed-a2c5-87fc754b8433",
    "description": "Retrieve a single district record from the SchoolDigger database",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "91e1c01d-91fa-4296-ad96-7f9bfc39ce06",
      "name": "Districts_GetAllDistricts",
      "request": {
        "url": "http://api.schooldigger.com/v1/districts?appID=%7B%7D&appKey=%7B%7D&boundaryAddress=%7B%7D&boxLatitudeNW=%7B%7D&boxLatitudeSE=%7B%7D&boxLongitudeNW=%7B%7D&boxLongitudeSE=%7B%7D&city=%7B%7D&distanceMiles=%7B%7D&isInBoundaryOnly=%7B%7D&nearLatitude=%7B%7D&nearLongitude=%7B%7D&page=%7B%7D&perPage=%7B%7D&q=%7B%7D&sortBy=%7B%7D&st=%7B%7D&zip=%7B%7D",
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
        "description": "Search the SchoolDigger database for districts. You may use any combination of criteria as query parameters."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "51d292b7-b5fc-4b81-9ab6-dfd24d61fb40"
        }
      ]
    },
    {
      "id": "35a1e403-c328-4f8b-ae83-d532f10b7e02",
      "name": "Districts_GetDistrict",
      "request": {
        "url": {
          "protocol": "http",
          "host": "api.schooldigger.com",
          "path": [
            "v1/districts/:id"
          ],
          "query": [
            {
              "key": "appID",
              "value": "%7B%7D",
              "disabled": false
            },
            {
              "key": "appKey",
              "value": "%7B%7D",
              "disabled": false
            }
          ],
          "variable": [
            {
              "id": "id",
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
        "description": "Retrieve a single district record from the SchoolDigger database"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "355ac97e-6bda-4da4-9752-e6c15d79aab4"
        }
      ]
    }
  ]
}
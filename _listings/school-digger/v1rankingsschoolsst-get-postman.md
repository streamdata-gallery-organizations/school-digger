{
  "info": {
    "name": "School Digger API V1 Returns a SchoolDigger school ranking list",
    "_postman_id": "5bcd162c-e6c5-4cbc-b5f5-7fa99b12f516",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "0e1127ce-0647-4daf-acab-adee960e7bc4",
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
          "id": "baba95fc-46db-42a6-8acd-367f4bb6646f"
        }
      ]
    },
    {
      "id": "1d258a5c-81a8-4a00-a960-8c24540c5d12",
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
          "id": "ab416433-5789-4095-a2e1-52dfb586526f"
        }
      ]
    },
    {
      "id": "d6b0d2e6-86ed-4c30-8c08-8f20a5a9527b",
      "name": "v1.rankings.districts.st.get",
      "request": {
        "url": {
          "protocol": "http",
          "host": "api.schooldigger.com",
          "path": [
            "v1/rankings/districts/:st"
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
            },
            {
              "key": "page",
              "value": "%7B%7D",
              "disabled": false
            },
            {
              "key": "perPage",
              "value": "%7B%7D",
              "disabled": false
            },
            {
              "key": "year",
              "value": "%7B%7D",
              "disabled": false
            }
          ],
          "variable": [
            {
              "id": "st",
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
        "description": "Returns a SchoolDigger district ranking list"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "f7f8c606-77cb-47c3-b501-f85e38226ea4"
        }
      ]
    },
    {
      "id": "2d165df9-ea60-4796-8f47-cbc8148fc320",
      "name": "v1.rankings.schools.st.get",
      "request": {
        "url": {
          "protocol": "http",
          "host": "api.schooldigger.com",
          "path": [
            "v1/rankings/schools/:st"
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
            },
            {
              "key": "level",
              "value": "%7B%7D",
              "disabled": false
            },
            {
              "key": "page",
              "value": "%7B%7D",
              "disabled": false
            },
            {
              "key": "perPage",
              "value": "%7B%7D",
              "disabled": false
            },
            {
              "key": "year",
              "value": "%7B%7D",
              "disabled": false
            }
          ],
          "variable": [
            {
              "id": "st",
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
        "description": "Returns a SchoolDigger school ranking list"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "5d5ad8a9-28f9-4baf-ae31-0ce72fb509ed"
        }
      ]
    }
  ]
}
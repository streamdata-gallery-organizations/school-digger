{
  "info": {
    "name": "School Digger API V1 Returns a list of schools",
    "_postman_id": "e147cd4d-c923-4347-b9a4-87007013c9a3",
    "description": "Search the SchoolDigger database for schools. You may use any combination of criteria as query parameters.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "c434fc45-29c8-4f73-8e57-bf9c97e19948",
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
          "id": "623fdda7-39c6-4c54-9f9d-e914bfaf6f31"
        }
      ]
    },
    {
      "id": "0d79d93b-f388-4d74-b5fc-24f6745ba2b2",
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
          "id": "5d68bcfa-e351-4350-b6b2-4f04b6a2fa4a"
        }
      ]
    },
    {
      "id": "ca9a7f49-2fd3-48d9-82ba-5da6e7c2c864",
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
          "id": "ade5ab45-9d59-4c8b-a738-2d8ba3a2694e"
        }
      ]
    },
    {
      "id": "b5ae0d65-be95-4fbf-b3bc-48913a13e37a",
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
          "id": "771019d9-17f4-4b9f-8eb9-7f54b00f7460"
        }
      ]
    },
    {
      "id": "843856ad-f7f2-4360-a1c4-4d517fa99882",
      "name": "Schools_GetAllSchools",
      "request": {
        "url": "http://api.schooldigger.com/v1/schools?appID=%7B%7D&appKey=%7B%7D&boundaryAddress=%7B%7D&boxLatitudeNW=%7B%7D&boxLatitudeSE=%7B%7D&boxLongitudeNW=%7B%7D&boxLongitudeSE=%7B%7D&city=%7B%7D&distanceMiles=%7B%7D&districtID=%7B%7D&isCharter=%7B%7D&isInBoundaryOnly=%7B%7D&isMagnet=%7B%7D&isTitleI=%7B%7D&isTitleISchoolwide=%7B%7D&isVirtual=%7B%7D&level=%7B%7D&nearLatitude=%7B%7D&nearLongitude=%7B%7D&page=%7B%7D&perPage=%7B%7D&q=%7B%7D&sortBy=%7B%7D&st=%7B%7D&zip=%7B%7D",
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
        "description": "Search the SchoolDigger database for schools. You may use any combination of criteria as query parameters."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "659ec9e9-93dc-4894-986d-6ddc66a4b81e"
        }
      ]
    }
  ]
}
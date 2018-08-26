{
  "info": {
    "name": "School Digger API V1 Returns a list of districts",
    "_postman_id": "6c3e1f0b-bf3f-4ac6-8c71-76cdba8412c6",
    "description": "Search the SchoolDigger database for districts. You may use any combination of criteria as query parameters.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "085ef541-e63a-40aa-a7cc-b5d0ba450210",
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
          "id": "465a756d-41e3-4969-8f0a-e797e5db4f47"
        }
      ]
    }
  ]
}
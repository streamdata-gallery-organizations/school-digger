---
swagger: "2.0"
x-collection-name: School Digger
x-complete: 0
info:
  title: School Digger API V1 Returns a detailed record for one district
  description: Retrieve a single district record from the SchoolDigger database
  termsOfService: https://developer.schooldigger.com/termsofservice
  contact:
    name: SchoolDigger
    email: api@schooldigger.com
  version: v1
host: api.schooldigger.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/districts:
    get:
      summary: Returns a list of districts
      description: Search the SchoolDigger database for districts. You may use any
        combination of criteria as query parameters.
      operationId: Districts_GetAllDistricts
      x-api-path-slug: v1districts-get
      parameters:
      - in: query
        name: appID
        description: Your API app id
      - in: query
        name: appKey
        description: Your API app key
      - in: query
        name: boundaryAddress
        description: Full U
      - in: query
        name: boxLatitudeNW
        description: Search for districts within a box defined by (BoxLatitudeNW/BoxLongitudeNW)
          to (BoxLongitudeSE/BoxLatitudeSE) (optional)
      - in: query
        name: boxLatitudeSE
        description: Search for districts within a box defined by (BoxLatitudeNW/BoxLongitudeNW)
          to (BoxLongitudeSE/BoxLatitudeSE) (optional)
      - in: query
        name: boxLongitudeNW
        description: Search for districts within a box defined by (BoxLatitudeNW/BoxLongitudeNW)
          to (BoxLongitudeSE/BoxLatitudeSE) (optional)
      - in: query
        name: boxLongitudeSE
        description: Search for districts within a box defined by (BoxLatitudeNW/BoxLongitudeNW)
          to (BoxLongitudeSE/BoxLatitudeSE) (optional)
      - in: query
        name: city
        description: Search for districts in this city (optional)
      - in: query
        name: distanceMiles
        description: Search for districts within (distanceMiles) of (nearLatitude)/(nearLongitude)
          (Default 5 miles) (optional) (Pro, Enterprise API levels only)
      - in: query
        name: isInBoundaryOnly
        description: Return only the districts that include given location (nearLatitdue/nearLongitude)
          or (nearAddress) in its attendance boundary (Enterprise API level only)
      - in: query
        name: nearLatitude
        description: Search for districts within (distanceMiles) of (nearLatitude)/(nearLongitude)
          (e
      - in: query
        name: nearLongitude
        description: Search for districts within (distanceMiles) of (nearLatitude)/(nearLongitude)
          (e
      - in: query
        name: page
        description: 'Page number to retrieve (optional, default: 1)'
      - in: query
        name: perPage
        description: 'Number of districts to retrieve on a page (50 max) (optional,
          default: 10)'
      - in: query
        name: q
        description: 'Search term - note: will match district name or city (optional)'
      - in: query
        name: sortBy
        description: Sort list
      - in: query
        name: st
        description: Two character state (e
      - in: query
        name: zip
        description: Search for districts in this 5-digit zip code (optional)
      responses:
        200:
          description: OK
      tags:
      - ""
  /v1/districts/{id}:
    get:
      summary: Returns a detailed record for one district
      description: Retrieve a single district record from the SchoolDigger database
      operationId: Districts_GetDistrict
      x-api-path-slug: v1districtsid-get
      parameters:
      - in: query
        name: appID
        description: Your API app id
      - in: query
        name: appKey
        description: Your API app key
      - in: path
        name: id
        description: The 7 digit District ID (e
      responses:
        200:
          description: OK
      tags:
      - ""
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
---
name: School Digger
x-slug: school-digger
description: Start your search for a great school at SchoolDigger.com! We have test
  scores, rankings, school and district boundaries, student/teacher ratios, ethnic
  makeup, and scores of other useful metrics and information for over 120,000 elementary,
  middle, and high schools in the United States!
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/schooldigger.png
x-kinRank: "7"
x-alexaRank: "0"
tags: School Digger
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/school-digger/master/_listings/school-digger/apis.md
specificationVersion: "0.14"
apis:
- name: School Digger API V1 - Returns a list of districts
  x-api-slug: v1districts-get
  description: Search the SchoolDigger database for districts. You may use any combination
    of criteria as query parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/schooldigger.png
  humanURL: http://schooldigger.com
  baseURL: https://api.schooldigger.com//
  tags: Schools, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/school-digger/master/_listings/school-digger/v1districts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/school-digger/master/_listings/school-digger/v1districts-get-openapi.md
- name: School Digger API V1 - Returns a detailed record for one district
  x-api-slug: v1districtsid-get
  description: Retrieve a single district record from the SchoolDigger database
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/schooldigger.png
  humanURL: http://schooldigger.com
  baseURL: https://api.schooldigger.com//
  tags: Schools, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/school-digger/master/_listings/school-digger/v1districtsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/school-digger/master/_listings/school-digger/v1districtsid-get-openapi.md
- name: School Digger API V1 - Returns a SchoolDigger district ranking list
  x-api-slug: v1rankingsdistrictsst-get
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/schooldigger.png
  humanURL: http://schooldigger.com
  baseURL: https://api.schooldigger.com//
  tags: Schools, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/school-digger/master/_listings/school-digger/v1rankingsdistrictsst-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/school-digger/master/_listings/school-digger/v1rankingsdistrictsst-get-openapi.md
- name: School Digger API V1 - Returns a SchoolDigger school ranking list
  x-api-slug: v1rankingsschoolsst-get
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/schooldigger.png
  humanURL: http://schooldigger.com
  baseURL: https://api.schooldigger.com//
  tags: Schools, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/school-digger/master/_listings/school-digger/v1rankingsschoolsst-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/school-digger/master/_listings/school-digger/v1rankingsschoolsst-get-openapi.md
- name: School Digger API V1 - Returns a list of schools
  x-api-slug: v1schools-get
  description: Search the SchoolDigger database for schools. You may use any combination
    of criteria as query parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/schooldigger.png
  humanURL: http://schooldigger.com
  baseURL: https://api.schooldigger.com//
  tags: Schools, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/school-digger/master/_listings/school-digger/v1schools-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/school-digger/master/_listings/school-digger/v1schools-get-openapi.md
- name: School Digger API V1 - Returns a detailed record for one school
  x-api-slug: v1schoolsid-get
  description: Retrieve a school record from the SchoolDigger database
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/schooldigger.png
  humanURL: http://schooldigger.com
  baseURL: https://api.schooldigger.com//
  tags: Schools, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/school-digger/master/_listings/school-digger/v1schoolsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/school-digger/master/_listings/school-digger/v1schoolsid-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://sap.api.gallery.streamdata.io
- type: x-api-stack
  url: http://school.digger.stack.network
- type: x-change-log
  url: https://developer.schooldigger.com/changelog
- type: x-developer
  url: https://developer.schooldigger.com/?r=schooldigger
- type: x-documentation
  url: https://developer.schooldigger.com/docs
- type: x-website
  url: http://schooldigger.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
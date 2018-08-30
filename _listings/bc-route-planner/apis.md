---
name: BC Route Planner
x-slug: bc-route-planner
description: The BC Route Planner is a REST web service that offers vehicle route
  plans that are based on the BC Digital Road Atlas (DRA). The BC Route Planner computes
  the shortest or fastest route between start and end points and returns the route,
  distance, time, and directions.
image: ""
x-kinRank: "7"
x-alexaRank: "0"
tags: BC Route Planner
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bc-route-planner/master/_listings/bc-route-planner/apis.md
specificationVersion: "0.14"
apis:
- name: BC Route Planner - Get the directions, path, distance and travel time between
    a series of geographic points
  x-api-slug: directions-outputformat-get
  description: Represents the turn-by-turn directions, geometry, distance, and time
    of the shortest path or fastest path between given start and end points
  image: ""
  humanURL: https://catalogue.data.gov.bc.ca/dataset/bc-route-planner
  baseURL: https://router.api.gov.bc.ca//
  tags: Locations, Routes, API Provider, Profiles, Routes, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bc-route-planner/master/_listings/bc-route-planner/directions-outputformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bc-route-planner/master/_listings/bc-route-planner/directions-outputformat-get-openapi.md
- name: BC Route Planner - Get distance and travel time between two geographic points
  x-api-slug: distance-outputformat-get
  description: Represents the distance and time of the shortest or fastest path between
    given start and end points.
  image: ""
  humanURL: https://catalogue.data.gov.bc.ca/dataset/bc-route-planner
  baseURL: https://router.api.gov.bc.ca//
  tags: Locations, Routes, API Provider, Profiles, Routes, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bc-route-planner/master/_listings/bc-route-planner/distance-outputformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bc-route-planner/master/_listings/bc-route-planner/distance-outputformat-get-openapi.md
- name: BC Route Planner - Get distance and travel time between each pair of geographic
    points
  x-api-slug: distancebetweenpairs-outputformat-get
  description: Represents the distance and time of the shortest or fastest paths between
    all pairs of fromPoints and toPoints. The number of fromPoints times the number
    of toPoints should not exceed 100 or the request will time out.
  image: ""
  humanURL: https://catalogue.data.gov.bc.ca/dataset/bc-route-planner
  baseURL: https://router.api.gov.bc.ca//
  tags: Locations, Routes, API Provider, Profiles, Routes, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bc-route-planner/master/_listings/bc-route-planner/distancebetweenpairs-outputformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bc-route-planner/master/_listings/bc-route-planner/distancebetweenpairs-outputformat-get-openapi.md
- name: BC Route Planner - Get the path, distance and travel time between a series
    of geographic points
  x-api-slug: route-outputformat-get
  description: Represents the geometry, distance, and time of the shortest or fastest
    path between given start and end points.
  image: ""
  humanURL: https://catalogue.data.gov.bc.ca/dataset/bc-route-planner
  baseURL: https://router.api.gov.bc.ca//
  tags: Locations, Routes, API Provider, Profiles, Routes, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bc-route-planner/master/_listings/bc-route-planner/route-outputformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bc-route-planner/master/_listings/bc-route-planner/route-outputformat-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://bc.laws.api.gallery.streamdata.io
- type: x-api-stack
  url: http://bc.route.planner.stack.network
- type: x-website
  url: https://catalogue.data.gov.bc.ca/dataset/bc-route-planner
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
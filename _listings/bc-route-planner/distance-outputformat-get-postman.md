{
  "info": {
    "name": "BC Route Planner Get distance and travel time between two geographic points",
    "_postman_id": "06763a00-6b69-4330-9d04-0c7112caba95",
    "description": "Represents the distance and time of the shortest or fastest path between given start and end points.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Directions",
      "item": [
        {
          "id": "16fb8617-4224-48f2-b75f-ac711e5d5964",
          "name": "represents-the-turnbyturn-directions-geometry-distance-and-time-of-the-shortest-path-or-fastest-path",
          "request": {
            "url": {
              "protocol": "http",
              "host": "router.api.gov.bc.ca",
              "path": [
                "directions.:outputFormat"
              ],
              "query": [
                {
                  "key": "criteria",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "distanceUnit",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "outputSRS",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "points",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "routeDescription",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "outputFormat",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Represents the turn-by-turn directions, geometry, distance, and time of the shortest path or fastest path between given start and end points"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5cc6b90e-6426-4d17-9bb0-e4be1e42188b"
            }
          ]
        }
      ]
    },
    {
      "name": "Distance",
      "item": [
        {
          "id": "d1b05e72-96d4-41f3-8f03-5f53023e922f",
          "name": "represents-the-distance-and-time-of-the-shortest-or-fastest-path-between-given-start-and-end-points-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "router.api.gov.bc.ca",
              "path": [
                "distance.:outputFormat"
              ],
              "query": [
                {
                  "key": "criteria",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "distanceUnit",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "outputSRS",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "points",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "routeDescription",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "outputFormat",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Represents the distance and time of the shortest or fastest path between given start and end points."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a473d69-3770-483c-b490-bab99ca93d97"
            }
          ]
        }
      ]
    }
  ]
}
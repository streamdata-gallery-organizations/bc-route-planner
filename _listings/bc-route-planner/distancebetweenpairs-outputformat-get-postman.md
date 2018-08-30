{
  "info": {
    "name": "BC Route Planner Get distance and travel time between each pair of geographic points",
    "_postman_id": "c8c96b5c-410d-4d19-93f1-6b49fc68cd2b",
    "description": "Represents the distance and time of the shortest or fastest paths between all pairs of fromPoints and toPoints. The number of fromPoints times the number of toPoints should not exceed 100 or the request will time out.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Directions",
      "item": [
        {
          "id": "b10676d5-44fc-4254-bfde-dc3f3ffa9b16",
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
              "id": "169895fa-054f-4ed7-b9d5-243650fb0053"
            }
          ]
        }
      ]
    },
    {
      "name": "Distance",
      "item": [
        {
          "id": "6fe3fb5f-6665-4bc5-8208-0b773bc51355",
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
              "id": "06a5190c-a9e1-4e40-b401-0e11b1601b50"
            }
          ]
        },
        {
          "id": "8b1566ea-74ff-4086-a6ac-9fcf19f1d5a7",
          "name": "represents-the-distance-and-time-of-the-shortest-or-fastest-paths-between-all-pairs-of-frompoints-an",
          "request": {
            "url": {
              "protocol": "http",
              "host": "router.api.gov.bc.ca",
              "path": [
                "distance/betweenPairs.:outputFormat"
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
                  "key": "fromPoints",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "outputSRS",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "routeDescription",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "toPoints",
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
            "description": "Represents the distance and time of the shortest or fastest paths between all pairs of fromPoints and toPoints. The number of fromPoints times the number of toPoints should not exceed 100 or the request will time out."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "14a703f7-6cf4-400c-be6f-0d22244d5527"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "Giphy Gif API Get GIF by Id",
    "_postman_id": "7ac39a88-39e6-48e2-900f-bbec0f508a7a",
    "description": "Returns a GIF given that GIF's unique ID",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Gifs",
      "item": [
        {
          "id": "dc50d415-ffb8-4a65-a67a-4d75b99628eb",
          "name": "getGifsById",
          "request": {
            "url": "http://api.giphy.com/v1/gifs?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "A multiget version of the get GIF by ID endpoint."
          },
          "response": [
            {
              "code": 200,
              "name": "Response_200",
              "id": "b59d2793-1514-4457-991f-703d4feb0dec"
            }
          ]
        },
        {
          "id": "b5fbb375-ecf6-4b96-9ce6-af792b772174",
          "name": "randomGif",
          "request": {
            "url": "http://api.giphy.com/v1/gifs/random?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a random GIF, limited by tag. Excluding the tag parameter will return a random GIF from the GIPHY catalog."
          },
          "response": [
            {
              "code": 200,
              "name": "Response_200",
              "id": "b95d2a35-24b6-4a59-be09-97d8344809c5"
            }
          ]
        },
        {
          "id": "e1236175-e9ad-4890-b3b7-65535b3282c2",
          "name": "searchGifs",
          "request": {
            "url": "http://api.giphy.com/v1/gifs/search?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Search all GIPHY GIFs for a word or phrase. Punctuation will be stripped and ignored.  Use a plus or url encode for phrases. Example paul+rudd, ryan+gosling or american+psycho."
          },
          "response": [
            {
              "code": 200,
              "name": "Response_200",
              "id": "9a89704b-f75a-42f4-8eeb-96121d334ba5"
            }
          ]
        },
        {
          "id": "2349a5b5-c1bd-4442-b388-12e58307e38a",
          "name": "translateGif",
          "request": {
            "url": "http://api.giphy.com/v1/gifs/translate?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The translate API draws on search, but uses the GIPHY `special sauce` to handle translating from one vocabulary to another. In this case, words and phrases to GIF"
          },
          "response": [
            {
              "code": 200,
              "name": "Response_200",
              "id": "f4dbe64b-69f3-4f84-b23e-dc8a8c0ee30c"
            }
          ]
        },
        {
          "id": "d4cef419-48c8-4a9a-b11b-49a65705f032",
          "name": "trendingGifs",
          "request": {
            "url": "http://api.giphy.com/v1/gifs/trending?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Fetch GIFs currently trending online. Hand curated by the GIPHY editorial team.  The data returned mirrors the GIFs showcased on the GIPHY homepage. Returns 25 results by default."
          },
          "response": [
            {
              "code": 200,
              "name": "Response_200",
              "id": "52e81c38-0e73-40f2-979d-5089d06ef44a"
            }
          ]
        },
        {
          "id": "957dfc43-c229-400f-9990-eddbe0afb0b4",
          "name": "getGifById",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.giphy.com",
              "path": [
                "v1",
                "gifs/:gifId"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "gifId",
                  "value": "gifId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a GIF given that GIF's unique ID"
          },
          "response": [
            {
              "code": 200,
              "name": "Response_200",
              "id": "d18f6561-8d5a-4ca8-b6ad-c5a3bda71623"
            }
          ]
        }
      ]
    }
  ]
}
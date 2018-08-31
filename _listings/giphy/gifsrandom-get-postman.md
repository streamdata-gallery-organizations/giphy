{
  "info": {
    "name": "Giphy Gif API Random GIF",
    "_postman_id": "3de8cea4-a338-408b-a8ca-2aaf8faac7e2",
    "description": "Returns a random GIF, limited by tag. Excluding the tag parameter will return a random GIF from the GIPHY catalog.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Gifs",
      "item": [
        {
          "id": "e6fbcb11-86a5-4bf9-b628-a0172c6302c1",
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
              "id": "13898ce7-c7fd-4b0a-bccc-258e33485444"
            }
          ]
        },
        {
          "id": "09b467c8-578b-4ee8-a430-3bc563371f9d",
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
              "id": "3ca69c60-d769-4df2-9520-197ece255af5"
            }
          ]
        }
      ]
    }
  ]
}
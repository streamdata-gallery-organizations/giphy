---
swagger: "2.0"
x-collection-name: Giphy
x-complete: 0
info:
  title: Giphy Gif API Random GIF
  description: Returns a random GIF, limited by tag. Excluding the tag parameter will
    return a random GIF from the GIPHY catalog.
  termsOfService: https://developers.giphy.com/
  version: v1
host: api.giphy.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /gifs:
    get:
      summary: Get GIFs by ID
      description: A multiget version of the get GIF by ID endpoint.
      operationId: getGifsById
      x-api-path-slug: gifs-get
      parameters:
      - in: query
        name: No Name
      responses:
        100:
          description: Invalid API Key - The API key passed was not valid or has expired
        105:
          description: Service currently unavailable - The requested service is temporarily
            unavailable
        106:
          description: Write operation failed - The requested operation failed due
            to a temporary issue
        111:
          description: Format "xxx" not found - The requested response format was
            not found
        112:
          description: Method "xxx" not found - The requested method was not found
        114:
          description: Invalid SOAP envelope - The SOAP envelope send in the request
            could not be parsed
        115:
          description: Invalid XML-RPC Method Call - The XML-RPC request document
            could not be parsed
        116:
          description: Bad URL found - One or more arguments contained a URL that
            has been used for abuse on Flickr
      tags:
      - Gifs
  /gifs/random:
    get:
      summary: Random GIF
      description: Returns a random GIF, limited by tag. Excluding the tag parameter
        will return a random GIF from the GIPHY catalog.
      operationId: randomGif
      x-api-path-slug: gifsrandom-get
      parameters:
      - in: query
        name: No Name
      responses:
        100:
          description: Invalid API Key - The API key passed was not valid or has expired
        105:
          description: Service currently unavailable - The requested service is temporarily
            unavailable
        106:
          description: Write operation failed - The requested operation failed due
            to a temporary issue
        111:
          description: Format "xxx" not found - The requested response format was
            not found
        112:
          description: Method "xxx" not found - The requested method was not found
        114:
          description: Invalid SOAP envelope - The SOAP envelope send in the request
            could not be parsed
        115:
          description: Invalid XML-RPC Method Call - The XML-RPC request document
            could not be parsed
        116:
          description: Bad URL found - One or more arguments contained a URL that
            has been used for abuse on Flickr
      tags:
      - Gifs
      - Random
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
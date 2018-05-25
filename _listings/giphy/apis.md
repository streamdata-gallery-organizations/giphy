---
name: Giphy
x-slug: giphy
description: Giphy is a search engine for GIFs. Animated GIFs have existed for decades,
  but there was still no good way to browse and discover the best the web had to offer.
  And the vision for Giphy isn&rsquo;t really just about finding GIFs. It&rsquo;s
  a search engine today but soon you&rsquo;ll see it grow into a community, a platform
  with a host of features targeted at gif artists, enthusiasts, bloggers, and anyone
  generally looking to discover or create that next big meme.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/giphy-logo.png
x-kinRank: "9"
x-alexaRank: ""
tags: Giphy
created: "2018-05-25"
modified: "2018-05-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/apis.md
specificationVersion: "0.14"
apis:
- name: Giphy Gif API Get GIFs by ID
  x-api-slug: giphy-gif-api
  description: A multiget version of the get GIF by ID endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/giphy-logo.png
  humanURL: https://giphy.com
  baseURL: http://api.giphy.com//v1//gifs
  tags: Gifs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/gifs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/gifs-get-openapi.md
- name: Giphy Gif API Random GIF
  x-api-slug: giphy-gif-api
  description: Returns a random GIF, limited by tag. Excluding the tag parameter will
    return a random GIF from the GIPHY catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/giphy-logo.png
  humanURL: https://giphy.com
  baseURL: http://api.giphy.com//v1//gifs/random
  tags: Gifs, Random
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/gifsrandom-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/gifsrandom-get-openapi.md
- name: Giphy Gif API Search GIFs
  x-api-slug: giphy-gif-api
  description: Search all GIPHY GIFs for a word or phrase. Punctuation will be stripped
    and ignored.  Use a plus or url encode for phrases. Example paul+rudd, ryan+gosling
    or american+psycho.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/giphy-logo.png
  humanURL: https://giphy.com
  baseURL: http://api.giphy.com//v1//gifs/search
  tags: Gifs, Search
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/gifssearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/gifssearch-get-openapi.md
- name: Giphy Gif API Translate phrase to GIF
  x-api-slug: giphy-gif-api
  description: The translate API draws on search, but uses the GIPHY `special sauce`
    to handle translating from one vocabulary to another. In this case, words and
    phrases to GIF
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/giphy-logo.png
  humanURL: https://giphy.com
  baseURL: http://api.giphy.com//v1//gifs/translate
  tags: Gifs, Translate
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/gifstranslate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/gifstranslate-get-openapi.md
- name: Giphy Gif API Trending GIFs
  x-api-slug: giphy-gif-api
  description: Fetch GIFs currently trending online. Hand curated by the GIPHY editorial
    team.  The data returned mirrors the GIFs showcased on the GIPHY homepage. Returns
    25 results by default.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/giphy-logo.png
  humanURL: https://giphy.com
  baseURL: http://api.giphy.com//v1//gifs/trending
  tags: Gifs, Trending
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/gifstrending-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/gifstrending-get-openapi.md
- name: Giphy Gif API Get GIF by Id
  x-api-slug: giphy-gif-api
  description: Returns a GIF given that GIF's unique ID
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/giphy-logo.png
  humanURL: https://giphy.com
  baseURL: http://api.giphy.com//v1//gifs/{gifId}
  tags: Gifs, Gif
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/gifsgifid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/gifsgifid-get-openapi.md
- name: Giphy Gif API Random Sticker
  x-api-slug: giphy-gif-api
  description: Returns a random GIF, limited by tag. Excluding the tag parameter will
    return a random GIF from the GIPHY catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/giphy-logo.png
  humanURL: https://giphy.com
  baseURL: http://api.giphy.com//v1//stickers/random
  tags: Stickers, Random
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/stickersrandom-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/stickersrandom-get-openapi.md
- name: Giphy Gif API Search Stickers
  x-api-slug: giphy-gif-api
  description: Replicates the functionality and requirements of the classic GIPHY
    search, but returns animated stickers rather than GIFs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/giphy-logo.png
  humanURL: https://giphy.com
  baseURL: http://api.giphy.com//v1//stickers/search
  tags: Stickers, Search
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/stickerssearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/stickerssearch-get-openapi.md
- name: Giphy Gif API Translate phrase to Sticker
  x-api-slug: giphy-gif-api
  description: The translate API draws on search, but uses the GIPHY `special sauce`
    to handle translating from one vocabulary to another. In this case, words and
    phrases to GIFs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/giphy-logo.png
  humanURL: https://giphy.com
  baseURL: http://api.giphy.com//v1//stickers/translate
  tags: Stickers, Translate
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/stickerstranslate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/stickerstranslate-get-openapi.md
- name: Giphy Gif API Trending Stickers
  x-api-slug: giphy-gif-api
  description: Fetch Stickers currently trending online. Hand curated by the GIPHY
    editorial team. Returns 25 results by default.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/giphy-logo.png
  humanURL: https://giphy.com
  baseURL: http://api.giphy.com//v1//stickers/trending
  tags: Stickers, Trending
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/stickerstrending-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/stickerstrending-get-openapi.md
- name: Giphy Gif API
  x-api-slug: giphy-gif-api
  description: Giphy is an animated search engine for discovering and sharing GIF
    images. Giphy exposes its search capabilities through a RESTlike API. The API
    is comprised of nine JSON endpoints, allowing developers to search for GIFs using
    a variety of filters and search parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/giphy-logo.png
  humanURL: https://giphy.com
  baseURL: http://api.giphy.com//v1
  tags: Giphy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/giphy/master/_listings/giphy/openapi.md
x-common:
- type: x-blog
  url: http://blog.giphy.com/
- type: x-developer
  url: https://api.giphy.com/
- type: x-github
  url: https://github.com/Giphy
- type: x-twitter
  url: https://twitter.com/giphy
- type: x-website
  url: https://giphy.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
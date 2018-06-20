---
swagger: "2.0"
x-collection-name: Flickr
x-complete: 1
info:
  title: Flickr
  description: explore-upload-and-organize-photos-on-flickr
  version: 1.0.0
host: api.flickr.com
basePath: /services/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/?method=flickr.groups.browse:
    get:
      summary: Groups Browse
      description: Browse the group category tree, finding groups and sub-categories.
      operationId: getRestMethodFlickr.groups.browse
      x-api-path-slug: restmethodflickr-groups-browse-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: cat_id
        description: The category id to fetch a list of groups and sub-categories
          for
      - in: query
        name: format
        description: Response format
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Browse
---
---
swagger: "2.0"
x-collection-name: New Relic
x-complete: 1
info:
  title: New Relic
  version: 1.0.0
basePath: v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /browser_applications.{format}:
    get:
      summary: Get Browser Applications. Format
      description: |-
        This API endpoint returns a list of the Browser Applications associated with your New Relic account.

        Browser Applications can be filtered by their name, or by the application IDs.
      operationId: getBrowserApplications.Format
      x-api-path-slug: browser-applications-format-get
      parameters:
      - in: query
        name: filter[ids]
        description: Filter by application ids
        type: list
      - in: query
        name: filter[name]
        description: Filter by application name
        type: string
      - in: query
        name: page
        description: Pagination index
        type: integer
      responses:
        200:
          description: OK
      tags:
      - Browser
      - Applications.
      - Format
    post:
      summary: Add Browser Applications. Format
      description: This API endpoint allows you to create a standalone Browser Application.
      operationId: postBrowserApplications.Format
      x-api-path-slug: browser-applications-format-post
      parameters:
      - in: body
        name: browser_application
        description: Browser Application Schema
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Browser
      - Applications.
      - Format
---